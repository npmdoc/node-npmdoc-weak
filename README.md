# api documentation for  [weak (v1.0.1)](https://github.com/TooTallNate/node-weak#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-weak.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-weak) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-weak.svg)](https://travis-ci.org/npmdoc/node-npmdoc-weak)
#### Make weak references to JavaScript Objects.

[![NPM](https://nodei.co/npm/weak.png?downloads=true)](https://www.npmjs.com/package/weak)

[![apidoc](https://npmdoc.github.io/node-npmdoc-weak/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-weak_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-weak/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-weak/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-weak/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Ben Noordhuis",
        "email": "info@bnoordhuis.nl"
    },
    "bugs": {
        "url": "https://github.com/TooTallNate/node-weak/issues"
    },
    "contributors": [
        {
            "name": "Nathan Rajlich",
            "email": "nathan@tootallnate.net",
            "url": "http://tootallnate.net"
        }
    ],
    "dependencies": {
        "bindings": "^1.2.1",
        "nan": "^2.0.5"
    },
    "description": "Make weak references to JavaScript Objects.",
    "devDependencies": {
        "mocha": "~2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "ab99aab30706959aa0200cb8cf545bb9cb33b99e",
        "tarball": "https://registry.npmjs.org/weak/-/weak-1.0.1.tgz"
    },
    "gitHead": "1c3b0376dab966782e5d1fcf06f9fcb1309cb2c0",
    "gypfile": true,
    "homepage": "https://github.com/TooTallNate/node-weak#readme",
    "keywords": [
        "weak",
        "reference",
        "js",
        "javascript",
        "object",
        "function",
        "callback"
    ],
    "license": "MIT",
    "main": "lib/weak.js",
    "maintainers": [
        {
            "name": "TooTallNate",
            "email": "nathan@tootallnate.net"
        },
        {
            "name": "tootallnate",
            "email": "nathan@tootallnate.net"
        }
    ],
    "name": "weak",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/TooTallNate/node-weak.git"
    },
    "scripts": {
        "install": "node-gyp rebuild",
        "test": "mocha -gc --reporter spec"
    },
    "version": "1.0.1"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module weak](#apidoc.module.weak)
1.  [function <span class="apidocSignatureSpan">weak.</span>_create ()](#apidoc.element.weak._create)
1.  [function <span class="apidocSignatureSpan">weak.</span>_getEmitter ()](#apidoc.element.weak._getEmitter)
1.  [function <span class="apidocSignatureSpan">weak.</span>_setCallback ()](#apidoc.element.weak._setCallback)
1.  [function <span class="apidocSignatureSpan">weak.</span>addCallback (weakref, fn)](#apidoc.element.weak.addCallback)
1.  [function <span class="apidocSignatureSpan">weak.</span>addListener (weakref, fn)](#apidoc.element.weak.addListener)
1.  [function <span class="apidocSignatureSpan">weak.</span>callbacks (weakref)](#apidoc.element.weak.callbacks)
1.  [function <span class="apidocSignatureSpan">weak.</span>create (obj, fn)](#apidoc.element.weak.create)
1.  [function <span class="apidocSignatureSpan">weak.</span>get ()](#apidoc.element.weak.get)
1.  [function <span class="apidocSignatureSpan">weak.</span>isDead ()](#apidoc.element.weak.isDead)
1.  [function <span class="apidocSignatureSpan">weak.</span>isNearDeath ()](#apidoc.element.weak.isNearDeath)
1.  [function <span class="apidocSignatureSpan">weak.</span>isWeakRef ()](#apidoc.element.weak.isWeakRef)
1.  [function <span class="apidocSignatureSpan">weak.</span>listeners (weakref)](#apidoc.element.weak.listeners)
1.  [function <span class="apidocSignatureSpan">weak.</span>removeCallback (weakref, fn)](#apidoc.element.weak.removeCallback)
1.  [function <span class="apidocSignatureSpan">weak.</span>removeCallbacks (weakref)](#apidoc.element.weak.removeCallbacks)
1.  [function <span class="apidocSignatureSpan">weak.</span>removeListener (weakref, fn)](#apidoc.element.weak.removeListener)
1.  [function <span class="apidocSignatureSpan">weak.</span>removeListeners (weakref)](#apidoc.element.weak.removeListeners)
1.  [function <span class="apidocSignatureSpan">weak.</span>weaken (obj, fn)](#apidoc.element.weak.weaken)
1.  string <span class="apidocSignatureSpan">weak.</span>path



# <a name="apidoc.module.weak"></a>[module weak](#apidoc.module.weak)

#### <a name="apidoc.element.weak._create"></a>[function <span class="apidocSignatureSpan">weak.</span>_create ()](#apidoc.element.weak._create)
- description and source-code
```javascript
function _create() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak._getEmitter"></a>[function <span class="apidocSignatureSpan">weak.</span>_getEmitter ()](#apidoc.element.weak._getEmitter)
- description and source-code
```javascript
function _getEmitter() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak._setCallback"></a>[function <span class="apidocSignatureSpan">weak.</span>_setCallback ()](#apidoc.element.weak._setCallback)
- description and source-code
```javascript
function _setCallback() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.addCallback"></a>[function <span class="apidocSignatureSpan">weak.</span>addCallback (weakref, fn)](#apidoc.element.weak.addCallback)
- description and source-code
```javascript
function addCallback(weakref, fn) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.on(CB, fn);
}
```
- example usage
```shell
...

### Boolean weak.isWeakRef(Object obj)

Checks to see if 'obj' is "weak reference" instance. Returns 'true' if the
passed in object is a "weak reference", 'false' otherwise.


### EventEmitter weak.addCallback(Weakref ref, Function callback)

Adds 'callback' to the Array of callback functions that will be invoked before the
Object gets garbage collected. The callbacks get executed in the order that they
are added.


### EventEmitter weak.removeCallback(Weakref ref, Function callback)
...
```

#### <a name="apidoc.element.weak.addListener"></a>[function <span class="apidocSignatureSpan">weak.</span>addListener (weakref, fn)](#apidoc.element.weak.addListener)
- description and source-code
```javascript
function addCallback(weakref, fn) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.on(CB, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.callbacks"></a>[function <span class="apidocSignatureSpan">weak.</span>callbacks (weakref)](#apidoc.element.weak.callbacks)
- description and source-code
```javascript
function callbacks(weakref) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.listeners(CB);
}
```
- example usage
```shell
...

### EventEmitter weak.removeCallbacks(Weakref ref)

Empties the Array of callback functions that will be invoked before the Object gets
garbage collected.


### Array weak.callbacks(Weakref ref)

Returns an Array that 'ref' iterates through to invoke the GC callbacks. This
utilizes node's 'EventEmitter#listeners()' function and therefore returns a copy
in node 0.10 and newer.
...
```

#### <a name="apidoc.element.weak.create"></a>[function <span class="apidocSignatureSpan">weak.</span>create (obj, fn)](#apidoc.element.weak.create)
- description and source-code
```javascript
function create(obj, fn) {
  var weakref = bindings._create(obj, new Emitter());
  if ('function' == typeof fn) {
    exports.addCallback(weakref, fn);
  }
  return weakref;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.get"></a>[function <span class="apidocSignatureSpan">weak.</span>get ()](#apidoc.element.weak.get)
- description and source-code
```javascript
function get() { [native code] }
```
- example usage
```shell
...
The Object can be a regular Object, an Array, a Function, a RegExp, or any of
the primitive types or constructor function created with 'new'.

Optionally, you can set a callback function to be invoked
before the object is garbage collected.


### Object weak.get(Weakref ref)

'get()' returns the actual reference to the Object that this weak reference was
created with. If this is called with a dead reference, 'undefined' is returned.


### Boolean weak.isDead(Weakref ref)
...
```

#### <a name="apidoc.element.weak.isDead"></a>[function <span class="apidocSignatureSpan">weak.</span>isDead ()](#apidoc.element.weak.isDead)
- description and source-code
```javascript
function isDead() { [native code] }
```
- example usage
```shell
...

### Object weak.get(Weakref ref)

'get()' returns the actual reference to the Object that this weak reference was
created with. If this is called with a dead reference, 'undefined' is returned.


### Boolean weak.isDead(Weakref ref)

Checks to see if 'ref' is a dead reference. Returns 'true' if the original Object
has already been GC'd, 'false' otherwise.


### Boolean weak.isNearDeath(Weakref ref)
...
```

#### <a name="apidoc.element.weak.isNearDeath"></a>[function <span class="apidocSignatureSpan">weak.</span>isNearDeath ()](#apidoc.element.weak.isNearDeath)
- description and source-code
```javascript
function isNearDeath() { [native code] }
```
- example usage
```shell
...

### Boolean weak.isDead(Weakref ref)

Checks to see if 'ref' is a dead reference. Returns 'true' if the original Object
has already been GC'd, 'false' otherwise.


### Boolean weak.isNearDeath(Weakref ref)

Checks to see if 'ref' is "near death". This will be 'true' exactly during the
weak reference callback function, and 'false' any other time.


### Boolean weak.isWeakRef(Object obj)
...
```

#### <a name="apidoc.element.weak.isWeakRef"></a>[function <span class="apidocSignatureSpan">weak.</span>isWeakRef ()](#apidoc.element.weak.isWeakRef)
- description and source-code
```javascript
function isWeakRef() { [native code] }
```
- example usage
```shell
...

### Boolean weak.isNearDeath(Weakref ref)

Checks to see if 'ref' is "near death". This will be 'true' exactly during the
weak reference callback function, and 'false' any other time.


### Boolean weak.isWeakRef(Object obj)

Checks to see if 'obj' is "weak reference" instance. Returns 'true' if the
passed in object is a "weak reference", 'false' otherwise.


### EventEmitter weak.addCallback(Weakref ref, Function callback)
...
```

#### <a name="apidoc.element.weak.listeners"></a>[function <span class="apidocSignatureSpan">weak.</span>listeners (weakref)](#apidoc.element.weak.listeners)
- description and source-code
```javascript
function callbacks(weakref) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.listeners(CB);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.removeCallback"></a>[function <span class="apidocSignatureSpan">weak.</span>removeCallback (weakref, fn)](#apidoc.element.weak.removeCallback)
- description and source-code
```javascript
function removeCallback(weakref, fn) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.removeListener(CB, fn);
}
```
- example usage
```shell
...
### EventEmitter weak.addCallback(Weakref ref, Function callback)

Adds 'callback' to the Array of callback functions that will be invoked before the
Object gets garbage collected. The callbacks get executed in the order that they
are added.


### EventEmitter weak.removeCallback(Weakref ref, Function callback)

Removes 'callback' from the Array of callback functions that will be invoked before
the Object gets garbage collected.


### EventEmitter weak.removeCallbacks(Weakref ref)
...
```

#### <a name="apidoc.element.weak.removeCallbacks"></a>[function <span class="apidocSignatureSpan">weak.</span>removeCallbacks (weakref)](#apidoc.element.weak.removeCallbacks)
- description and source-code
```javascript
function removeCallbacks(weakref) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.removeAllListeners(CB);
}
```
- example usage
```shell
...

### EventEmitter weak.removeCallback(Weakref ref, Function callback)

Removes 'callback' from the Array of callback functions that will be invoked before
the Object gets garbage collected.


### EventEmitter weak.removeCallbacks(Weakref ref)

Empties the Array of callback functions that will be invoked before the Object gets
garbage collected.


### Array weak.callbacks(Weakref ref)
...
```

#### <a name="apidoc.element.weak.removeListener"></a>[function <span class="apidocSignatureSpan">weak.</span>removeListener (weakref, fn)](#apidoc.element.weak.removeListener)
- description and source-code
```javascript
function removeCallback(weakref, fn) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.removeListener(CB, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.removeListeners"></a>[function <span class="apidocSignatureSpan">weak.</span>removeListeners (weakref)](#apidoc.element.weak.removeListeners)
- description and source-code
```javascript
function removeCallbacks(weakref) {
  var emitter = bindings._getEmitter(weakref);
  return emitter.removeAllListeners(CB);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.weak.weaken"></a>[function <span class="apidocSignatureSpan">weak.</span>weaken (obj, fn)](#apidoc.element.weak.weaken)
- description and source-code
```javascript
function create(obj, fn) {
  var weakref = bindings._create(obj, new Emitter());
  if ('function' == typeof fn) {
    exports.addCallback(weakref, fn);
  }
  return weakref;
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
