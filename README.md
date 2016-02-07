# Contramonkey

A [Ghost](https://ghost.org/) theme.

## Setup

Use the [ghost-local](https://github.com/bergren2/ghost-local) project to set-up
a development environment, then clone this repository into `content/themes/contramonkey`.

Once cloned, change to the `contramonkey` directory and run the following:

    $ npm install
    $ bundle install

## Development

From within the `contramonkey` directory, run

    $ sass --watch assets/sass:assets/css

Commit both Sass and CSS files, since the CSS will be used directly by Ghost in
production without compilation.

Useful Links:
- [Ghost Theme Docs](https://themes.ghost.org/docs/)

## License

See LICENSE for details.
