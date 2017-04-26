# npmdoc-duo

#### basic api documentation for  [duo (v0.15.7)](http://duojs.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-duo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-duo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-duo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-duo)

#### A next-generation package manager for the front-end

[![NPM](https://nodei.co/npm/duo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/duo)

- [https://npmdoc.github.io/node-npmdoc-duo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-duo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-duo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-duo/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-duo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-duo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "duo": "bin/duo",
        "_duo": "bin/_duo",
        "duo-authenticate": "bin/duo-authenticate",
        "duo-clean-cache": "bin/duo-clean-cache",
        "duo-duplicates": "bin/duo-duplicates",
        "duo-install": "bin/duo-install",
        "duo-ls": "bin/duo-ls"
    },
    "bugs": {
        "url": "https://github.com/duojs/duo/issues"
    },
    "dependencies": {
        "archy": "^1.0.0",
        "batch": "^0.5.1",
        "bytes": "^2.1.0",
        "co": "^3.1.0",
        "co-each": "^0.1.0",
        "co-exists": "0.0.1",
        "co-fs": "~1.2.0",
        "co-parallel": "~1.0.0",
        "commander": "^2.2.0",
        "component-clone": "^0.2.2",
        "conceal": "^1.0.0",
        "convert-source-map": "^1.1.1",
        "cp": "^0.2.0",
        "debug": "^2.0.0",
        "delegates": "^0.1.0",
        "duo-cache": "^2.1.2",
        "duo-css-compat": "^0.3.1",
        "duo-main": "0.0.6",
        "duo-pack": "^3.0.0",
        "duo-package": "^0.10.3",
        "duo-parse": "^0.2.0",
        "duo-string-to-js": "~0.1.0",
        "duo-test": "0.x",
        "duo-watch": "^0.1.1",
        "extend.js": "0.0.2",
        "file-deps": "^0.0.7",
        "get-stdin": "^4.0.1",
        "glob": "^5.0.10",
        "has-generators": "^1.0.1",
        "hasha": "^1.0.1",
        "json-mask": "^0.3.1",
        "language-classifier": "0.0.1",
        "mkdirp": "^0.5.0",
        "node-netrc": "^0.1.0",
        "object-values": "^1.0.0",
        "path-search": "^1.0.0",
        "request": "^2.60.0",
        "stream-log": "^0.2.3",
        "thunkify": "~2.1.1",
        "unyield": "0.0.1",
        "ware": "^1.2.0",
        "win-fork": "^1.1.1"
    },
    "description": "A next-generation package manager for the front-end",
    "devDependencies": {
        "bluebird": "^2.9.20",
        "co-mocha": "~1.0.3",
        "co-wait": "0.0.0",
        "coffee-script": "^1.9.3",
        "duo-jade": "0.x",
        "eslint": "^0.23.0",
        "eslint-config-duo": "0.0.4",
        "expect.js": "^0.3.1",
        "gnode": "^0.1.1",
        "gulp": "^3.9.0",
        "istanbul": "^0.3.15",
        "map-stream": "~0.1.0",
        "mocha": "^2.2.5",
        "regenerator": "^0.8.31",
        "rimraf": "^2.2.8",
        "semver": "^4.3.3",
        "styl": "^0.2.7"
    },
    "directories": {},
    "dist": {
        "shasum": "2352621bbee5221842abf6e235660452ae884960",
        "tarball": "https://registry.npmjs.org/duo/-/duo-0.15.7.tgz"
    },
    "gitHead": "a01cfa748619c963d5c9824273db2e7390c92eb2",
    "homepage": "http://duojs.org/",
    "license": "MIT",
    "main": "lib/duo.js",
    "maintainers": [
        {
            "name": "mattmueller"
        },
        {
            "name": "yields"
        },
        {
            "name": "dominicbarnes"
        },
        {
            "name": "stephenmathieson"
        }
    ],
    "name": "duo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/duojs/duo.git"
    },
    "scripts": {},
    "version": "0.15.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
