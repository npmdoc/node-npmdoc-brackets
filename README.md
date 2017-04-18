# npmdoc-brackets

#### api documentation for  [brackets (v0.5.8)](https://github.com/rabchev/brackets-server)  [![npm package](https://img.shields.io/npm/v/npmdoc-brackets.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-brackets) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-brackets.svg)](https://travis-ci.org/npmdoc/node-npmdoc-brackets)

#### Brackets Server is a server for providing hosted version of the popular code editor Brackets.

[![NPM](https://nodei.co/npm/brackets.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/brackets)

- [https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-brackets/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-brackets/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-brackets/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-brackets/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Boyan Rabchev"
    },
    "bin": {
        "brackets": "./bin/run.js",
        "brackets-server": "./bin/run.js"
    },
    "bugs": {
        "url": "https://github.com/rabchev/brackets-server/issues"
    },
    "contributors": [
        {
            "name": "Boyan Rabchev"
        }
    ],
    "dependencies": {
        "commander": "^2.3.0",
        "glob": "^4.0.6",
        "mkdirp": "^0.5.0",
        "ncp": "^1.0.0",
        "open": "^0.0.5",
        "rimraf": "^2.2.8",
        "send": "^0.9.3",
        "socket.io": "1.1.0"
    },
    "description": "Brackets Server is a server for providing hosted version of the popular code editor Brackets.",
    "devDependencies": {
        "chai": "*",
        "grunt": "*",
        "grunt-concurrent": "*",
        "grunt-contrib-clean": "*",
        "grunt-contrib-compress": "*",
        "grunt-contrib-concat": "*",
        "grunt-contrib-copy": "*",
        "grunt-contrib-htmlmin": "*",
        "grunt-contrib-less": "0.8.2",
        "grunt-contrib-requirejs": "*",
        "grunt-node-inspector": "*",
        "grunt-release": "*",
        "grunt-replace": "*",
        "grunt-shell": "*",
        "grunt-simple-mocha": "*",
        "grunt-targethtml": "*",
        "grunt-text-replace": "*",
        "grunt-usemin": "0.1.11",
        "load-grunt-tasks": "*",
        "mocha": "*",
        "q": "0.9.2",
        "shelljs": "^0.3.0",
        "sinon-chai": "*",
        "supertest": "*"
    },
    "directories": {},
    "dist": {
        "shasum": "7ecb9847cab882f7ccb68b12a2d8d426430d1195",
        "tarball": "https://registry.npmjs.org/brackets/-/brackets-0.5.8.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "a848dee514079e80ecba2d430e99abd863f554b0",
    "homepage": "https://github.com/rabchev/brackets-server",
    "keywords": [
        "brackets",
        "node",
        "nodejs",
        "code",
        "editor",
        "web",
        "project",
        "application",
        "management",
        "dev",
        "development",
        "javascript",
        "html",
        "css",
        "ide"
    ],
    "license": {
        "type": "MIT",
        "url": "http://github.com/rabchev/brackets-server/blob/master/LICENSE"
    },
    "main": "./lib/server",
    "maintainers": [
        {
            "name": "rabchev"
        }
    ],
    "name": "brackets",
    "optionalDependencies": {},
    "preferGlobal": "true",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/rabchev/brackets-server.git"
    },
    "scripts": {
        "postinstall": "node lib/post-install.js",
        "test": "grunt test"
    },
    "version": "0.5.8"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
