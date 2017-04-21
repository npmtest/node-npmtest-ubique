# npmtest-ubique

#### basic test coverage for  [ubique (v0.5.1)](http://maxto.github.io/index.html)  [![npm package](https://img.shields.io/npm/v/npmtest-ubique.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ubique) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ubique.svg)](https://travis-ci.org/npmtest/node-npmtest-ubique)

#### A mathematical and quantitative library for Javascript and Node.js

[![NPM](https://nodei.co/npm/ubique.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ubique)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ubique/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ubique/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ubique/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ubique/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ubique/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ubique/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ubique/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ubique/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ubique/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ubique/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ubique/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ubique/build/test-report.html](https://npmtest.github.io/node-npmtest-ubique/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ubique/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ubique/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ubique/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ubique/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ubique/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ubique/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ubique/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ubique/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ubique",
    "version": "0.5.1",
    "date": "2015-09-23",
    "author": "Max Todaro <m.todaro.ge@gmail.com>",
    "description": "A mathematical and quantitative library for Javascript and Node.js",
    "main": "./index",
    "contributors": [],
    "homepage": "http://maxto.github.io/index.html",
    "repository": {
        "type": "git",
        "url": "https://github.com/maxto/ubique.git"
    },
    "keywords": [
        "mathematic",
        "matrix",
        "arithmetic",
        "statistics",
        "linear algebra",
        "matlab",
        "regression",
        "finance",
        "quantitative analysis"
    ],
    "scripts": {
        "test": "mocha --ui tdd --recursive"
    },
    "engines": {
        "node": ">= 0.11.0"
    },
    "devDependencies": {
        "gulp": "^3.8.11",
        "gulp-util": "^3.0.4",
        "mocha": "^2.2.4",
        "uglify-js": "^2.4.21",
        "webpack": "^1.8.11"
    },
    "license": "MIT",
    "bugs": {
        "url": "https://github.com/maxto/ubique/issues"
    },
    "dependencies": {
        "moment": "^2.10.2",
        "request": "^2.55.0",
        "sync-request": "^2.0.1"
    },
    "browser": {
        "request": false
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
