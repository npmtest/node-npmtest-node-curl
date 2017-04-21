# npmtest-node-curl

#### basic test coverage for  [node-curl (v0.3.3)](http://github.com/jiangmiao/node-curl)  [![npm package](https://img.shields.io/npm/v/npmtest-node-curl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-node-curl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-node-curl.svg)](https://travis-ci.org/npmtest/node-npmtest-node-curl)

#### node wrapper for multi curl, fully implemented.

[![NPM](https://nodei.co/npm/node-curl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-curl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-node-curl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-curl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-node-curl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-node-curl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-node-curl/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-node-curl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-node-curl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-node-curl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-node-curl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-node-curl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-node-curl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-node-curl/build/test-report.html](https://npmtest.github.io/node-npmtest-node-curl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-node-curl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-node-curl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-curl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-curl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-node-curl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-node-curl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "node-curl",
    "version": "0.3.3",
    "author": "Jiang Miao <jiangfriend@gmail.com>",
    "description": "node wrapper for multi curl, fully implemented.",
    "keywords": [
        "node-curl",
        "curl",
        "multi-curl",
        "mcurl"
    ],
    "homepage": "http://github.com/jiangmiao/node-curl",
    "repository": {
        "type": "git",
        "url": "git://github.com/jiangmiao/node-curl.git"
    },
    "main": "./lib",
    "scripts": {
        "install": "sh src/generate_curl_options_list.sh && (node-gyp rebuild || node-waf configure build)"
    },
    "engines": {
        "node": ">= 0.6.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
