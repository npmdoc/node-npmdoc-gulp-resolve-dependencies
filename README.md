# npmdoc-gulp-resolve-dependencies

#### api documentation for  gulp-resolve-dependencies (v2.2.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-gulp-resolve-dependencies.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-gulp-resolve-dependencies) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-gulp-resolve-dependencies.svg)](https://travis-ci.org/npmdoc/node-npmdoc-gulp-resolve-dependencies)

#### Resolve dependency directives in assets (e.g. "@requires" or "//= require" in JavaScript)

[![NPM](https://nodei.co/npm/gulp-resolve-dependencies.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/gulp-resolve-dependencies)

- [https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-gulp-resolve-dependencies/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "gulp-resolve-dependencies",
    "version": "2.2.0",
    "description": "Resolve dependency directives in assets (e.g. \"@requires\" or \"//= require\" in JavaScript)",
    "license": "MIT",
    "repository": "backflip/gulp-resolve-dependencies",
    "author": "Thomas Jaggi",
    "engines": {
        "node": ">=0.10.0"
    },
    "scripts": {
        "pretest": "npm i",
        "test": "./node_modules/mocha/bin/mocha"
    },
    "main": "./index.js",
    "keywords": [
        "gulpplugin",
        "gulp",
        "js",
        "dependencies",
        "depend",
        "depends",
        "concat",
        "order",
        "juicer",
        "sprockets"
    ],
    "dependencies": {
        "dag": "0.0.1",
        "gulp-util": "^3.0.3",
        "lodash": "^3.1.0"
    },
    "devDependencies": {
        "event-stream": "^3.2.2",
        "gulp": "^3.8.10",
        "gulp-concat": "^2.4.3",
        "gulp-tap": "^0.1.3",
        "mocha": "^2.1.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
