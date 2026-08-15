# Awesome ECMAScript 6 Tools with stars

## Transpilers

* [Babel](https://github.com/babel/babel) ⭐ 43,983 | 🐛 770 | 🌐 TypeScript | 📅 2026-08-14 - Turn ES6+ code into vanilla ES5 with no runtime
* [Traceur compiler](https://github.com/google/traceur-compiler) ⚠️ Archived - ES6 features > ES5. Includes classes, generators, promises, destructuring patterns, default parameters & more.
* [Lebab](https://github.com/mohebifar/lebab) ⭐ 5,638 | 🐛 39 | 🌐 JavaScript | 📅 2026-04-01 - Transformations for ES5 code to ES6 (approximates)
* Facebook's [regenerator](https://github.com/facebook/regenerator) ⚠️ Archived - transform ES6 yield/generator functions to ES5
* [babelify](https://github.com/babel/babelify) ⭐ 1,677 | 🐛 12 | 🌐 JavaScript | 📅 2021-08-06 - Babel transpiler wrapped as a [Browserify](http://browserify.org/) transform
* Square's [es6-module-transpiler](https://github.com/esnext/es6-module-transpiler) ⚠️ Archived - ES6 modules to AMD or CJS
* [es6ify](https://github.com/thlorenz/es6ify) ⭐ 590 | 🐛 15 | 🌐 JavaScript | 📅 2017-06-12 - Traceur compiler wrapped as a [Browserify](http://browserify.org/) v2 transform
* Facebook's [jstransform](https://github.com/facebookarchive/jstransform) ⚠️ Archived - A simple utility for pluggable JS syntax transforms. Comes with a small set of ES6 -> ES5 transforms
* [regexpu](https://github.com/mathiasbynens/regexpu) ⭐ 242 | 🐛 3 | 🌐 JavaScript | 📅 2024-09-18 — Transform Unicode-aware ES6 regular expressions to ES5
* [Some Sweet.js macros](https://github.com/jlongster/es6-macros) ⭐ 239 | 🐛 13 | 🌐 JavaScript | 📅 2014-07-04 that compile from ES6 to ES5
* [es6-transpiler](https://github.com/termi/es6-transpiler) ⭐ 215 | 🐛 38 | 🌐 JavaScript | 📅 2015-07-19 - ES6 > ES5. Includes classes, destructuring, default parameters, spread
* [defs](https://github.com/olov/defs) ⭐ 114 | 🐛 1 | 🌐 JavaScript | 📅 2019-11-06 - ES6 block-scoped const and let variables to ES3 vars
* [es6\_module\_transpiler-rails](https://github.com/DavyJonesLocker/es6_module_transpiler-rails) ⭐ 87 | 🐛 0 | 🌐 JavaScript | 📅 2014-12-09 - ES6 Modules in the Rails Asset Pipeline
* Bitovi's [transpile](https://github.com/stealjs/transpile) ⭐ 25 | 🐛 21 | 🌐 JavaScript | 📅 2022-06-01 - Converts ES6 to AMD, CJS, and StealJS.

## Build-time transpilation

### Gulp Plugins

* Babel: [gulp-babel](https://github.com/babel/gulp-babel) ⭐ 1,307 | 🐛 33 | 🌐 JavaScript | 📅 2026-07-21
* TypeScript: [gulp-typescript](https://github.com/ivogabe/gulp-typescript) ⭐ 852 | 🐛 62 | 🌐 JavaScript | 📅 2023-02-02
* Traceur: [gulp-traceur](https://github.com/sindresorhus/gulp-traceur) ⚠️ Archived
* ES6 Module Transpiler: [gulp-es6-module-transpiler](https://github.com/ryanseddon/gulp-es6-module-transpiler) ⭐ 61 | 🐛 6 | 🌐 JavaScript | 📅 2022-03-09
* es6-transpiler: [gulp-es6-transpiler](https://github.com/sindresorhus/gulp-es6-transpiler) ⚠️ Archived - ES6 → ES5
* Regenerator: [gulp-regenerator](https://github.com/sindresorhus/gulp-regenerator) ⚠️ Archived
* es6-jstransform: [gulp-jstransform](https://github.com/hemanth/gulp-jstransform) ⭐ 16 | 🐛 20 | 🌐 JavaScript | 📅 2026-01-29 - ES6 → ES5 using FB's [jstransform](https://github.com/facebook/jstransform) ⚠️ Archived
* regexpu: [gulp-regexpu](https://github.com/mathiasbynens/gulp-regexpu) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2015-02-15

### Grunt Tasks

* Babel: [grunt-babel](https://github.com/babel/grunt-babel) ⭐ 434 | 🐛 24 | 🌐 JavaScript | 📅 2026-06-18 - Turn ES6+ code into vanilla ES5 with no runtime
* TypeScript: [grunt-ts](https://github.com/TypeStrong/grunt-ts) ⭐ 327 | 🐛 81 | 🌐 JavaScript | 📅 2022-12-07 - ES6+ > ES5/ES3 transpilation
* Traceur: [grunt-traceur](https://github.com/aaronfrost/grunt-traceur) ⭐ 202 | 🐛 9 | 🌐 JavaScript | 📅 2022-12-06 ES6 > ES5 transpilation, [grunt-traceur-build](https://github.com/tarruda/grunt-traceur-build) ⭐ 8 | 🐛 1 | 🌐 JavaScript | 📅 2016-02-21
* ES6 Module Transpiler: [grunt-es6-module-transpiler](https://github.com/joefiorini/grunt-es6-module-transpiler) ⭐ 83 | 🐛 3 | 🌐 JavaScript | 📅 2016-02-20
* [grunt-microlib](https://github.com/thomasboyt/grunt-microlib) ⚠️ Archived - tools for libs using ES6 module transpiler (sample [Gruntfile](https://github.com/jakearchibald/es6-promise/blob/c3336087fffc52e66cf5398e5b56b23a291080fc/Gruntfile.js) ⭐ 7,255 | 🐛 26 | 🌐 JavaScript | 📅 2022-11-14)
* Regenerator: [grunt-regenerator](https://github.com/sindresorhus/grunt-regenerator) ⚠️ Archived - ES6 generator functions to ES5
* es6-transpiler: [grunt-es6-transpiler](https://github.com/sindresorhus/grunt-es6-transpiler) ⚠️ Archived - ES6 → ES5
* [grunt-defs](https://github.com/EE/grunt-defs) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2017-08-16 - ES6 block scoped const and let variables, to ES3

### Broccoli Plugins

* Babel: [broccoli-babel-transpiler](https://github.com/babel/broccoli-babel-transpiler) ⭐ 58 | 🐛 19 | 🌐 JavaScript | 📅 2025-04-01
* Traceur: [broccoli-traceur](https://github.com/sindresorhus/broccoli-traceur) ⚠️ Archived
* ES6 Transpiler: [broccoli-transpiler](https://github.com/sindresorhus/broccoli-es6-transpiler) ⚠️ Archived
* Regenerator: [broccoli-regenerator](https://github.com/sindresorhus/broccoli-regenerator) ⚠️ Archived
* ES6 Module Transpiler: [broccoli-es6-module-transpiler](https://github.com/mmun/broccoli-es6-module-transpiler) ⭐ 5 | 🐛 3 | 🌐 JavaScript | 📅 2014-12-16
* ES6 fat arrow transpiler: [broccoli-es6-arrow](https://github.com/hemanth/broccoli-es6-arrow.git) ⭐ 5 | 🐛 12 | 🌐 JavaScript | 📅 2023-12-01
* TypeScript: [broccoli-tsc](https://github.com/ngParty/broccoli-tsc) ⭐ 1 | 🐛 3 | 🌐 TypeScript | 📅 2015-05-20

### Brunch Plugins

* Babel: [babel-brunch](https://github.com/babel/babel-brunch) ⭐ 69 | 🐛 1 | 🌐 JavaScript | 📅 2021-08-10
* ES6 Module Transpiler: [es6-module-transpiler-brunch](https://github.com/gcollazo/es6-module-transpiler-brunch) ⚠️ Archived
* TypeScript: [typescript-brunch](https://github.com/joshheyse/typescript-brunch)

## Webpack plugins

* Babel: [babel-loader](https://github.com/babel/babel-loader) ⭐ 4,839 | 🐛 65 | 🌐 JavaScript | 📅 2026-08-04
* TypeScript: [awesome-typescript-loader](https://github.com/s-panferov/awesome-typescript-loader) ⚠️ Archived
* Traceur: [traceur-compiler-loader](https://github.com/gdi2290/traceur-compiler-loader) ⭐ 4 | 🐛 0 | 🌐 JavaScript | 📅 2015-03-08

## Duo plugins

* Babel: [duo-babel](https://github.com/babel/duo-babel) ⚠️ Archived
* TypeScript: [duo-typescript](https://github.com/frankwallis/duo-typescript) ⭐ 1 | 🐛 1 | 🌐 JavaScript | 📅 2015-06-10

## Connect plugins

* Babel: [babel-connect](https://github.com/babel/babel-connect) ⚠️ Archived
* TypeScript: [typescript-middleware](https://github.com/brn/typescript-middleware) ⭐ 9 | 🐛 4 | 🌐 JavaScript | 📅 2017-03-02

## Gobble plugins

* Babel: [gobble-babel](https://github.com/babel/gobble-babel) ⚠️ Archived
* Traceur: [gobble-es6-transpiler](https://github.com/gobblejs/gobble-es6-transpiler) ⭐ 2 | 🐛 0 | 🌐 JavaScript | 📅 2015-01-12

## Jade plugins

* Babel: [jade-babel](https://github.com/babel/jade-babel) ⚠️ Archived
* Traceur: [jade-traceur](https://www.npmjs.com/package/jade-traceur)

## Jest plugins

* Babel: [babel-jest](https://github.com/babel/babel-jest) ⚠️ Archived

## Karma plugins

* Babel: [karma-babel-preprocessor](https://github.com/babel/karma-babel-preprocessor) ⭐ 168 | 🐛 8 | 🌐 JavaScript | 📅 2023-09-25
* TypeScript: [karma-typescript-preprocessor](https://github.com/sergeyt/karma-typescript-preprocessor) ⭐ 49 | 🐛 22 | 🌐 TypeScript | 📅 2022-12-03
* Traceur: [karma-traceur-preprocessor](https://github.com/karma-runner/karma-traceur-preprocessor) ⚠️ Archived

## Sprockets plugins

* TypeScript: [typescript-rails](https://github.com/typescript-ruby/typescript-rails) ⭐ 254 | 🐛 18 | 🌐 Ruby | 📅 2016-11-13
* Traceur: [sprockets-traceur](https://github.com/gunpowderlabs/sprockets-traceur) ⭐ 24 | 🐛 2 | 🌐 Ruby | 📅 2015-10-07
* Babel: [sprockets-es6](https://github.com/josh/sprockets-es6)

## Browser plugins

* [Scratch JS](https://github.com/richgilbank/Scratch-JS) ⭐ 349 | 🐛 26 | 🌐 JavaScript | 📅 2022-08-06 - A Chrome/Opera DevTools extension to run ES6 on a page with either Babel or Traceur
* [generator-typescript](https://github.com/mrkev/generator-typescript) ⭐ 19 | 🐛 0 | 🌐 JavaScript | 📅 2017-05-03 - Yeoman generator for TypeScript apps

## Mocha plugins

* [Mocha Traceur](https://github.com/domenic/mocha-traceur) ⭐ 15 | 🐛 2 | 🌐 JavaScript | 📅 2017-05-19 - A simple plugin for Mocha to pass JS files through the Traceur compiler

## Module Loaders

* [Babel Module Loader](https://github.com/babel/babel-loader) ⭐ 4,839 | 🐛 65 | 🌐 JavaScript | 📅 2026-08-04
* ES6 [Module Loader polyfill](https://github.com/ModuleLoader/es6-module-loader) ⚠️ Archived (compat with latest spec and Traceur)
* [js-loaders](https://github.com/jorendorff/js-loaders) ⚠️ Archived - Mozilla's spec-compliant loader prototype
* [beck.js](https://github.com/unscriptable/beck) ⭐ 5 | 🐛 0 | 🌐 JavaScript | 📅 2013-12-17 - toolkit for ES6 Module Loader pipelines, shim for legacy environments
* [JSPM](http://jspm.io/) - ES6, AMD, CJS module loading/package management

## Boilerplates

* [es6-jspm-gulp-boilerplate](https://github.com/alexweber/es6-jspm-gulp-boilerplate) ⭐ 136 | 🐛 7 | 🌐 JavaScript | 📅 2016-08-11 - Tooling to allow the community to use es6 now via babel in conjunction jspm, with source maps, concatenation, minification, compression, and unit testing in real browsers using es6.
* [es6-boilerplate](https://github.com/davidjnelson/es6-boilerplate) ⭐ 87 | 🐛 0 | 🌐 JavaScript | 📅 2018-02-06 - Tooling to allow the community to use es6 now via traceur in conjunction with amd and browser global modules, with source maps, concatenation, minification, compression, and unit testing in real browsers.

## Code generation

* [Loom generators with ES6 ember modules](https://github.com/ryanflorence/loom-generators-ember) ⭐ 15 | 🐛 3 | 🌐 JavaScript | 📅 2013-11-30
* [generator-es6-babel](https://github.com/HenriqueLimas/generator-es6-babel) ⭐ 10 | 🐛 0 | 🌐 JavaScript | 📅 2015-09-05 - Yeoman generator for Babel apps
* [generator-node-esnext](https://github.com/briandipalma/generator-node-esnext) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2014-11-18 - Yeoman generator for Traceur apps
* [generator-gulp-babelify](https://github.com/HenriqueLimas/generator-gulp-babelify) ⭐ 3 | 🐛 0 | 🌐 JavaScript | 📅 2015-12-11 - Yeoman generator for [Babel](https://babeljs.io/), [Browserify](http://browserify.org/) and [Gulp](http://gulpjs.com/)
* [grunt-init-es6](https://www.npmjs.com/package/grunt-init-es6) - scaffold node modules with unit tests, authored in ES6
* Brunch [plugin](https://www.npmjs.com/package/es6-module-transpiler-brunch) for ES6 module transpilation

## Polyfills

* [core-js](https://github.com/zloirock/core-js) ⭐ 25,517 | 🐛 44 | 🌐 JavaScript | 📅 2026-08-15 - Modular and compact polyfills for ES6 including Symbols, Map, Set, Iterators, Promises, setImmediate, Array generics, etc. The standard library used by [Babel](https://github.com/babel/babel) ⭐ 43,983 | 🐛 770 | 🌐 TypeScript | 📅 2026-08-14.
* [es6-promise](https://github.com/jakearchibald/es6-promise) ⭐ 7,255 | 🐛 26 | 🌐 JavaScript | 📅 2022-11-14 - polyfill for Promises matching the ES6 API
* [es6-shim](https://github.com/paulmillr/es6-shim) ⭐ 3,101 | 🐛 35 | 🌐 JavaScript | 📅 2026-04-16 - almost all new ES6 methods — from Map, Set, String, Array, Object, Object.is and more.
* [ES6 shim](https://github.com/inexorabletash/polyfill/blob/master/es6.md) ⚠️ Archived
* [`Object.assign`](https://github.com/sindresorhus/object-assign) ⭐ 917 | 🐛 0 | 🌐 JavaScript | 📅 2023-11-05
* [harmony-reflect](https://github.com/tvcutsem/harmony-reflect) ⭐ 482 | 🐛 8 | 🌐 JavaScript | 📅 2024-01-15 - ES6 [reflection module](http://wiki.ecmascript.org/doku.php?id=harmony:reflect_api) (contains the [Proxy API](http://soft.vub.ac.be/~tvcutsem/proxies/))
* [ES6 Symbol polyfill](https://github.com/medikoo/es6-symbol) ⭐ 179 | 🐛 2 | 🌐 JavaScript | 📅 2024-03-01
* [`String.prototype.startsWith`](https://github.com/mathiasbynens/String.prototype.startsWith) ⭐ 142 | 🐛 0 | 🌐 JavaScript | 📅 2024-09-27
* [`String.prototype.includes`](https://github.com/mathiasbynens/String.prototype.includes) ⭐ 69 | 🐛 2 | 🌐 JavaScript | 📅 2024-10-15
* [`Array.from`](https://github.com/mathiasbynens/Array.from) ⭐ 67 | 🐛 0 | 🌐 JavaScript | 📅 2024-03-23
* [`String.fromCodePoint`](https://github.com/mathiasbynens/String.fromCodePoint) ⭐ 60 | 🐛 0 | 🌐 JavaScript | 📅 2024-02-06
* [`String.prototype.codePointAt`](https://github.com/mathiasbynens/String.prototype.codePointAt) ⭐ 55 | 🐛 0 | 🌐 JavaScript | 📅 2024-10-17
* [`String.prototype.at`](https://github.com/mathiasbynens/String.prototype.at) ⚠️ Archived
* Polymer's [WeakMap shim](https://github.com/Polymer/WeakMap) ⚠️ Archived
* [`Array.prototype.find`](https://github.com/paulmillr/Array.prototype.find) ⭐ 38 | 🐛 1 | 🌐 JavaScript | 📅 2024-03-19
* [`String.prototype.endsWith`](https://github.com/mathiasbynens/String.prototype.endsWith) ⭐ 36 | 🐛 1 | 🌐 JavaScript | 📅 2024-03-20
* [`String.prototype.repeat`](https://github.com/mathiasbynens/String.prototype.repeat) ⭐ 28 | 🐛 2 | 🌐 JavaScript | 📅 2021-01-16
* [`Array.prototype.findIndex`](https://github.com/paulmillr/Array.prototype.findIndex) ⭐ 28 | 🐛 0 | 🌐 JavaScript | 📅 2024-12-17
* [ES6 Map Shim](https://github.com/eriwen/es6-map-shim) ⚠️ Archived - destructive shim that follows the latest specification as closely as possible.
* [`Number.isFinite`](https://github.com/sindresorhus/is-finite) ⚠️ Archived
* [`Array.of`](https://github.com/mathiasbynens/Array.of) ⭐ 16 | 🐛 0 | 🌐 JavaScript | 📅 2024-09-05
* [`Math.sign`](https://github.com/sindresorhus/math-sign) ⚠️ Archived
* [`RegExp.prototype.match`](https://github.com/mathiasbynens/RegExp.prototype.match) ⭐ 10 | 🐛 1 | 🌐 JavaScript | 📅 2014-07-20
* [`Function.create`](https://github.com/walling/Function.create.js) ⭐ 7 | 🐛 0 | 🌐 JavaScript | 📅 2013-02-17
* [`RegExp.prototype.search`](https://github.com/mathiasbynens/RegExp.prototype.search) ⭐ 5 | 🐛 1 | 🌐 JavaScript | 📅 2014-07-20
* [ES6 Map, Set, WeakMap](https://github.com/EliSnow/Blitz-Collections) ⚠️ Archived
* [WeakMap, Map, Set, HashMap - ES6 Collections](https://github.com/Benvie/harmony-collections)
* [ES5 based shims in pure CJS style](https://gist.github.com/medikoo/102b7d0e697627133788#list-of-ecmascript-6-shims) -  Array, Object, Number, Math and String functions/methods, plus Map, Set, Symbol and WeakMap objects

## Editors

* Grammar and transpilation [package](https://github.com/gandm/language-babel) ⭐ 472 | 🐛 42 | 🌐 CoffeeScript | 📅 2020-01-15  for [Atom](https://atom.io/)
* ES6 syntax highlighting for [Sublime Text and TextMate](https://github.com/Benvie/JavaScriptNext.tmLanguage) ⭐ 33 | 🐛 8 | 📅 2018-07-16
* ES6 syntax support in [WebStorm](https://www.jetbrains.com/webstorm/) and [PhpStorm](https://www.jetbrains.com/phpstorm/), compilation to ES5 with [file watchers or task runners](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)
* DocPad [plugin](https://github.com/pflannery/docpad-plugin-traceur) for Traceur
* Learn ES6 transpilation options in Webstorm [Read Blog Post](http://blog.jetbrains.com/webstorm/2015/05/ecmascript-6-in-webstorm-transpiling/)

## Parsers

* [Acorn](https://github.com/ternjs/acorn) ⭐ 11,429 | 🐛 17 | 🌐 JavaScript | 📅 2026-07-28 - A small, fast, JavaScript-based JavaScript parser with ES6 support, parses to [SpiderMonkey AST](https://developer.mozilla.org/en-US/docs/Mozilla/Projects/SpiderMonkey/Parser_API) format.
* [Traceur compiler](https://github.com/google/traceur-compiler) ⚠️ Archived also has built-in parser available under `traceur.syntax.Parser`.
* [Esprima](http://esprima.org) - JavaScript parser supporting ES6, parses to [ESTree AST format](https://github.com/estree/estree) ⭐ 5,422 | 🐛 44 | 📅 2026-05-01
* [esparse](https://github.com/zenparsing/esparse) ⭐ 115 | 🐛 0 | 🌐 JavaScript | 📅 2018-09-21 - ES6 parser written in ES6.

## Other

* [Recast](https://github.com/benjamn/recast) ⭐ 5,253 | 🐛 201 | 🌐 TypeScript | 📅 2026-08-10 - Esprima-based JavaScript syntax tree transformer, conservative pretty-printer, and automatic source map generator. Used by several of the transpilers listed above, including [regenerator](https://github.com/facebook/regenerator) ⚠️ Archived and [es6-arrow-function](https://github.com/esnext/es6-arrow-function) ⚠️ Archived.
* [Isparta](https://github.com/douglasduteil/isparta) ⚠️ Archived
* [Paws on ES6](https://github.com/hemanth/paws-on-es6) ⭐ 329 | 🐛 0 | 🌐 JavaScript | 📅 2017-04-03 -  Minimalist examples of ES6 functionalities.
* [ES.next showcase](https://github.com/sindresorhus/esnext-showcase) ⚠️ Archived - real-world usage examples of ES6 features
* [let-er](https://github.com/getify/let-er) ⚠️ Archived - transpiles [let-block block-scoping](http://wiki.ecmascript.org/doku.php?id=proposals:block_expressions#let_statement) (not accepted into ES6) into either ES3 or ES6
* [es-dependency-graph](https://github.com/yahoo/es-dependency-graph) ⭐ 29 | 🐛 0 | 🌐 JavaScript | 📅 2019-02-08 and [grunt-es-dependency-graph](https://github.com/yahoo/grunt-es-dependency-graph) ⚠️ Archived - Generate a list of imports and exports from ES6 module files, useful for preloading, bundling, etc.
* [ES6 Lab setup](https://github.com/hemanth/es6-lab-setup) ⭐ 29 | 🐛 18 | 🌐 JavaScript | 📅 2025-07-17 - A simple setup for transpiling ES6 to ES5 using `Babel` or `traceur` with `gulp` and `jasmine` support.
* [looper](https://github.com/wycats/looper) ⚠️ Archived - static analysis tools for ES6
* [es6-import-validate](https://github.com/sproutsocial/es6-import-validate) ⚠️ Archived and [grunt-es6-import-validate](https://github.com/sproutsocial/grunt-es6-import-validate) ⚠️ Archived - validate matching named/default import statements in ES6 modules.
* [es6-translate](https://github.com/calvinmetcalf/es6-translate) ⭐ 5 | 🐛 5 | 🌐 JavaScript | 📅 2018-08-29 - Uses the ES6 loader hooks to load (node flavored) commonjs packages in ES6.
* [es6-module-packager](https://www.npmjs.com/package/es6-module-packager)
* [ES6 on node](http://h3manth.com/new/blog/2013/es6-on-nodejs/) - How to use ES6 features in node.js.
* [babel-node](https://babeljs.io/docs/usage/cli/#babel-node) - Run node cli with ES6 transpiling using Babel.
* [TypeScript](http://www.typescriptlang.org/) - A superset of ECMAScript with strict typing that aims to align with ES6
* [Rollup](http://rollupjs.org/) - Rollup is a next-generation JavaScript module bundler. Author your app or library using ES2015 modules, then efficiently bundle them up into a single file for use in browsers and Node.js

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
