# npmtest-appium

#### test coverage for  [appium (v1.6.4)](https://github.com/appium/appium#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-appium.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-appium) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-appium.svg)](https://travis-ci.org/npmtest/node-npmtest-appium)

#### Automation for Apps.

[![NPM](https://nodei.co/npm/appium.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/appium)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-appium/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-appium/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-appium/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-appium/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-appium/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-appium/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-appium/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-appium/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-appium/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-appium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-appium/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-appium/build/test-report.html](https://npmtest.github.io/node-npmtest-appium/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-appium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-appium/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-appium/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-appium/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-appium/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-appium/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-appium/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-appium/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "https://github.com/appium"
    },
    "bin": {
        "appium": "./build/lib/main.js"
    },
    "bugs": {
        "url": "https://github.com/appium/appium/issues"
    },
    "contributors": [
        {
            "name": "Authors ordered by first contribution"
        },
        {
            "name": "Dan Cuellar"
        },
        {
            "name": "E. James Infusino"
        },
        {
            "name": "Jason Huggins"
        },
        {
            "name": "Jason Carr"
        },
        {
            "name": "Jayme Deffenbaugh"
        },
        {
            "name": "Roman Salvador"
        },
        {
            "name": "Luke Inman-Semerau"
        },
        {
            "name": "Pradeep Bishnoi"
        },
        {
            "name": "Charles Nowacek"
        },
        {
            "name": "Jayakumar Chinnappan"
        },
        {
            "name": "Robin Keller"
        },
        {
            "name": "Adam Christian"
        },
        {
            "name": "Jonathan Lipps"
        },
        {
            "name": "Sebastian Tiedtke"
        },
        {
            "name": "Christian Bromann"
        },
        {
            "name": "Jeremy Avnet"
        },
        {
            "name": "Bernard Kobos"
        },
        {
            "name": "Santiago Suarez Ordoñez"
        },
        {
            "name": "Joe Mathes"
        }
    ],
    "dependencies": {
        "appium-android-driver": "1.x",
        "appium-base-driver": "2.x",
        "appium-fake-driver": "0.x",
        "appium-ios-driver": "1.x",
        "appium-mac-driver": "1.x",
        "appium-selendroid-driver": "1.x",
        "appium-support": "2.x",
        "appium-uiautomator2-driver": "0.x",
        "appium-windows-driver": "0.x",
        "appium-xcuitest-driver": "2.x",
        "appium-youiengine-driver": "1.x",
        "argparse": "1.x",
        "asyncbox": "2.x",
        "babel-runtime": "=5.8.24",
        "bluebird": "2.x",
        "continuation-local-storage": "3.x",
        "date-utils": "1.x",
        "fsevents": "1.x",
        "lodash": "4.x",
        "npmlog": "2.x",
        "request-promise": "1.x",
        "source-map-support": "0.x",
        "teen_process": "1.x",
        "winston": "2.x"
    },
    "description": "Automation for Apps.",
    "devDependencies": {
        "appium-gulp-plugins": "1.x",
        "babel-eslint": "6.x",
        "chai": "3.x",
        "chai-as-promised": "5.x",
        "eslint": "2.x",
        "eslint-config-appium": "0.x",
        "eslint-plugin-babel": "3.x",
        "eslint-plugin-import": "1.x",
        "eslint-plugin-mocha": "3.x",
        "eslint-plugin-promise": "3.x",
        "gulp": "3.x",
        "mocha": "2.x",
        "pre-commit": "1.x",
        "sinon": "1.x",
        "wd": "1.x"
    },
    "directories": {
        "lib": "./lib",
        "doc": "./docs"
    },
    "dist": {
        "shasum": "8b6beed6cb81ab3d8233231d15c62a7c24de5c56",
        "tarball": "https://registry.npmjs.org/appium/-/appium-1.6.4.tgz"
    },
    "engines": {
        "node": ">=4",
        "npm": ">=3"
    },
    "gitHead": "980af5e2b25c7d2cfee8ebb84a3bb8c4cb3616e6",
    "homepage": "https://github.com/appium/appium#readme",
    "license": "Apache-2.0",
    "main": "./build/lib/main.js",
    "maintainers": [
        {
            "name": "dangraham"
        },
        {
            "name": "imurchie"
        },
        {
            "name": "jlipps"
        }
    ],
    "name": "appium",
    "optionalDependencies": {
        "fsevents": "1.x"
    },
    "pre-commit": [
        "precommit-msg",
        "lint",
        "test"
    ],
    "repository": {
        "type": "git",
        "url": "git+https://github.com/appium/appium.git"
    },
    "scripts": {
        "lint": "gulp eslint",
        "precommit-msg": "echo 'Pre-commit checks...' && exit 0",
        "prepublish": "gulp prepublish",
        "test": "gulp once",
        "watch": "gulp"
    },
    "tags": [
        "automation",
        "javascript",
        "selenium",
        "webdriver",
        "ios",
        "android",
        "firefoxos",
        "testing"
    ],
    "version": "1.6.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
