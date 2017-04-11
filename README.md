# test coverage for  [electron (v1.6.2)](https://github.com/electron-userland/electron-prebuilt#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-electron.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-electron) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-electron.svg)](https://travis-ci.org/npmtest/node-npmtest-electron)
#### Install prebuilt electron binaries for the command-line using npm

[![NPM](https://nodei.co/npm/electron.png?downloads=true)](https://www.npmjs.com/package/electron)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-electron/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-electron/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-electron/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-electron/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-electron/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-electron/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-electron/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-electron%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-electron/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-electron/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-electron%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-electron/build/apidoc.html)

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
            "name": "electron",
            "email": "electron@github.com"
        },
        {
            "name": "jlord",
            "email": "to.jlord@gmail.com"
        },
        {
            "name": "kevinsawicki",
            "email": "kevinsawicki@gmail.com"
        },
        {
            "name": "mafintosh",
            "email": "mathiasbuus@gmail.com"
        },
        {
            "name": "mattdesl",
            "email": "dave.des@gmail.com"
        },
        {
            "name": "maxogden",
            "email": "max@maxogden.com"
        },
        {
            "name": "zcbenz",
            "email": "zcbenz@gmail.com"
        },
        {
            "name": "zeke",
            "email": "zeke@sikelianos.com"
        }
    ],
    "name": "electron",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
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
