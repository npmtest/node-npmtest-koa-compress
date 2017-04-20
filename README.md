# npmtest-koa-compress

#### basic test coverage for  koa-compress (v2.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-koa-compress.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-koa-compress) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-koa-compress.svg)](https://travis-ci.org/npmtest/node-npmtest-koa-compress)

#### Compress middleware for koa

[![NPM](https://nodei.co/npm/koa-compress.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/koa-compress)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-koa-compress/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-compress/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-koa-compress/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-koa-compress/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-koa-compress/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-koa-compress/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-koa-compress/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-koa-compress/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-koa-compress/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-koa-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-koa-compress/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-koa-compress/build/test-report.html](https://npmtest.github.io/node-npmtest-koa-compress/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-koa-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-koa-compress/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-koa-compress/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-koa-compress/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-koa-compress/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-koa-compress/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "koa-compress",
    "description": "Compress middleware for koa",
    "version": "2.0.0",
    "author": {
        "name": "Jonathan Ong",
        "url": "http://jongleberry.com",
        "twitter": "https://twitter.com/jongleberry"
    },
    "license": "MIT",
    "repository": "koajs/compress",
    "dependencies": {
        "bytes": "^2.3.0",
        "compressible": "^2.0.0",
        "koa-is-json": "^1.0.0",
        "statuses": "^1.0.0"
    },
    "devDependencies": {
        "istanbul": "^0.4.2",
        "koa": "^2.0.0-alpha.3",
        "mocha": "^2.4.1",
        "should": "^3.0.0",
        "supertest": "^1.0.0"
    },
    "scripts": {
        "test": "NODE_ENV=test mocha --require should --reporter spec",
        "test-cov": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha -- --require should",
        "test-travis": "NODE_ENV=test node ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha --report lcovonly -- --require should"
    },
    "files": [
        "index.js",
        "LICENSE",
        "HISTORY.md"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
