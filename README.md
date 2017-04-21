# npmtest-sails-rest

#### basic test coverage for  sails-rest (v0.1.1)  [![npm package](https://img.shields.io/npm/v/npmtest-sails-rest.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-sails-rest) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-sails-rest.svg)](https://travis-ci.org/npmtest/node-npmtest-sails-rest)

#### rest adapter for Sails / Waterline

[![NPM](https://nodei.co/npm/sails-rest.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/sails-rest)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-sails-rest/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-rest/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-sails-rest/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-sails-rest/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-sails-rest/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-sails-rest/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-sails-rest/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-sails-rest/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-sails-rest/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-sails-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-sails-rest/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-sails-rest/build/test-report.html](https://npmtest.github.io/node-npmtest-sails-rest/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-sails-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-sails-rest/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-sails-rest/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-sails-rest/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-sails-rest/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-sails-rest/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "sails-rest",
    "version": "0.1.1",
    "description": "rest adapter for Sails / Waterline",
    "main": "index.js",
    "scripts": {
        "test": "node test/integration/runner -R spec -b"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/zohararad/sails-rest.git"
    },
    "keywords": [
        "rest",
        "adapter",
        "sails",
        "waterline",
        "sails.js",
        "plugin"
    ],
    "author": "Zohar Arad",
    "license": "MIT",
    "readmeFilename": "README.md",
    "dependencies": {
        "async": "^1.4.2",
        "lodash": "^3.9.3",
        "restify": "^3.0.3",
        "superagent": "^1.2.0"
    },
    "devDependencies": {
        "body-parser": "^1.12.4",
        "captains-log": "~0.11.0",
        "express": "^4.12.4",
        "mocha": "*",
        "multer": "^0.1.8",
        "sails-memory": "^0.10.4",
        "waterline-adapter-tests": "~0.10.0"
    },
    "waterlineAdapter": {
        "type": "rest",
        "interfaces": [
            "semantic"
        ],
        "waterlineVersion": "~0.10.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
