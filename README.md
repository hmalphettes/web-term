<!---------------------------------------------------------------------------->
<!-- STOP, LOOK & LISTEN!                                                   -->
<!-- ====================                                                   -->
<!-- Do NOT edit this file directly since it's generated from a template    -->
<!-- file, using https://github.com/IonicaBizau/node-blah                   -->
<!--                                                                        -->
<!-- If you found a typo in documentation, fix it in the source files       -->
<!-- (`lib/*.js`) and make a pull request.                                  -->
<!--                                                                        -->
<!-- If you have any other ideas, open an issue.                            -->
<!--                                                                        -->
<!-- Please consider reading the contribution steps (CONTRIBUTING.md).      -->
<!-- * * * Thanks! * * *                                                    -->
<!---------------------------------------------------------------------------->

![web-term](http://i.imgur.com/3kMJhvc.png)

# `$ web-term` [![Donate now][donate-now]][paypal-donations]

A full screen terminal in your browser.

## Installation

```sh
$ npm i web-term
```

### CLI Usage
You can install the package globally and use it as command line tool:

```sh
$ npm i -g web-term
```

Then, run `web-term --help` and see what the cli tool can do.

## Usage
Run `web-term` and then open `localhost:9000` in your web browser. If you want to configure the things, run `web-term -h`
and see what are the available options.

```sh
$ web-term -h
Usage: web-term [options]

Options:
  -p, --port <port>      The web term server port.
  -d, --daemon           Start web term as background process.
  -c, --cwd <path>       The path to the web terminal current working
                         directory.
  -o, --open             If provided, the web term will be automatically
                         opened in the default browser.
  -b, --shell <program>  The shell program. By default `bash`.
  -s, --start <program>  The start program.
  -h, --help             Displays this help.
  -v, --version          Displays version information.

Examples:
  web-term # Default behavior
  web-term -p 8080 # start on localhost:8080
  web-term -d # daemonize
  web-term -c path/to/some/dir
  web-term -o # Opens the web-term in the browser
  web-term -s alsamixer # Opens alsamixer in the browser

Documentation can be found at https://github.com/IonicaBizau/web-term
```

## Screenshots

### VIM
![](http://i.imgur.com/49FTpfI.png)

### Alsamixer
![](http://i.imgur.com/rJbtLdi.jpg)

## Thanks
This project is highly based on [`tty.js`](https://github.com/chjj/tty.js) created by [@chjj](https://github.com/chjj). Thanks a lot for this awesome stuff!

## Documentation

For full API reference, see the [DOCUMENTATION.md][docs] file.

## How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].

## License
[KINDLY][license] © [Ionică Bizău][website]–The [LICENSE](/LICENSE) file contains
a copy of the license.

[license]: http://ionicabizau.github.io/kindly-license/?author=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica@gmail.com%3E&year=2015
[contributing]: /CONTRIBUTING.md
[website]: http://ionicabizau.net
[docs]: /DOCUMENTATION.md
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MG98D7NPFZ3MG
[donate-now]: http://i.imgur.com/jioicaN.png