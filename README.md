# npmdoc-global

#### api documentation for  [global (v4.3.1)](https://github.com/Raynos/global)  [![npm package](https://img.shields.io/npm/v/npmdoc-global.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-global) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-global.svg)](https://travis-ci.org/npmdoc/node-npmdoc-global)

#### Require global variables

[![NPM](https://nodei.co/npm/global.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/global)

- [https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-global/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-global/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-global/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-global/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Raynos"
    },
    "browser": {
        "min-document": false,
        "individual": false
    },
    "bugs": {
        "url": "https://github.com/Raynos/global/issues"
    },
    "contributors": [
        {
            "name": "Raynos"
        }
    ],
    "dependencies": {
        "min-document": "^2.19.0",
        "process": "~0.5.1"
    },
    "description": "Require global variables",
    "devDependencies": {
        "tape": "^2.12.0"
    },
    "directories": {},
    "dist": {
        "shasum": "5f757908c7cbabce54f386ae440e11e26b7916df",
        "tarball": "https://registry.npmjs.org/global/-/global-4.3.1.tgz"
    },
    "gitHead": "65eb66c398296ef52887e0ba06a21a88eae62ab6",
    "homepage": "https://github.com/Raynos/global",
    "keywords": [],
    "license": "MIT",
    "main": "window.js",
    "maintainers": [
        {
            "name": "raynos"
        },
        {
            "name": "mattesch"
        },
        {
            "name": "jerrysievert"
        }
    ],
    "name": "global",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Raynos/global.git"
    },
    "scripts": {
        "build": "browserify test/index.js -o test/static/bundle.js",
        "test": "node ./test",
        "testem": "testem"
    },
    "testling": {
        "files": "test/index.js",
        "browsers": {
            "ie": [
                "8",
                "9",
                "10"
            ],
            "firefox": [
                "16",
                "17",
                "nightly"
            ],
            "chrome": [
                "22",
                "23",
                "canary"
            ],
            "opera": [
                "12",
                "next"
            ],
            "safari": [
                "5.1"
            ]
        }
    },
    "version": "4.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
