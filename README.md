# npmtest-express-pino-logger

#### basic test coverage for  [express-pino-logger (v2.0.0)](https://github.com/pinojs/express-pino-logger#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-express-pino-logger.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-express-pino-logger) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-express-pino-logger.svg)](https://travis-ci.org/npmtest/node-npmtest-express-pino-logger)

#### An express middleware to log with pino

[![NPM](https://nodei.co/npm/express-pino-logger.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-pino-logger)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-express-pino-logger/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-pino-logger/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-express-pino-logger/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-express-pino-logger/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-express-pino-logger/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-express-pino-logger/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-express-pino-logger/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-express-pino-logger/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-express-pino-logger/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-express-pino-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-express-pino-logger/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-express-pino-logger/build/test-report.html](https://npmtest.github.io/node-npmtest-express-pino-logger/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-express-pino-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-express-pino-logger/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-express-pino-logger/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-pino-logger/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-pino-logger/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-pino-logger/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-express-pino-logger/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-express-pino-logger/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "express-pino-logger",
    "version": "2.0.0",
    "description": "An express middleware to log with pino",
    "main": "logger.js",
    "scripts": {
        "test": "standard && tap test.js"
    },
    "precommit": "test",
    "keywords": [
        "express",
        "connect",
        "http",
        "logger",
        "fast",
        "pino"
    ],
    "author": "Matteo Collina <hello@matteocollina.com>",
    "license": "MIT",
    "dependencies": {
        "pino-http": "^2.0.0"
    },
    "devDependencies": {
        "express": "^4.13.4",
        "express-bunyan-logger": "^1.2.0",
        "express-winston": "^2.0.0",
        "morgan": "^1.7.0",
        "pino": "^3.0.0",
        "pre-commit": "^1.1.2",
        "split2": "^2.0.1",
        "standard": "^8.0.0",
        "tap": "^8.0.0",
        "winston": "^2.2.0"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pinojs/express-pino-logger.git"
    },
    "bugs": {
        "url": "https://github.com/pinojs/express-pino-logger/issues"
    },
    "homepage": "https://github.com/pinojs/express-pino-logger#readme"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
