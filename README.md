# gulp-coffeetape [![NPM version][npm-image]][npm-url] [![Build Status][travis-image]][travis-url] [![Dependency Status][daviddm-image]][daviddm-url] [![Coverage percentage][coveralls-image]][coveralls-url]
> Run Tape tests written in CoffeeScript

# NOTICE: No longer maintained. Feel free to use/create a fork if you are interested.

This is a node application generated using [generator-coffee-node](https://github.com/jhessin/generator-coffee-node).

## Usage

By default this project will compile any coffeescript you put in the `src/` directory and place it in a `lib/` directory (customizable in gulpfile.coffee).

The entry point of the program will be `src/index.coffee` by default. This can be customized by modifying your `package.json`&#39;s `main` entry from `lib/index.js`, but it is simpler to just `import` or `require` what you need in the index.coffee file.

## License

MIT © [Jim Hessin](http://www.grillbrickstudios.com)


[npm-image]: https://badge.fury.io/js/gulp-coffeetape.svg
[npm-url]: https://npmjs.org/package/gulp-coffeetape
[travis-image]: https://travis-ci.org/jhessin/gulp-coffeetape.svg?branch=master
[travis-url]: https://travis-ci.org/jhessin/gulp-coffeetape
[daviddm-image]: https://david-dm.org/jhessin/gulp-coffeetape.svg?theme=shields.io
[daviddm-url]: https://david-dm.org/jhessin/gulp-coffeetape
[coveralls-image]: https://coveralls.io/repos/jhessin/gulp-coffeetape/badge.svg
[coveralls-url]: https://coveralls.io/r/jhessin/gulp-coffeetape
