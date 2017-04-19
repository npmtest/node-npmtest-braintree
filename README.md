# npmtest-braintree

#### test coverage for  [braintree (v2.0.2)](http://github.com/braintree/braintree_node)  [![npm package](https://img.shields.io/npm/v/npmtest-braintree.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-braintree) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-braintree.svg)](https://travis-ci.org/npmtest/node-npmtest-braintree)

#### A library for integrating with Braintree.

[![NPM](https://nodei.co/npm/braintree.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/braintree)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-braintree/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-braintree/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-braintree/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-braintree/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-braintree/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-braintree/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-braintree/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-braintree/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-braintree/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-braintree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-braintree/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-braintree/build/test-report.html](https://npmtest.github.io/node-npmtest-braintree/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-braintree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-braintree/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-braintree/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-braintree/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-braintree/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-braintree/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-braintree/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-braintree/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Braintree",
        "url": "http://www.braintreepayments.com"
    },
    "bugs": {
        "url": "https://github.com/braintree/braintree_node/issues"
    },
    "dependencies": {
        "dateformat": "1.0.1-1.2.3",
        "depd": "~1.1.0",
        "readable-stream": "1.1.10",
        "semver": "5.1.0",
        "source-map-support": "0.2.9",
        "underscore": "1.8.3",
        "xml2js": "0.1.13"
    },
    "description": "A library for integrating with Braintree.",
    "devDependencies": {
        "chai": "1.5.0",
        "coffee-script": "1.6.1",
        "eslint": "^2.7.0",
        "eslint-config-braintree": "^1.0.2",
        "mocha": "3.2.0"
    },
    "directories": {
        "lib": "./lib"
    },
    "dist": {
        "shasum": "3c898c40404969f34d31e158fe0b17c09d7955f5",
        "tarball": "https://registry.npmjs.org/braintree/-/braintree-2.0.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "gitHead": "d2e1e52d8bb702f1de261d7ecd4b9165ddaf0436",
    "homepage": "http://github.com/braintree/braintree_node",
    "keywords": [
        "braintree",
        "payments"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "braintree"
        }
    ],
    "name": "braintree",
    "optionalDependencies": {
        "source-map-support": "0.2.9"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/braintree/braintree_node.git"
    },
    "scripts": {
        "lint": "eslint lib/",
        "test": "npm run lint && npm run test:unit",
        "test:integration": "mocha --timeout 60000 --slow 2000 spec/integration --recursive --compilers coffee:coffee-script",
        "test:unit": "mocha spec/unit --recursive --compilers coffee:coffee-script"
    },
    "version": "2.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
