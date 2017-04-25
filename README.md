# npmtest-cookie-parser

#### basic test coverage for  [cookie-parser (v1.4.3)](https://github.com/expressjs/cookie-parser)  [![npm package](https://img.shields.io/npm/v/npmtest-cookie-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cookie-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cookie-parser.svg)](https://travis-ci.org/npmtest/node-npmtest-cookie-parser)

#### cookie parsing with signatures

[![NPM](https://nodei.co/npm/cookie-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cookie-parser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cookie-parser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie-parser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cookie-parser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cookie-parser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cookie-parser/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-cookie-parser/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-cookie-parser/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cookie-parser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cookie-parser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cookie-parser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cookie-parser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cookie-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cookie-parser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cookie-parser/build/test-report.html](https://npmtest.github.io/node-npmtest-cookie-parser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cookie-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cookie-parser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cookie-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cookie-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cookie-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cookie-parser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cookie-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cookie-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "url": "http://tjholowaychuk.com"
    },
    "bugs": {
        "url": "https://github.com/expressjs/cookie-parser/issues"
    },
    "contributors": [
        {
            "name": "Douglas Christopher Wilson"
        }
    ],
    "dependencies": {
        "cookie": "0.3.1",
        "cookie-signature": "1.0.6"
    },
    "description": "cookie parsing with signatures",
    "devDependencies": {
        "istanbul": "0.4.3",
        "mocha": "2.5.3",
        "supertest": "1.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0fe31fa19d000b95f4aadf1f53fdc2b8a203baa5",
        "tarball": "https://registry.npmjs.org/cookie-parser/-/cookie-parser-1.4.3.tgz"
    },
    "engines": {
        "node": ">= 0.8.0"
    },
    "files": [
        "LICENSE",
        "HISTORY.md",
        "index.js"
    ],
    "gitHead": "ad0b2cb834affe3929f0a690cd0494cd0b96d6be",
    "homepage": "https://github.com/expressjs/cookie-parser",
    "keywords": [
        "cookie",
        "middleware"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "defunctzombie"
        },
        {
            "name": "dougwilson"
        }
    ],
    "name": "cookie-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/expressjs/cookie-parser.git"
    },
    "scripts": {
        "test": "mocha --reporter spec --bail --check-leaks test/",
        "test-cov": "istanbul cover node_modules/mocha/bin/_mocha -- --reporter dot --check-leaks test/",
        "test-travis": "istanbul cover node_modules/mocha/bin/_mocha --report lcovonly -- --reporter spec --check-leaks test/"
    },
    "version": "1.4.3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
