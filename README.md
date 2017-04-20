# npmtest-github-webhook

#### basic test coverage for  [github-webhook (v1.1.3)](https://github.com/rvagg/github-webhook#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-github-webhook.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-github-webhook) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-github-webhook.svg)](https://travis-ci.org/npmtest/node-npmtest-github-webhook)

#### A flexible web server for reacting GitHub Webhooks

[![NPM](https://nodei.co/npm/github-webhook.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/github-webhook)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-github-webhook/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-github-webhook/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-github-webhook/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-github-webhook/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-github-webhook/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-github-webhook/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-github-webhook/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-github-webhook/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-github-webhook/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-github-webhook/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-github-webhook/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-github-webhook/build/test-report.html](https://npmtest.github.io/node-npmtest-github-webhook/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-github-webhook/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-github-webhook/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-github-webhook/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-github-webhook/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-github-webhook/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-github-webhook/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-github-webhook/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-github-webhook/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Rod Vagg",
        "url": "http://r.va.gg"
    },
    "bin": {
        "github-webhook": "./github-webhook.js"
    },
    "bugs": {
        "url": "https://github.com/rvagg/github-webhook/issues"
    },
    "dependencies": {
        "debug": "~2.1.3",
        "github-webhook-handler": "~0.4.0",
        "matchme": "~2.0.1",
        "minimist": "~1.1.1",
        "split2": "~0.2.1",
        "through2": "~2.0.0"
    },
    "description": "A flexible web server for reacting GitHub Webhooks",
    "devDependencies": {
        "bl": "~1.0.0",
        "supertest": "~1.0.1",
        "tape": "~4.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "6a6a4ebb1217e516146747edc73a569e7ddcefc8",
        "tarball": "https://registry.npmjs.org/github-webhook/-/github-webhook-1.1.3.tgz"
    },
    "gitHead": "60f8e3d43134228ce56288c954a92ea1f173c5cd",
    "homepage": "https://github.com/rvagg/github-webhook#readme",
    "keywords": [
        "github",
        "webhooks"
    ],
    "license": "MIT",
    "main": "github-webhook.js",
    "maintainers": [
        {
            "name": "rvagg"
        }
    ],
    "name": "github-webhook",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rvagg/github-webhook.git"
    },
    "scripts": {
        "test": "node test.js"
    },
    "version": "1.1.3"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
