# npmtest-nodewebkit

#### basic test-coverage for  nodewebkit (v0.11.6)  [![npm package](https://img.shields.io/npm/v/npmtest-nodewebkit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-nodewebkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-nodewebkit.svg)](https://travis-ci.org/npmtest/node-npmtest-nodewebkit)

#### A installer for node-webkit

[![NPM](https://nodei.co/npm/nodewebkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/nodewebkit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-nodewebkit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodewebkit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-nodewebkit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-nodewebkit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-nodewebkit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-nodewebkit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-nodewebkit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-nodewebkit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-nodewebkit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-nodewebkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-nodewebkit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-nodewebkit/build/test-report.html](https://npmtest.github.io/node-npmtest-nodewebkit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-nodewebkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-nodewebkit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-nodewebkit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-nodewebkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-nodewebkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "nodewebkit",
    "version": "0.11.6",
    "description": "A installer for node-webkit",
    "repository": {
        "type": "git",
        "url": "git://github.com/shama/nodewebkit.git"
    },
    "main": "index.js",
    "bin": {
        "nodewebkit": "bin/nodewebkit"
    },
    "scripts": {
        "postinstall": "node scripts/install.js",
        "test": "node test/index.js"
    },
    "files": [
        "lib",
        "bin",
        "scripts",
        "index.js"
    ],
    "author": "Kyle Robinson Young",
    "license": "MIT",
    "dependencies": {
        "rimraf": "^2.2.2",
        "download": "^0.1.10",
        "multimeter": "^0.1.1",
        "yargs": "^1.2.1",
        "semver": "^2.3.1"
    },
    "devDependencies": {
        "request": "^2.30.0",
        "tape": "^2.12.3"
    },
    "keywords": [
        "node-webkit",
        "webkit",
        "installer",
        "desktop",
        "application"
    ]
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
