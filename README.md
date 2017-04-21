# npmtest-jscs-jsdoc

#### basic test coverage for  [jscs-jsdoc (v2.0.0)](https://github.com/jscs-dev/jscs-jsdoc)  [![npm package](https://img.shields.io/npm/v/npmtest-jscs-jsdoc.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-jscs-jsdoc) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-jscs-jsdoc.svg)](https://travis-ci.org/npmtest/node-npmtest-jscs-jsdoc)

#### JSCS jsdoc plugin

[![NPM](https://nodei.co/npm/jscs-jsdoc.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/jscs-jsdoc)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-jscs-jsdoc/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-jscs-jsdoc/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-jscs-jsdoc/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/test-report.html](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-jscs-jsdoc/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-jscs-jsdoc/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Alexej Yaroshevich"
    },
    "bugs": {
        "url": "https://github.com/jscs-dev/jscs-jsdoc/issues"
    },
    "contributors": [
        {
            "name": "Alexej Yaroshevich"
        },
        {
            "name": "Henry Zhu"
        },
        {
            "name": "Christopher Hiller"
        },
        {
            "name": "Raphael Pigulla"
        }
    ],
    "dependencies": {
        "comment-parser": "^0.3.1",
        "jsdoctypeparser": "~1.2.0"
    },
    "description": "JSCS jsdoc plugin",
    "devDependencies": {
        "chai": "^2.3.0",
        "chai-subset": "^1.1.0",
        "jscs": "git://github.com/jscs-dev/node-jscs.git#master",
        "jshint": "^2.7.0",
        "mocha": "^2.2.4"
    },
    "directories": {},
    "dist": {
        "shasum": "f53ebce029aa3125bd88290ba50d64d4510a4871",
        "tarball": "https://registry.npmjs.org/jscs-jsdoc/-/jscs-jsdoc-2.0.0.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "lib",
        "LICENSE"
    ],
    "gitHead": "5b3b85b4b4dc6379a7af8dab3250c903f0c4c7ee",
    "homepage": "https://github.com/jscs-dev/jscs-jsdoc",
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/jscs-dev/jscs-jsdoc/raw/master/LICENSE"
        }
    ],
    "main": "lib/index",
    "maintainers": [
        {
            "name": "mdevils"
        },
        {
            "name": "qfox"
        }
    ],
    "name": "jscs-jsdoc",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jscs-dev/jscs-jsdoc.git"
    },
    "scripts": {
        "browserify": "browserify --standalone JsdocJscsPlugin lib/index.js -o jscs-jsdoc-browser.js",
        "changelog": "changelog-maker jscs-dev jscs-jsdoc --group",
        "lint": "jshint lib test && jscs lib test",
        "test": "npm run lint && mocha"
    },
    "version": "2.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
