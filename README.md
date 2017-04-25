# npmdoc-leveldb

#### basic api documentation for  [leveldb (v0.7.1)](https://github.com/my8bird/node-leveldb)  [![npm package](https://img.shields.io/npm/v/npmdoc-leveldb.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-leveldb) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-leveldb.svg)](https://travis-ci.org/npmdoc/node-npmdoc-leveldb)

#### Bindings for using LevelDB through node.

[![NPM](https://nodei.co/npm/leveldb.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/leveldb)

- [https://npmdoc.github.io/node-npmdoc-leveldb/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-leveldb/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-leveldb/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-leveldb/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-leveldb/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-leveldb/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "leveldb",
    "keywords": [
        "database",
        "leveldb"
    ],
    "description": "Bindings for using LevelDB through node.",
    "homepage": "https://github.com/my8bird/node-leveldb",
    "version": "0.7.1",
    "main": "lib",
    "engines": {
        "node": ">=0.6.13 <0.9.0"
    },
    "scripts": {
        "prepublish": "make coffee",
        "preinstall": "make build",
        "postinstall": "make pkgclean",
        "test": "make test"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/my8bird/node-leveldb.git"
    },
    "bugs": {
        "url": "https://github.com/my8bird/node-leveldb/issues"
    },
    "dependencies": {},
    "devDependencies": {
        "coffee-script": "~1.3.0",
        "mocha": "~1.3.0"
    },
    "contributors": [
        "Carter Thaxton <carter.thaxton@gmail.com>",
        "Damon Oehlman <damon.oehlman@gmail.com>",
        "Gabor Cselle <gabor@google.com>",
        "Hans Wennborg <hans@chromium.org>",
        "Michael Phan-Ba <michael@mikepb.com>",
        "Nathan Landis <my8bird@gmail.com>",
        "Randall Leeds <randall.leeds@gmail.com>",
        "Sanjay Ghemawat <sanjay@google.com>",
        "shinuza <samorigorse@gmail.com>",
        "Stefan Thomas <justmoon@members.fsf.org>",
        "Tim Caswell <tim@creationix.com>",
        "dgrogan@chromium.org",
        "jorlow@chromium.org"
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
