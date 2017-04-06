# api documentation for  [duo (v0.15.7)](http://duojs.org/)  [![npm package](https://img.shields.io/npm/v/npmdoc-duo.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-duo) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-duo.svg)](https://travis-ci.org/npmdoc/node-npmdoc-duo)
#### A next-generation package manager for the front-end

[![NPM](https://nodei.co/npm/duo.png?downloads=true)](https://www.npmjs.com/package/duo)

[![apidoc](https://npmdoc.github.io/node-npmdoc-duo/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-duo_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-duo/build/apidoc.html)

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
            "name": "mattmueller",
            "email": "mattmuelle@gmail.com"
        },
        {
            "name": "yields",
            "email": "yields@icloud.com"
        },
        {
            "name": "dominicbarnes",
            "email": "dominic@dbarnes.info"
        },
        {
            "name": "stephenmathieson",
            "email": "me@stephenmathieson.com"
        }
    ],
    "name": "duo",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/duojs/duo.git"
    },
    "scripts": {},
    "version": "0.15.7"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module duo](#apidoc.module.duo)
1.  [function <span class="apidocSignatureSpan">duo.</span>cache (file)](#apidoc.element.duo.cache)
1.  [function <span class="apidocSignatureSpan">duo.</span>file (attrs, duo)](#apidoc.element.duo.file)
1.  [function <span class="apidocSignatureSpan">duo.</span>super_ ()](#apidoc.element.duo.super_)
1.  object <span class="apidocSignatureSpan">duo.</span>file.prototype
1.  object <span class="apidocSignatureSpan">duo.</span>util

#### [module duo.cache](#apidoc.module.duo.cache)
1.  [function <span class="apidocSignatureSpan">duo.</span>cache (file)](#apidoc.element.duo.cache.cache)
1.  [function <span class="apidocSignatureSpan">duo.cache.</span>clean ()](#apidoc.element.duo.cache.clean)

#### [module duo.file](#apidoc.module.duo.file)
1.  [function <span class="apidocSignatureSpan">duo.</span>file (attrs, duo)](#apidoc.element.duo.file.file)

#### [module duo.file.prototype](#apidoc.module.duo.file.prototype)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>dependencies ()](#apidoc.element.duo.file.prototype.dependencies)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>exists ()](#apidoc.element.duo.file.prototype.exists)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>include ()](#apidoc.element.duo.file.prototype.include)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>included ()](#apidoc.element.duo.file.prototype.included)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>json ()](#apidoc.element.duo.file.prototype.json)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>load ()](#apidoc.element.duo.file.prototype.load)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>local ()](#apidoc.element.duo.file.prototype.local)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>modified ()](#apidoc.element.duo.file.prototype.modified)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>remote ()](#apidoc.element.duo.file.prototype.remote)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>set (attrs)](#apidoc.element.duo.file.prototype.set)
1.  [function <span class="apidocSignatureSpan">duo.file.prototype.</span>toString ()](#apidoc.element.duo.file.prototype.toString)

#### [module duo.util](#apidoc.module.duo.util)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>collect (val, memo)](#apidoc.element.duo.util.collect)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>entries (root, list)](#apidoc.element.duo.util.entries)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>findroot (root)](#apidoc.element.duo.util.findroot)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>plugins (root, plugins)](#apidoc.element.duo.util.plugins)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>token ()](#apidoc.element.duo.util.token)
1.  [function <span class="apidocSignatureSpan">duo.util.</span>type (src)](#apidoc.element.duo.util.type)



# <a name="apidoc.module.duo"></a>[module duo](#apidoc.module.duo)

#### <a name="apidoc.element.duo.cache"></a>[function <span class="apidocSignatureSpan">duo.</span>cache (file)](#apidoc.element.duo.cache)
- description and source-code
```javascript
cache = function (file) {
  if (!(file in instances)) {
    debug('creating new cache instance');
    instances[file] = new Cache(file);
  }

  return instances[file];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file"></a>[function <span class="apidocSignatureSpan">duo.</span>file (attrs, duo)](#apidoc.element.duo.file)
- description and source-code
```javascript
function File(attrs, duo) {
  if (!(this instanceof File)) return new File(attrs, duo);
  this.attrs = clone(attrs || {});
  this.duo = duo;

  var type = attrs.type ? '.' + attrs.type : '';
  var path = attrs.path || 'source' + type;

  // initial attrs
  this.attrs.path = resolve(attrs.root, path);
  this.attrs.type = attrs.type || extension(this.path);
  this.attrs.id = relative(duo.root(), this.path);

  // local vs remote
  this.attrs.local = !!(attrs.entry || attrs.local);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.super_"></a>[function <span class="apidocSignatureSpan">duo.</span>super_ ()](#apidoc.element.duo.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.duo.cache"></a>[module duo.cache](#apidoc.module.duo.cache)

#### <a name="apidoc.element.duo.cache.cache"></a>[function <span class="apidocSignatureSpan">duo.</span>cache (file)](#apidoc.element.duo.cache.cache)
- description and source-code
```javascript
cache = function (file) {
  if (!(file in instances)) {
    debug('creating new cache instance');
    instances[file] = new Cache(file);
  }

  return instances[file];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.cache.clean"></a>[function <span class="apidocSignatureSpan">duo.cache.</span>clean ()](#apidoc.element.duo.cache.clean)
- description and source-code
```javascript
function* () {
  debug('clearing out cache instance list');
  yield each(values(instances), function* (instance) {
    yield instance.clean();
  });
  instances = {};
}
```
- example usage
```shell
...

  return instances[file];
};

exports.clean = function* () {
  debug('clearing out cache instance list');
  yield each(values(instances), function* (instance) {
    yield instance.clean();
  });
  instances = {};
};
...
```



# <a name="apidoc.module.duo.file"></a>[module duo.file](#apidoc.module.duo.file)

#### <a name="apidoc.element.duo.file.file"></a>[function <span class="apidocSignatureSpan">duo.</span>file (attrs, duo)](#apidoc.element.duo.file.file)
- description and source-code
```javascript
function File(attrs, duo) {
  if (!(this instanceof File)) return new File(attrs, duo);
  this.attrs = clone(attrs || {});
  this.duo = duo;

  var type = attrs.type ? '.' + attrs.type : '';
  var path = attrs.path || 'source' + type;

  // initial attrs
  this.attrs.path = resolve(attrs.root, path);
  this.attrs.type = attrs.type || extension(this.path);
  this.attrs.id = relative(duo.root(), this.path);

  // local vs remote
  this.attrs.local = !!(attrs.entry || attrs.local);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.duo.file.prototype"></a>[module duo.file.prototype](#apidoc.module.duo.file.prototype)

#### <a name="apidoc.element.duo.file.prototype.dependencies"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>dependencies ()](#apidoc.element.duo.file.prototype.dependencies)
- description and source-code
```javascript
dependencies = function () {
  if (this.deps) return this.deps;
  if (!this.src) return [];
  this.deps = filedeps(this.src, this.type);
  return this.deps;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.exists"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>exists ()](#apidoc.element.duo.file.prototype.exists)
- description and source-code
```javascript
function* () {
  if (this.raw != null) return true;
  else return yield exists(this.path);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.include"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>include ()](#apidoc.element.duo.file.prototype.include)
- description and source-code
```javascript
include = function (){
  return this[target][name].apply(this[target], arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.included"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>included ()](#apidoc.element.duo.file.prototype.included)
- description and source-code
```javascript
included = function (){
  return this[target][name].apply(this[target], arguments);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.json"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>json ()](#apidoc.element.duo.file.prototype.json)
- description and source-code
```javascript
json = function () {
  var json = clone(this.attrs);
  if (!json.entry) delete json.entry;
  return mask(json, fields);
}
```
- example usage
```shell
...
 var raw = this.raw;
 if (raw == null) raw = yield fs.readFile(this.path, 'utf8');
 this.attrs.src = raw;

 // transform the file and update attributes
 var entry = this.entry ? this : this.duo.entry();
 var res = yield this.plugins.run(this, entry);
 this.set(res[0].json());

 return this;
};

/**
* Check if the path to the file exists, unless we already have the raw source.
*
...
```

#### <a name="apidoc.element.duo.file.prototype.load"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>load ()](#apidoc.element.duo.file.prototype.load)
- description and source-code
```javascript
function* () {
  if (typeof this.src !== 'undefined') return this;

  // read the file
  var raw = this.raw;
  if (raw == null) raw = yield fs.readFile(this.path, 'utf8');
  this.attrs.src = raw;

  // transform the file and update attributes
  var entry = this.entry ? this : this.duo.entry();
  var res = yield this.plugins.run(this, entry);
  this.set(res[0].json());

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.local"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>local ()](#apidoc.element.duo.file.prototype.local)
- description and source-code
```javascript
local = function () {
  if (this.attrs.entry) return true;
  if (this.attrs.local) return !!this.attrs.local;
  return false;
}
```
- example usage
```shell
...
};

/**
* Determine if a file is a remote (eg: not a local)
*/

File.prototype.remote = function () {
 return !this.local();
};

/**
* Get the extension of a 'path'.
*
* @param {String} path
* @return {String} ext
...
```

#### <a name="apidoc.element.duo.file.prototype.modified"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>modified ()](#apidoc.element.duo.file.prototype.modified)
- description and source-code
```javascript
function* () {
  try {
    var stat = yield fs.stat(this.path);
    this.attrs.mtime = stat.mtime.getTime();
  } catch (e) {
    var now = new Date();
    this.attrs.mtime = now.getTime();
  }

  return this.mtime;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.remote"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>remote ()](#apidoc.element.duo.file.prototype.remote)
- description and source-code
```javascript
remote = function () {
  return !this.local();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.file.prototype.set"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>set (attrs)](#apidoc.element.duo.file.prototype.set)
- description and source-code
```javascript
set = function (attrs) {
  extend(this.attrs, attrs || {});
  return this;
}
```
- example usage
```shell
...
 var raw = this.raw;
 if (raw == null) raw = yield fs.readFile(this.path, 'utf8');
 this.attrs.src = raw;

 // transform the file and update attributes
 var entry = this.entry ? this : this.duo.entry();
 var res = yield this.plugins.run(this, entry);
 this.set(res[0].json());

 return this;
};

/**
* Check if the path to the file exists, unless we already have the raw source.
*
...
```

#### <a name="apidoc.element.duo.file.prototype.toString"></a>[function <span class="apidocSignatureSpan">duo.file.prototype.</span>toString ()](#apidoc.element.duo.file.prototype.toString)
- description and source-code
```javascript
toString = function () {
  var json = clone(this.attrs);
  if (!json.entry) delete json.entry;
  return mask(json, fields);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.duo.util"></a>[module duo.util](#apidoc.module.duo.util)

#### <a name="apidoc.element.duo.util.collect"></a>[function <span class="apidocSignatureSpan">duo.util.</span>collect (val, memo)](#apidoc.element.duo.util.collect)
- description and source-code
```javascript
collect = function (val, memo) {
  val.split(',').forEach(function (val) {
    memo.push(val);
  });

  return memo;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.util.entries"></a>[function <span class="apidocSignatureSpan">duo.util.</span>entries (root, list)](#apidoc.element.duo.util.entries)
- description and source-code
```javascript
entries = function (root, list) {
  return list.filter(globs).reduce(function (memo, entry) {
    if (isDir(path.join(root, entry))) {
      return memo.concat(listFiles(root, entry));
    } else {
      return memo.concat(entry);
    }
  }, []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.util.findroot"></a>[function <span class="apidocSignatureSpan">duo.util.</span>findroot (root)](#apidoc.element.duo.util.findroot)
- description and source-code
```javascript
findroot = function (root) {
  var cwd = process.cwd();
  if (root) return resolve(cwd, root);
  var sep = path.sep;
  var parts = cwd.split(sep);
  var dir = cwd;

  while (!exists(path.join(dir, 'component.json')) && parts.length > 1) {
    parts.pop();
    dir = parts.join(sep);
  }

  return parts.length <= 1
    ? cwd
    : dir;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.util.plugins"></a>[function <span class="apidocSignatureSpan">duo.util.</span>plugins (root, plugins)](#apidoc.element.duo.util.plugins)
- description and source-code
```javascript
plugins = function (root, plugins) {
  return plugins.map(function (plugin) {
    var local = resolve(root, plugin);
    var npm = resolve(root, 'node_modules', plugin);
    var cwd = resolve(process.cwd(), 'node_modules', plugin);
    var mod;

    if (exists(local)) mod = require(local);
    else if (exists(local + '.js')) mod = require(local);
    else if (exists(npm)) mod = require(npm);
    else mod = require(cwd);

    return Array.isArray(mod) ? mod : mod();
  }, []);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.util.token"></a>[function <span class="apidocSignatureSpan">duo.util.</span>token ()](#apidoc.element.duo.util.token)
- description and source-code
```javascript
token = function () {
  if ('GH_TOKEN' in process.env) return process.env.GH_TOKEN;

  var auth = netrc('api.github.com');
  if (auth && auth.password) return auth.password;

  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.duo.util.type"></a>[function <span class="apidocSignatureSpan">duo.util.</span>type (src)](#apidoc.element.duo.util.type)
- description and source-code
```javascript
type = function (src) {
  return langmap[detect(src)];
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
