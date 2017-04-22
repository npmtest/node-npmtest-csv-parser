# npmtest-csv-parser

#### basic test-coverage for  [csv-parser (v1.11.0)](https://github.com/mafintosh/csv-parser)  [![npm package](https://img.shields.io/npm/v/npmtest-csv-parser.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-csv-parser) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-csv-parser.svg)](https://travis-ci.org/npmtest/node-npmtest-csv-parser)

#### Streaming CSV parser that aims for maximum speed as well as compatibility with the csv-spectrum test suite

[![NPM](https://nodei.co/npm/csv-parser.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/csv-parser)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-csv-parser/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-parser/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-csv-parser/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-csv-parser/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-csv-parser/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-csv-parser/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-csv-parser/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-csv-parser/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-csv-parser/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-csv-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-csv-parser/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-csv-parser/build/test-report.html](https://npmtest.github.io/node-npmtest-csv-parser/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-csv-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-csv-parser/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-csv-parser/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-csv-parser/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-csv-parser/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-csv-parser/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-csv-parser/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-csv-parser/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "mafintosh"
    },
    "bin": {
        "csv-parser": "./bin.js"
    },
    "bugs": {
        "url": "https://github.com/mafintosh/csv-parser/issues"
    },
    "dependencies": {
        "generate-function": "^1.0.1",
        "generate-object-property": "^1.0.0",
        "inherits": "^2.0.1",
        "minimist": "^1.2.0",
        "ndjson": "^1.4.0"
    },
    "description": "Streaming CSV parser that aims for maximum speed as well as compatibility with the csv-spectrum test suite",
    "devDependencies": {
        "bops": "^0.1.1",
        "concat-stream": "^1.4.5",
        "csv-spectrum": "^1.0.0",
        "standard": "^5.4.1",
        "tape": "^4.2.2"
    },
    "directories": {
        "example": "examples",
        "test": "test"
    },
    "dist": {
        "shasum": "cd92c3f49895a3c1591591035cbfbe6b51c55ab1",
        "tarball": "https://registry.npmjs.org/csv-parser/-/csv-parser-1.11.0.tgz"
    },
    "gitHead": "234c57e330d23cf3c8503417e5436144ef51816a",
    "homepage": "https://github.com/mafintosh/csv-parser",
    "keywords": [
        "csv",
        "parser",
        "fast",
        "json"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mafintosh"
        },
        {
            "name": "maxogden"
        }
    ],
    "name": "csv-parser",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mafintosh/csv-parser.git"
    },
    "scripts": {
        "test": "standard && tape test/test.js"
    },
    "version": "1.11.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
