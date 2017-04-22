# npmtest-on-finished

#### basic test coverage for  [on-finished (v2.3.0)](https://github.com/jshttp/on-finished)  [![npm package](https://img.shields.io/npm/v/npmtest-on-finished.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-on-finished) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-on-finished.svg)](https://travis-ci.org/npmtest/node-npmtest-on-finished)

#### Execute a callback when a request closes, finishes, or errors

[![NPM](https://nodei.co/npm/on-finished.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/on-finished)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-on-finished/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-on-finished/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-on-finished/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-on-finished/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-on-finished/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-on-finished/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-on-finished/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-on-finished/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-on-finished/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-on-finished/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-on-finished/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-on-finished/build/test-report.html](https://npmtest.github.io/node-npmtest-on-finished/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-on-finished/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-on-finished/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-on-finished/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-on-finished/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-on-finished/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-on-finished/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/jshttp/on-finished/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        },
        {
            "name": "Jonathan Ong",
            "url": "http://jongleberry.com"
        }
    ],
    "dependencies": {
        "ee-first": "1.1.1"
    },
    "description": "Execute a callback when a request closes, finishes, or errors",
    "devDependencies": {
        "istanbul": "0.3.9",
        "mocha": "2.2.5"
    },
    "directories": {},
    "dist": {
        "shasum": "20f1336481b083cd75337992a16971aa2d906947",
        "tarball": "https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz"
    },
    "engines": {
        "node": ">= 0.8"
    },
    "files": [
        "HISTORY.md",
        "LICENSE",
        "index.js"
    ],
    "gitHead": "34babcb58126a416fcf5205768204f2e12699dda",
    "homepage": "https://github.com/jshttp/on-finished",
    "license": "MIT",
    "maintainers": [
        {
            "name": "dougwilson"
        },
        {
            "name": "jongleberry"
        }
    ],
    "name": "on-finished",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jshttp/on-finished.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "2.3.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
