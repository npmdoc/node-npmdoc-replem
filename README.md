# npmdoc-replem

#### api documentation for  replem (v2.0.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-replem.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-replem) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-replem.svg)](https://travis-ci.org/npmdoc/node-npmdoc-replem)

#### Instantly try npm modules in REPL environment

[![NPM](https://nodei.co/npm/replem.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/replem)

- [https://npmdoc.github.io/node-npmdoc-replem/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-replem/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-replem/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-replem/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-replem/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-replem/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "replem",
    "version": "2.0.1",
    "description": "Instantly try npm modules in REPL environment",
    "scripts": {
        "test": "echo \"Error: no test specified\" && exit 1",
        "lint": "eslint lib"
    },
    "author": "Raine Virta <raine.virta@gmail.com>",
    "license": "ISC",
    "repository": "raine/replem",
    "bin": {
        "replem": "./bin/replem"
    },
    "keywords": [
        "repl"
    ],
    "dependencies": {
        "camelcase": "^1.2.1",
        "chalk": "^1.1.1",
        "char-spinner": "^1.0.1",
        "debug": "^2.2.0",
        "glob": "^5.0.14",
        "minimist": "^1.2.0",
        "npm": "4.3.0",
        "npm-package-arg": "^4.0.2",
        "ramda": "0.18.x",
        "ramda-fantasy": "^0.4.0",
        "repl.history": "^0.1.3",
        "sanctuary": "0.7.x",
        "xtend": "^4.0.0"
    },
    "devDependencies": {
        "eslint": "^1.4.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
