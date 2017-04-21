# npmdoc-http-signature

#### api documentation for  [http-signature (v1.1.1)](https://github.com/joyent/node-http-signature/)  [![npm package](https://img.shields.io/npm/v/npmdoc-http-signature.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-http-signature) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-http-signature.svg)](https://travis-ci.org/npmdoc/node-npmdoc-http-signature)

#### Reference implementation of Joyent's HTTP Signature scheme.

[![NPM](https://nodei.co/npm/http-signature.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http-signature)

- [https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-signature/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-signature/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-http-signature/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-http-signature/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "http-signature",
    "description": "Reference implementation of Joyent's HTTP Signature scheme.",
    "version": "1.1.1",
    "license": "MIT",
    "author": "Joyent, Inc",
    "contributors": [
        "Mark Cavage <mcavage@gmail.com>",
        "David I. Lehn <dil@lehn.org>",
        "Patrick Mooney <patrick.f.mooney@gmail.com>"
    ],
    "repository": {
        "type": "git",
        "url": "git://github.com/joyent/node-http-signature.git"
    },
    "homepage": "https://github.com/joyent/node-http-signature/",
    "bugs": "https://github.com/joyent/node-http-signature/issues",
    "keywords": [
        "https",
        "request"
    ],
    "engines": {
        "node": ">=0.8",
        "npm": ">=1.3.7"
    },
    "main": "lib/index.js",
    "scripts": {
        "test": "tap test/*.js"
    },
    "dependencies": {
        "assert-plus": "^0.2.0",
        "jsprim": "^1.2.2",
        "sshpk": "^1.7.0"
    },
    "devDependencies": {
        "node-uuid": "^1.4.1",
        "tap": "0.4.2"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
