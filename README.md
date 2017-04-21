# npmdoc-plex-api

#### api documentation for  plex-api (v5.1.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-plex-api.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-plex-api) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-plex-api.svg)](https://travis-ci.org/npmdoc/node-npmdoc-plex-api)

#### Simple wrapper for querying against HTTP API on the Plex Media Server

[![NPM](https://nodei.co/npm/plex-api.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/plex-api)

- [https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-plex-api/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-plex-api/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-plex-api/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-plex-api/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "plex-api",
    "version": "5.1.0",
    "description": "Simple wrapper for querying against HTTP API on the Plex Media Server",
    "main": "lib/api.js",
    "directories": {
        "test": "test"
    },
    "dependencies": {
        "plex-api-credentials": "^3.0.0",
        "plex-api-headers": "1.1.0",
        "request": "2.79.0",
        "uuid": "2.0.2",
        "xml2js": "0.4.16"
    },
    "devDependencies": {
        "expect.js": "^0.3.1",
        "mocha": "^2.5.0",
        "nock": "^8.0.0",
        "prettier": "1.1.0",
        "proxyquire": "^1.7.3",
        "sinon": "^1.17.2"
    },
    "scripts": {
        "format": "npm run format:exec -- --write",
        "format:exec": "prettier --single-quote --print-width=120 --tab-width=4 '{lib,test}/**/*.js'",
        "test": "npm run test:lint && npm run test:unit",
        "test:lint": "npm run format:exec -- --list-different",
        "test:unit": "mocha test/*-test.js",
        "test:watch": "npm run test:unit -- -w"
    },
    "files": [
        "lib"
    ],
    "repository": "git://github.com/phillipj/node-plex-api",
    "keywords": [
        "plex",
        "api"
    ],
    "engines": {
        "node": ">=4.0"
    },
    "author": "Phillip Johnsen <phillip@lightweight.no>",
    "license": "MIT"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
