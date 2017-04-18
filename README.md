# npmtest-long

test coverage for  [long (v3.2.0)](https://github.com/dcodeIO/long.js#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-long.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-long) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-long.svg)](https://travis-ci.org/npmtest/node-npmtest-long)
#### A Long class for representing a 64-bit two's-complement integer value.

[![NPM](https://nodei.co/npm/long.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/long)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-long/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-long/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-long/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-long/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-long/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-long/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-long/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-long/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-long/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-long/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-long/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-long/build/test-report.html](https://npmtest.github.io/node-npmtest-long/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-long/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-long/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-long/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-long/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-long/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-long/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-long/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-long/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Daniel Wirtz"
    },
    "bugs": {
        "url": "https://github.com/dcodeIO/long.js/issues"
    },
    "dependencies": {},
    "description": "A Long class for representing a 64-bit two's-complement integer value.",
    "devDependencies": {
        "closurecompiler": "^1.6",
        "metascript": "~0",
        "testjs": "latest"
    },
    "directories": {},
    "dist": {
        "shasum": "d821b7138ca1cb581c172990ef14db200b5c474b",
        "tarball": "https://registry.npmjs.org/long/-/long-3.2.0.tgz"
    },
    "engines": {
        "node": ">=0.6"
    },
    "gitHead": "8cdc1f74ced4f771aa844f1cbc565b1d4c4451b8",
    "homepage": "https://github.com/dcodeIO/long.js#readme",
    "keywords": [
        "math"
    ],
    "license": "Apache-2.0",
    "main": "dist/long.js",
    "maintainers": [
        {
            "name": "dcode"
        }
    ],
    "name": "long",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dcodeIO/long.js.git"
    },
    "scripts": {
        "build": "node scripts/build.js",
        "compile": "ccjs dist/long.js --compilation_level=SIMPLE_OPTIMIZATIONS --create_source_map=dist/long.min.map > dist/long.min.js",
        "compress": "gzip -c -9 dist/long.min.js > dist/long.min.js.gz",
        "make": "npm run-script build && npm run-script compile && npm run-script compress && npm test",
        "test": "node node_modules/testjs/bin/testjs tests/suite.js"
    },
    "version": "3.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
