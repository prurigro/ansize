# ansize-stdout #

A fork of [Ansize](https://github.com/jhchen/ansize) that puts its focus on displaying images.

## DETAILS ##

This fork differs from the upstream project in two key ways:

1. It sends the rendered image to stdout without writing anything to file.
2. The width argument is optional, and the width of the terminal is used in its place when it isn't provided.

The rendering functionality works the same way as it does upstream in [Ansize](https://github.com/jhchen/ansize).

## INSTALLATION ##

    go get github.com/prurigro/ansize-stdout

## USAGE ##

* Display the image with a specified column width: `ansize-stdout <image> [width]`
* Display the image at the terminal width: `ansize-stdout <image>`

## CREDITS ##

* The [Ansize](https://github.com/jhchen/ansize) project: [Jason Chen](https://github.com/jhchen)
* The [ansize-stdout](https://github.com/prurigro/ansize-stdout) fork: [Kevin MacMartin](https://github.com/prurigro)

## LICENSE ##

Released under the [MIT license](http://opensource.org/licenses/MIT).
