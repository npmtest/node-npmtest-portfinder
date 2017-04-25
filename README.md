# npmtest-portfinder

#### basic test coverage for  [portfinder (v1.0.13)](https://github.com/indexzero/node-portfinder#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-portfinder.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-portfinder) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-portfinder.svg)](https://travis-ci.org/npmtest/node-npmtest-portfinder)

#### A simple tool to find an open port on the current machine

[![NPM](https://nodei.co/npm/portfinder.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/portfinder)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-portfinder/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-portfinder/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-portfinder/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-portfinder/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-portfinder/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-portfinder/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-portfinder/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-portfinder/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-portfinder/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-portfinder/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-portfinder/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-portfinder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-portfinder/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-portfinder/build/test-report.html](https://npmtest.github.io/node-npmtest-portfinder/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-portfinder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-portfinder/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-portfinder/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-portfinder/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-portfinder/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-portfinder/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-portfinder/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-portfinder/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/indexzero/node-portfinder/issues"
    },
    "dependencies": {
        "async": "^1.5.2",
        "debug": "^2.2.0",
        "mkdirp": "0.5.x"
    },
    "description": "A simple tool to find an open port on the current machine",
    "devDependencies": {
        "glob": "^6.0.4",
        "vows": "0.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "bb32ecd87c27104ae6ee44b5a3ccbf0ebb1aede9",
        "tarball": "https://registry.npmjs.org/portfinder/-/portfinder-1.0.13.tgz"
    },
    "engines": {
        "node": ">= 0.12.0"
    },
    "files": [
        "lib"
    ],
    "gitHead": "20161e8e00355099c90062a069a7aa68dc9bcf9b",
    "homepage": "https://github.com/indexzero/node-portfinder#readme",
    "keywords": [
        "http",
        "ports",
        "utilities"
    ],
    "license": "MIT",
    "main": "./lib/portfinder",
    "maintainers": [
        {
            "name": "eriktrom"
        },
        {
            "name": "indexzero"
        }
    ],
    "name": "portfinder",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/indexzero/node-portfinder.git"
    },
    "scripts": {
        "test": "vows test/*-test.js --spec"
    },
    "types": "./lib/portfinder.d.ts",
    "version": "1.0.13",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
