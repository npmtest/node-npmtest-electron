# test coverage for  [electron (v1.6.2)](https://github.com/electron-userland/electron-prebuilt#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron.svg)](https://travis-ci.org/npmtest/node-npmtest-electron)
#### Install prebuilt electron binaries for the command-line using npm

[![NPM](https://nodei.co/npm/electron.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/electron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-electron/build/test-report.html](https://npmtest.github.io/node-npmtest-electron/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mathias Buus"
    },
    "bin": {
        "electron": "cli.js"
    },
    "bugs": {
        "url": "https://github.com/electron-userland/electron-prebuilt/issues"
    },
    "dependencies": {
        "electron-download": "^3.0.1",
        "extract-zip": "^1.0.3"
    },
    "description": "Install prebuilt electron binaries for the command-line using npm",
    "devDependencies": {
        "home-path": "^0.1.1",
        "path-exists": "^2.0.0",
        "standard": "^5.4.1",
        "tape": "^3.0.1"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "b0ccd7703f86d09c4d2a7273455c3f993f158994",
        "tarball": "https://registry.npmjs.org/electron/-/electron-1.6.2.tgz"
    },
    "homepage": "https://github.com/electron-userland/electron-prebuilt#readme",
    "keywords": [
        "electron"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "electron"
        },
        {
            "name": "jlord"
        },
        {
            "name": "kevinsawicki"
        },
        {
            "name": "mafintosh"
        },
        {
            "name": "mattdesl"
        },
        {
            "name": "maxogden"
        },
        {
            "name": "zcbenz"
        },
        {
            "name": "zeke"
        }
    ],
    "name": "electron",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/electron-userland/electron-prebuilt.git"
    },
    "scripts": {
        "cache-clean": "rm -rf ~/.electron && rm -rf dist",
        "postinstall": "node install.js",
        "pretest": "npm run cache-clean && npm run postinstall",
        "test": "tape test/*.js && standard"
    },
    "version": "1.6.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
