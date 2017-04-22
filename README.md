# npmdoc-npm-windows-upgrade

#### api documentation for  npm-windows-upgrade (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-npm-windows-upgrade.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-npm-windows-upgrade) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-npm-windows-upgrade.svg)](https://travis-ci.org/npmdoc/node-npmdoc-npm-windows-upgrade)

#### Upgrade npm on Windows, easily and automatically

[![NPM](https://nodei.co/npm/npm-windows-upgrade.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/npm-windows-upgrade)

- [https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-npm-windows-upgrade/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "npm-windows-upgrade",
    "description": "Upgrade npm on Windows, easily and automatically",
    "os": [
        "!darwin",
        "!linux"
    ],
    "scripts": {
        "build": "babel src --out-dir lib --source-maps true",
        "preversion": "npm run build",
        "test": "standard \"./src/*.js\" && mocha"
    },
    "version": "4.0.0",
    "private": false,
    "preferGlobal": true,
    "bin": {
        "npm-windows-upgrade": "./bin/npm-windows-upgrade.js"
    },
    "repository": "https://github.com/felixrieseberg/npm-windows-upgrade",
    "engines": {
        "node": ">= 4.0.0"
    },
    "keywords": [
        "Windows",
        "npm",
        "npm upgrade"
    ],
    "author": {
        "name": "Felix Rieseberg",
        "url": "http://www.felixrieseberg.com"
    },
    "bugs": {
        "url": "https://github.com/felixrieseberg/npm-windows-upgrade/issues"
    },
    "license": "MIT",
    "licenses": [
        {
            "type": "MIT",
            "url": "http://github.com/felixrieseberg/npm-windows-upgrade/blob/master/LICENSE"
        }
    ],
    "devDependencies": {
        "babel-cli": "^6.24.0",
        "babel-core": "^6.24.0",
        "babel-eslint": "^7.2.1",
        "babel-plugin-syntax-async-functions": "^6.13.0",
        "babel-plugin-transform-async-to-generator": "^6.22.0",
        "babel-plugin-transform-regenerator": "^6.22.0",
        "babel-preset-es2015": "^6.24.0",
        "chai": "^3.5.0",
        "mocha": "^3.2.0",
        "mockery": "^2.0.0",
        "standard": "^9.0.2"
    },
    "dependencies": {
        "babel-polyfill": "^6.23.0",
        "chalk": "~1.1.0",
        "cli-spinner": "~0.2.6",
        "commander": "~2.9.0",
        "debug": "^2.6.3",
        "inquirer": "~3.0.6",
        "prompt": "~1.0.0",
        "regenerator-runtime-only": "~0.8.38"
    },
    "standard": {
        "parser": "babel-eslint"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
