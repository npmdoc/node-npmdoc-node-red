# npmdoc-node-red

#### api documentation for  [node-red (v0.16.2)](http://nodered.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-red.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-red) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-red.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-red)

#### A visual tool for wiring the Internet of Things

[![NPM](https://nodei.co/npm/node-red.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-red)

- [https://npmdoc.github.io/node-npmdoc-node-red/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-red/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-red/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-red/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "node-red": "./red.js",
        "node-red-pi": "bin/node-red-pi"
    },
    "bugs": {
        "url": "https://github.com/node-red/node-red/issues"
    },
    "contributors": [
        {
            "name": "Nick O'Leary"
        },
        {
            "name": "Dave Conway-Jones"
        }
    ],
    "dependencies": {
        "basic-auth": "1.1.0",
        "bcrypt": "~1.0.1",
        "bcryptjs": "2.4.0",
        "body-parser": "1.15.2",
        "cheerio": "0.22.0",
        "clone": "2.1.0",
        "cookie-parser": "1.4.3",
        "cors": "2.8.1",
        "cron": "1.2.1",
        "express": "4.14.0",
        "follow-redirects": "1.2.1",
        "fs-extra": "1.0.0",
        "fs.notify": "0.0.4",
        "i18next": "1.10.6",
        "is-utf8": "0.2.1",
        "js-yaml": "3.7.0",
        "json-stringify-safe": "5.0.1",
        "jsonata": "1.0.10",
        "media-typer": "0.3.0",
        "mqtt": "2.2.1",
        "mustache": "2.3.0",
        "node-red-node-email": "0.1.*",
        "node-red-node-feedparser": "0.1.*",
        "node-red-node-rbe": "0.1.*",
        "node-red-node-twitter": "0.1.*",
        "nopt": "3.0.6",
        "oauth2orize": "1.7.0",
        "on-headers": "1.0.1",
        "passport": "0.3.2",
        "passport-http-bearer": "1.0.1",
        "passport-oauth2-client-password": "0.1.2",
        "raw-body": "2.2.0",
        "semver": "5.3.0",
        "sentiment": "2.1.0",
        "uglify-js": "2.7.5",
        "when": "3.7.7",
        "ws": "1.1.1",
        "xml2js": "0.4.17"
    },
    "description": "A visual tool for wiring the Internet of Things",
    "devDependencies": {
        "grunt": "~1.0.1",
        "grunt-chmod": "~1.1.1",
        "grunt-cli": "~1.2.0",
        "grunt-concurrent": "~2.3.1",
        "grunt-contrib-clean": "~1.0.0",
        "grunt-contrib-compress": "~1.3.0",
        "grunt-contrib-concat": "~1.0.1",
        "grunt-contrib-copy": "~1.0.0",
        "grunt-contrib-jshint": "~1.1.0",
        "grunt-contrib-uglify": "~2.0.0",
        "grunt-contrib-watch": "~1.0.0",
        "grunt-jsonlint": "~1.1.0",
        "grunt-nodemon": "~0.4.2",
        "grunt-sass": "~1.2.1",
        "grunt-simple-mocha": "~0.4.1",
        "mocha": "~3.2.0",
        "should": "^8.4.0",
        "sinon": "1.17.7",
        "supertest": "2.0.1"
    },
    "directories": {},
    "dist": {
        "shasum": "3f77d608f1b0e89907af3f31e2c3eb8844a2b17b",
        "tarball": "https://registry.npmjs.org/node-red/-/node-red-0.16.2.tgz"
    },
    "engines": {
        "node": ">=4"
    },
    "homepage": "http://nodered.org",
    "keywords": [
        "editor",
        "messaging",
        "iot",
        "flow"
    ],
    "license": "Apache-2.0",
    "main": "red/red.js",
    "maintainers": [
        {
            "name": "dceejay"
        },
        {
            "name": "knolleary"
        }
    ],
    "name": "node-red",
    "optionalDependencies": {
        "bcrypt": "~1.0.1"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/node-red/node-red.git"
    },
    "scripts": {
        "build": "grunt build",
        "start": "node red.js",
        "test": "grunt"
    },
    "version": "0.16.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
