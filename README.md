# npmtest-winston-elasticsearch

#### basic test coverage for  [winston-elasticsearch (v0.5.0)](https://github.com/vanthome/winston-elasticsearch#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-winston-elasticsearch.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-winston-elasticsearch) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-winston-elasticsearch.svg)](https://travis-ci.org/npmtest/node-npmtest-winston-elasticsearch)

#### An Elasticsearch transport for winston

[![NPM](https://nodei.co/npm/winston-elasticsearch.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/winston-elasticsearch)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-winston-elasticsearch/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-winston-elasticsearch/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-winston-elasticsearch/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-winston-elasticsearch/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/test-report.html](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-winston-elasticsearch/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-winston-elasticsearch/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-winston-elasticsearch/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-winston-elasticsearch/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-winston-elasticsearch/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        {
            "name": "Jacques-Olivier D. Bernier",
            "url": "https://github.com/jackdbernier"
        },
        {
            "name": "Thomas Hoppe",
            "url": "https://github.com/vanthome"
        }
    ],
    "bugs": {
        "url": "https://github.com/vanthome/winston-elasticsearch/issues"
    },
    "contributors": [
        {
            "name": "Andy Potanin",
            "url": "https://github.com/andypotanin"
        }
    ],
    "dependencies": {
        "debug": "^2.4.4",
        "elasticsearch": "^12.1.3",
        "lodash": "^4.17.2",
        "moment": "^2.17.1",
        "promise": "^7.1.1",
        "retry": "^0.10.1",
        "winston": "^2.3.0"
    },
    "description": "An Elasticsearch transport for winston",
    "devDependencies": {
        "babel-eslint": "^7.1.1",
        "coveralls": "^2.11.15",
        "eslint": "^3.12.2",
        "eslint-config-airbnb-base": "^11.0.0",
        "eslint-plugin-import": "^2.2.0",
        "eslint-plugin-json": "^1.2.0",
        "istanbul": "^0.4.5",
        "mocha": "^3.2.0",
        "should": "^11.1.2"
    },
    "directories": {},
    "dist": {
        "shasum": "77aad5921041fea77ee9f1f7774ebf72e7bccaf2",
        "tarball": "https://registry.npmjs.org/winston-elasticsearch/-/winston-elasticsearch-0.5.0.tgz"
    },
    "engines": {
        "node": ">= 6.0.0"
    },
    "gitHead": "1909c20f64bc41eb4d665b63289522f547f56057",
    "homepage": "https://github.com/vanthome/winston-elasticsearch#readme",
    "keywords": [
        "logging",
        "winston",
        "elasticsearch",
        "transport",
        "logstash"
    ],
    "license": "MIT",
    "main": "index",
    "maintainers": [
        {
            "name": "nfuse"
        },
        {
            "name": "vanthome"
        }
    ],
    "name": "winston-elasticsearch",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+ssh://git@github.com/vanthome/winston-elasticsearch.git"
    },
    "scripts": {
        "coveralls": "istanbul cover ./node_modules/mocha/bin/_mocha --report lcovonly -- -R spec ./test/*",
        "lint": "eslint *.json *.js",
        "mocha": "mocha ./test/*",
        "test": "npm run lint && npm run mocha"
    },
    "version": "0.5.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
