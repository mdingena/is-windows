# is-windows [![NPM version](https://img.shields.io/npm/v/is-windows.svg?style=flat)](https://www.npmjs.com/package/is-windows) [![NPM monthly downloads](https://img.shields.io/npm/dm/is-windows.svg?style=flat)](https://npmjs.org/package/is-windows)  [![NPM total downloads](https://img.shields.io/npm/dt/is-windows.svg?style=flat)](https://npmjs.org/package/is-windows) [![Linux Build Status](https://img.shields.io/travis/jonschlinkert/is-windows.svg?style=flat&label=Travis)](https://travis-ci.org/jonschlinkert/is-windows)

> Returns true if the platform is windwows.

## Install

Install with [npm](https://www.npmjs.com/):

```sh
$ npm install --save is-windows
```

## Heads up!

As of `v0.2.0` this module always returns a function.

## Usage

```js
var isWindows = require('is-windows');

isWindows();
//=> returns true if the platform is windows
```

## About

### Related projects

* [is-absolute](https://www.npmjs.com/package/is-absolute): Polyfill for node.js `path.isAbolute`. Returns true if a file path is absolute. | [homepage](https://github.com/jonschlinkert/is-absolute "Polyfill for node.js `path.isAbolute`. Returns true if a file path is absolute.")
* [is-glob](https://www.npmjs.com/package/is-glob): Returns `true` if the given string looks like a glob pattern or an extglob pattern… [more](https://github.com/jonschlinkert/is-glob) | [homepage](https://github.com/jonschlinkert/is-glob "Returns `true` if the given string looks like a glob pattern or an extglob pattern. This makes it easy to create code that only uses external modules like node-glob when necessary, resulting in much faster code execution and initialization time, and a bet")
* [is-relative](https://www.npmjs.com/package/is-relative): Returns `true` if the path appears to be relative. | [homepage](https://github.com/jonschlinkert/is-relative "Returns `true` if the path appears to be relative.")
* [isobject](https://www.npmjs.com/package/isobject): Returns true if the value is an object and not an array or null. | [homepage](https://github.com/jonschlinkert/isobject "Returns true if the value is an object and not an array or null.")
* [window-size](https://www.npmjs.com/package/window-size): Reliable way to to get the height and width of the terminal/console in a node.js… [more](https://github.com/jonschlinkert/window-size) | [homepage](https://github.com/jonschlinkert/window-size "Reliable way to to get the height and width of the terminal/console in a node.js environment.")

### Contributing

Pull requests and stars are always welcome. For bugs and feature requests, [please create an issue](../../issues/new).

### Contributors

| **Commits** | **Contributor**<br/> | 
| --- | --- |
| 8 | [jonschlinkert](https://github.com/jonschlinkert) |
| 1 | [gucong3000](https://github.com/gucong3000) |

### Building docs

_(This document was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme) (a [verb](https://github.com/verbose/verb) generator), please don't edit the readme directly. Any changes to the readme must be made in [.verb.md](.verb.md).)_

To generate the readme and API documentation with [verb](https://github.com/verbose/verb):

```sh
$ npm install -g verb verb-generate-readme && verb
```

### Running tests

Install dev dependencies:

```sh
$ npm install -d && npm test
```

### Author

**Jon Schlinkert**

* [github/jonschlinkert](https://github.com/jonschlinkert)
* [twitter/jonschlinkert](http://twitter.com/jonschlinkert)

### License

Copyright © 2016, [Jon Schlinkert](https://github.com/jonschlinkert).
Released under the [MIT license](https://github.com/jonschlinkert/is-windows/blob/master/LICENSE).

***

_This file was generated by [verb-generate-readme](https://github.com/verbose/verb-generate-readme), v0.2.0, on December 08, 2016._