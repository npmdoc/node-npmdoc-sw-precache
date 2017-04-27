# npmdoc-sw-precache

#### basic api documentation for  [sw-precache (v5.1.0)](https://github.com/googlechrome/sw-precache)  [![npm package](https://img.shields.io/npm/v/npmdoc-sw-precache.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-sw-precache) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-sw-precache.svg)](https://travis-ci.org/npmdoc/node-npmdoc-sw-precache)

#### Generates a service worker to cache your local App Shell resources.

[![NPM](https://nodei.co/npm/sw-precache.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sw-precache)

- [https://npmdoc.github.io/node-npmdoc-sw-precache/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sw-precache/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sw-precache/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sw-precache/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-sw-precache/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-sw-precache/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jeff Posnick",
        "url": "https://jeffy.info"
    },
    "bin": {
        "sw-precache": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/googlechrome/sw-precache/issues"
    },
    "dependencies": {
        "dom-urls": "^1.1.0",
        "es6-promise": "^4.0.5",
        "glob": "^7.1.1",
        "lodash.defaults": "^4.2.0",
        "lodash.template": "^4.4.0",
        "meow": "^3.7.0",
        "mkdirp": "^0.5.1",
        "pretty-bytes": "^4.0.2",
        "sw-toolbox": "^3.4.0",
        "update-notifier": "^1.0.3"
    },
    "description": "Generates a service worker to cache your local App Shell resources.",
    "devDependencies": {
        "del": "^2.2.2",
        "eslint": "^3.15.0",
        "eslint-config-google": "^0.7.1",
        "express": "^4.14.1",
        "gh-pages": "^0.12.0",
        "grunt": "^1.0.1",
        "gulp": "^3.9.1",
        "gulp-doctoc": "^0.1.4",
        "gulp-eslint": "^3.0.1",
        "gulp-load-plugins": "^1.5.0",
        "gulp-mocha": "^3.0.1",
        "gulp-replace": "^0.5.4",
        "gulp-util": "^3.0.8",
        "jade": "^1.11.0",
        "mocha": "^3.2.0",
        "node-fetch": "^1.6.3",
        "run-sequence": "^1.2.2"
    },
    "directories": {},
    "dist": {
        "shasum": "0d79a0574fc85dc425340dc457dc45d4c5c2c9d5",
        "tarball": "https://registry.npmjs.org/sw-precache/-/sw-precache-5.1.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "files": [
        "cli.js",
        "lib",
        "service-worker.tmpl"
    ],
    "gitHead": "ad248039992cf8644beba7aa15495b47954f9c43",
    "homepage": "https://github.com/googlechrome/sw-precache",
    "keywords": [
        "caching",
        "offline",
        "precaching",
        "service-worker",
        "serviceworker",
        "appshell",
        "pwa"
    ],
    "license": "Apache-2.0",
    "main": "lib/sw-precache.js",
    "maintainers": [
        {
            "name": "addyosmani"
        },
        {
            "name": "gauntface"
        },
        {
            "name": "jeffposnick"
        },
        {
            "name": "wibblymat"
        }
    ],
    "name": "sw-precache",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/googlechrome/sw-precache.git"
    },
    "scripts": {
        "doctoc": "doctoc",
        "test": "gulp test lint"
    },
    "version": "5.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
