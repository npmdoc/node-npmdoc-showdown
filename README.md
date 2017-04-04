# api documentation for  [showdown (v1.6.4)](http://showdownjs.github.io/showdown/)  [![npm package](https://img.shields.io/npm/v/npmdoc-showdown.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-showdown) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-showdown.svg)](https://travis-ci.org/npmdoc/node-npmdoc-showdown)
#### A Markdown to HTML converter written in Javascript

[![NPM](https://nodei.co/npm/showdown.png?downloads=true)](https://www.npmjs.com/package/showdown)

[![apidoc](https://npmdoc.github.io/node-npmdoc-showdown/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-showdown_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-showdown/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-showdown/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-showdown/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Estevão Santos"
    },
    "bin": {
        "showdown": "bin/showdown.js"
    },
    "bugs": {
        "url": "https://github.com/showdownjs/showdown/issues"
    },
    "contributors": [
        {
            "name": "John Gruber"
        },
        {
            "name": "John Fraser"
        },
        {
            "name": "Corey Innis"
        },
        {
            "name": "Remy Sharp"
        },
        {
            "name": "Konstantin Käfer"
        },
        {
            "name": "Roger Braun"
        },
        {
            "name": "Dominic Tarr"
        },
        {
            "name": "Cat Chen"
        },
        {
            "name": "Titus Stone"
        },
        {
            "name": "Rob Sutherland"
        },
        {
            "name": "Pavel Lang"
        },
        {
            "name": "Ben Combee"
        },
        {
            "name": "Adam Backstrom"
        },
        {
            "name": "Pascal Deschênes"
        },
        {
            "name": "Estevão Santos"
        }
    ],
    "dependencies": {
        "yargs": "^6.6.0"
    },
    "description": "A Markdown to HTML converter written in Javascript",
    "devDependencies": {
        "chai": "^3.5.0",
        "grunt": "^1.0.1",
        "grunt-contrib-clean": "^1.0.0",
        "grunt-contrib-concat": "^1.0.1",
        "grunt-contrib-jshint": "^1.1.0",
        "grunt-contrib-uglify": "^2.0.0",
        "grunt-conventional-changelog": "^6.1.0",
        "grunt-conventional-github-releaser": "^1.0.0",
        "grunt-endline": "^0.6.1",
        "grunt-eslint": "^19.0.0",
        "grunt-simple-mocha": "^0.4.0",
        "js-beautify": "^1.5.6",
        "load-grunt-tasks": "^3.2.0",
        "performance-now": "^2.0.0",
        "quiet-grunt": "^0.2.3",
        "semver": "^5.0.0",
        "semver-sort": "0.0.4",
        "sinon": "^1.14.1",
        "source-map-support": "^0.4.11"
    },
    "directories": {},
    "dist": {
        "shasum": "056bbb654ecdb8d8643ae12d6d597893ccaf46c6",
        "tarball": "https://registry.npmjs.org/showdown/-/showdown-1.6.4.tgz"
    },
    "gitHead": "072973ab8b027b86fb54bc6eb59850dc80f42b3a",
    "homepage": "http://showdownjs.github.io/showdown/",
    "keywords": [
        "markdown",
        "converter"
    ],
    "license": "BSD-3-Clause",
    "main": "./dist/showdown.js",
    "maintainers": [
        {
            "name": "coreyti",
            "email": "corey@coolerator.net"
        },
        {
            "name": "pdeschen",
            "email": "pdeschen@rassemblr.com"
        },
        {
            "name": "tivie",
            "email": "estevao.santos@gmail.com"
        }
    ],
    "name": "showdown",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/showdownjs/showdown.git",
        "web": "https://github.com/showdownjs/showdown"
    },
    "scripts": {
        "test": "grunt test"
    },
    "version": "1.6.4"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module showdown](#apidoc.module.showdown)
1.  [function <span class="apidocSignatureSpan">showdown.</span>Converter (converterOptions)](#apidoc.element.showdown.Converter)
1.  [function <span class="apidocSignatureSpan">showdown.</span>extension (name, ext)](#apidoc.element.showdown.extension)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getAllExtensions ()](#apidoc.element.showdown.getAllExtensions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getDefaultOptions (simple)](#apidoc.element.showdown.getDefaultOptions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getFlavor ()](#apidoc.element.showdown.getFlavor)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getFlavorOptions (name)](#apidoc.element.showdown.getFlavorOptions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getOption (key)](#apidoc.element.showdown.getOption)
1.  [function <span class="apidocSignatureSpan">showdown.</span>getOptions ()](#apidoc.element.showdown.getOptions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>removeExtension (name)](#apidoc.element.showdown.removeExtension)
1.  [function <span class="apidocSignatureSpan">showdown.</span>resetExtensions ()](#apidoc.element.showdown.resetExtensions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>resetOptions ()](#apidoc.element.showdown.resetOptions)
1.  [function <span class="apidocSignatureSpan">showdown.</span>setFlavor (name)](#apidoc.element.showdown.setFlavor)
1.  [function <span class="apidocSignatureSpan">showdown.</span>setOption (key, value)](#apidoc.element.showdown.setOption)
1.  [function <span class="apidocSignatureSpan">showdown.</span>subParser (name, func)](#apidoc.element.showdown.subParser)
1.  [function <span class="apidocSignatureSpan">showdown.</span>validateExtension (ext)](#apidoc.element.showdown.validateExtension)
1.  object <span class="apidocSignatureSpan">showdown.</span>extensions
1.  object <span class="apidocSignatureSpan">showdown.</span>helper

#### [module showdown.helper](#apidoc.module.showdown.helper)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>encodeEmailAddress (mail)](#apidoc.element.showdown.helper.encodeEmailAddress)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>escapeCharacters (text, charsToEscape, afterBackslash)](#apidoc.element.showdown.helper.escapeCharacters)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>escapeCharactersCallback (wholeMatch, m1)](#apidoc.element.showdown.helper.escapeCharactersCallback)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>forEach (obj, callback)](#apidoc.element.showdown.helper.forEach)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>isArray (a)](#apidoc.element.showdown.helper.isArray)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>isFunction (a)](#apidoc.element.showdown.helper.isFunction)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>isString (a)](#apidoc.element.showdown.helper.isString)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>isUndefined (value)](#apidoc.element.showdown.helper.isUndefined)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>matchRecursiveRegExp (str, left, right, flags)](#apidoc.element.showdown.helper.matchRecursiveRegExp)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>replaceRecursiveRegExp (str, replacement, left, right, flags)](#apidoc.element.showdown.helper.replaceRecursiveRegExp)
1.  [function <span class="apidocSignatureSpan">showdown.helper.</span>stdExtName (s)](#apidoc.element.showdown.helper.stdExtName)
1.  object <span class="apidocSignatureSpan">showdown.helper.</span>regexes



# <a name="apidoc.module.showdown"></a>[module showdown](#apidoc.module.showdown)

#### <a name="apidoc.element.showdown.Converter"></a>[function <span class="apidocSignatureSpan">showdown.</span>Converter (converterOptions)](#apidoc.element.showdown.Converter)
- description and source-code
```javascript
Converter = function (converterOptions) {
  'use strict';

  var
<span class="apidocCodeCommentSpan">      /**
       * Options used by this converter
       * @private
       * @type {{}}
       */
</span>      options = {},

      /**
       * Language extensions used by this converter
       * @private
       * @type {Array}
       */
      langExtensions = [],

      /**
       * Output modifiers extensions used by this converter
       * @private
       * @type {Array}
       */
      outputModifiers = [],

      /**
       * Event listeners
       * @private
       * @type {{}}
       */
      listeners = {},

      /**
       * The flavor set in this converter
       */
      setConvFlavor = setFlavor;

  _constructor();

  /**
   * Converter constructor
   * @private
   */
  function _constructor () {
    converterOptions = converterOptions || {};

    for (var gOpt in globalOptions) {
      if (globalOptions.hasOwnProperty(gOpt)) {
        options[gOpt] = globalOptions[gOpt];
      }
    }

    // Merge options
    if (typeof converterOptions === 'object') {
      for (var opt in converterOptions) {
        if (converterOptions.hasOwnProperty(opt)) {
          options[opt] = converterOptions[opt];
        }
      }
    } else {
      throw Error('Converter expects the passed parameter to be an object, but ' + typeof converterOptions +
      ' was passed instead.');
    }

    if (options.extensions) {
      showdown.helper.forEach(options.extensions, _parseExtension);
    }
  }

  /**
   * Parse extension
   * @param {*} ext
   * @param {string} [name='']
   * @private
   */
  function _parseExtension (ext, name) {

    name = name || null;
    // If it's a string, the extension was previously loaded
    if (showdown.helper.isString(ext)) {
      ext = showdown.helper.stdExtName(ext);
      name = ext;

      // LEGACY_SUPPORT CODE
      if (showdown.extensions[ext]) {
        console.warn('DEPRECATION WARNING: ' + ext + ' is an old extension that uses a deprecated loading method.' +
          'Please inform the developer that the extension should be updated!');
        legacyExtensionLoading(showdown.extensions[ext], ext);
        return;
      // END LEGACY SUPPORT CODE

      } else if (!showdown.helper.isUndefined(extensions[ext])) {
        ext = extensions[ext];

      } else {
        throw Error('Extension "' + ext + '" could not be loaded. It was either not found or is not a valid extension.');
      }
    }

    if (typeof ext === 'function') {
      ext = ext();
    }

    if (!showdown.helper.isArray(ext)) {
      ext = [ext];
    }

    var validExt = validate(ext, name);
    if (!validExt.valid) {
      throw Error(validExt.error);
    }

    for (var i = 0; i < ext.length; ++i) {
      switch (ext[i].type) {

        case 'lang':
          langExtensions.push(ext[i]);
          break;

        case 'output':
          outputModifiers.push(ext[i]);
          break;
      }
      if (ext[i].hasOwnProperty('listeners')) {
        for (var ln in ext[i].listeners) {
          if (ext[i].listeners.hasOwnProperty(ln)) {
            listen(ln, ext[i].listeners[ln]);
          }
        }
      }
    }

  }

  /**
   * LEGACY_SUPPORT
   * @param {*} ext
   * @param {string} name
   */
  function legacyExtensionLoading (ext, name) {
    if (typeof ext === 'function') {
      ext = ext(new showdown.Converter());
    }
    if (!showdown.helper.isArray(ext)) {
      ext = [ext];
    }
    var valid = validate(ext, name);

    if (!valid.valid) {
      throw Error(valid.error);
    }

    for (var i = 0; i < ext.length; ++i) {
      switch (ext[i].type) {
        case 'lang':
          langExtensions.push(ext[i]);
          break;
        case 'output':
          outputModifiers.push(ext[i]);
          break;
        default:// should never reach here
          throw Error('Extension loader error: Type unrecognized!!!');
      }
    }
  }

  /**
   * Listen to an event
   * @param {string} name
   * @param {function} callback
   */
  function listen (name, callback) {
    if (!showdown.helper.isString(name)) {
      throw Error('Invalid argument in converter.listen ...
```
- example usage
```shell
...

## Quick Example

### Node

'''js
var showdown  = require('showdown'),
    converter = new showdown.Converter(),
    text      = '#hello, markdown!',
    html      = converter.makeHtml(text);
'''

### Browser

'''js
...
```

#### <a name="apidoc.element.showdown.extension"></a>[function <span class="apidocSignatureSpan">showdown.</span>extension (name, ext)](#apidoc.element.showdown.extension)
- description and source-code
```javascript
extension = function (name, ext) {
  'use strict';

  if (!showdown.helper.isString(name)) {
    throw Error('Extension \'name\' must be a string');
  }

  name = showdown.helper.stdExtName(name);

  // Getter
  if (showdown.helper.isUndefined(ext)) {
    if (!extensions.hasOwnProperty(name)) {
      throw Error('Extension named ' + name + ' is not registered!');
    }
    return extensions[name];

    // Setter
  } else {
    // Expand extension if it's wrapped in a function
    if (typeof ext === 'function') {
      ext = ext();
    }

    // Ensure extension is an array
    if (!showdown.helper.isArray(ext)) {
      ext = [ext];
    }

    var validExtension = validate(ext, name);

    if (validExtension.valid) {
      extensions[name] = ext;
    } else {
      throw Error(validExtension.error);
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.getAllExtensions"></a>[function <span class="apidocSignatureSpan">showdown.</span>getAllExtensions ()](#apidoc.element.showdown.getAllExtensions)
- description and source-code
```javascript
getAllExtensions = function () {
  'use strict';
  return extensions;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.getDefaultOptions"></a>[function <span class="apidocSignatureSpan">showdown.</span>getDefaultOptions (simple)](#apidoc.element.showdown.getDefaultOptions)
- description and source-code
```javascript
getDefaultOptions = function (simple) {
  'use strict';
  return getDefaultOpts(simple);
}
```
- example usage
```shell
...
var thisConverterSpecificOptions = converter.getOptions();
'''

### Retrieve the default options

You can get showdown's default options with:
'''js
var defaultOptions = showdown.getDefaultOptions();
'''

### Valid Options

* **omitExtraWLInCodeBlocks**: (boolean) [default false] Omit the trailing newline in a code block. Ex:

   This:
...
```

#### <a name="apidoc.element.showdown.getFlavor"></a>[function <span class="apidocSignatureSpan">showdown.</span>getFlavor ()](#apidoc.element.showdown.getFlavor)
- description and source-code
```javascript
getFlavor = function () {
  'use strict';
  return setFlavor;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.getFlavorOptions"></a>[function <span class="apidocSignatureSpan">showdown.</span>getFlavorOptions (name)](#apidoc.element.showdown.getFlavorOptions)
- description and source-code
```javascript
getFlavorOptions = function (name) {
  'use strict';
  if (flavor.hasOwnProperty(name)) {
    return flavor[name];
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.getOption"></a>[function <span class="apidocSignatureSpan">showdown.</span>getOption (key)](#apidoc.element.showdown.getOption)
- description and source-code
```javascript
getOption = function (key) {
  'use strict';
  return globalOptions[key];
}
```
- example usage
```shell
...

Showdown provides 2 methods (both local and global) to retrieve previous set options.

#### getOption()

'''js
// Global
var myOption = showdown.getOption('optionKey');

//Local
var myOption = converter.getOption('optionKey');
'''

#### getOptions()
...
```

#### <a name="apidoc.element.showdown.getOptions"></a>[function <span class="apidocSignatureSpan">showdown.</span>getOptions ()](#apidoc.element.showdown.getOptions)
- description and source-code
```javascript
getOptions = function () {
  'use strict';
  return globalOptions;
}
```
- example usage
```shell
...
var myOption = converter.getOption('optionKey');
'''

#### getOptions()

'''js
// Global
var showdownGlobalOptions = showdown.getOptions();

//Local
var thisConverterSpecificOptions = converter.getOptions();
'''

### Retrieve the default options
...
```

#### <a name="apidoc.element.showdown.removeExtension"></a>[function <span class="apidocSignatureSpan">showdown.</span>removeExtension (name)](#apidoc.element.showdown.removeExtension)
- description and source-code
```javascript
removeExtension = function (name) {
  'use strict';
  delete extensions[name];
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.resetExtensions"></a>[function <span class="apidocSignatureSpan">showdown.</span>resetExtensions ()](#apidoc.element.showdown.resetExtensions)
- description and source-code
```javascript
resetExtensions = function () {
  'use strict';
  extensions = {};
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.resetOptions"></a>[function <span class="apidocSignatureSpan">showdown.</span>resetOptions ()](#apidoc.element.showdown.resetOptions)
- description and source-code
```javascript
resetOptions = function () {
  'use strict';
  globalOptions = getDefaultOpts(true);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.setFlavor"></a>[function <span class="apidocSignatureSpan">showdown.</span>setFlavor (name)](#apidoc.element.showdown.setFlavor)
- description and source-code
```javascript
setFlavor = function (name) {
  'use strict';
  if (!flavor.hasOwnProperty(name)) {
    throw Error(name + ' flavor was not found');
  }
  var preset = flavor[name];
  setFlavor = name;
  for (var option in preset) {
    if (preset.hasOwnProperty(option)) {
      globalOptions[option] = preset[option];
    }
  }
}
```
- example usage
```shell
...
 * original - original markdown flavor as in [John Gruber's spec](https://daringfireball.net/projects/markdown/)
 * vanilla  - showdown base flavor (as from v1.3.1)
 * github   - GFM (GitHub Flavored Markdown)


### Global
'''javascript
showdown.setFlavor('github');
'''

### Instance
'''javascript
converter.setFlavor('github');
'''
...
```

#### <a name="apidoc.element.showdown.setOption"></a>[function <span class="apidocSignatureSpan">showdown.</span>setOption (key, value)](#apidoc.element.showdown.setOption)
- description and source-code
```javascript
setOption = function (key, value) {
  'use strict';
  globalOptions[key] = value;
  return this;
}
```
- example usage
```shell
...
Options can be set:

#### Globally

Setting a "global" option affects all instances of showdown

'''js
showdown.setOption('optionKey', 'value');
'''

#### Locally
Setting a "local" option only affects the specified Converter object.
Local options can be set:

* **through the constructor**
...
```

#### <a name="apidoc.element.showdown.subParser"></a>[function <span class="apidocSignatureSpan">showdown.</span>subParser (name, func)](#apidoc.element.showdown.subParser)
- description and source-code
```javascript
subParser = function (name, func) {
  'use strict';
  if (showdown.helper.isString(name)) {
    if (typeof func !== 'undefined') {
      parsers[name] = func;
    } else {
      if (parsers.hasOwnProperty(name)) {
        return parsers[name];
      } else {
        throw Error('SubParser named ' + name + ' not registered!');
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.validateExtension"></a>[function <span class="apidocSignatureSpan">showdown.</span>validateExtension (ext)](#apidoc.element.showdown.validateExtension)
- description and source-code
```javascript
validateExtension = function (ext) {
  'use strict';

  var validateExtension = validate(ext, null);
  if (!validateExtension.valid) {
    console.warn(validateExtension.error);
    return false;
  }
  return true;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.showdown.helper"></a>[module showdown.helper](#apidoc.module.showdown.helper)

#### <a name="apidoc.element.showdown.helper.encodeEmailAddress"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>encodeEmailAddress (mail)](#apidoc.element.showdown.helper.encodeEmailAddress)
- description and source-code
```javascript
encodeEmailAddress = function (mail) {
  'use strict';
  var encode = [
    function (ch) {
      return '&#' + ch.charCodeAt(0) + ';';
    },
    function (ch) {
      return '&#x' + ch.charCodeAt(0).toString(16) + ';';
    },
    function (ch) {
      return ch;
    }
  ];

  mail = mail.replace(/./g, function (ch) {
    if (ch === '@') {
      // this *must* be encoded. I insist.
      ch = encode[Math.floor(Math.random() * 2)](ch);
    } else {
      var r = Math.random();
      // roughly 10% raw, 45% hex, 45% dec
      ch = (
        r > 0.9 ? encode[2](ch) : r > 0.45 ? encode[1](ch) : encode[0](ch)
      );
    }
    return ch;
  });

  return mail;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.escapeCharacters"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>escapeCharacters (text, charsToEscape, afterBackslash)](#apidoc.element.showdown.helper.escapeCharacters)
- description and source-code
```javascript
escapeCharacters = function (text, charsToEscape, afterBackslash) {
  'use strict';
  // First we have to escape the escape characters so that
  // we can build a character class out of them
  var regexString = '([' + charsToEscape.replace(/([\[\]\\])/g, '\\$1') + '])';

  if (afterBackslash) {
    regexString = '\\\\' + regexString;
  }

  var regex = new RegExp(regexString, 'g');
  text = text.replace(regex, escapeCharactersCallback);

  return text;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.escapeCharactersCallback"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>escapeCharactersCallback (wholeMatch, m1)](#apidoc.element.showdown.helper.escapeCharactersCallback)
- description and source-code
```javascript
function escapeCharactersCallback(wholeMatch, m1) {
  'use strict';
  var charCodeToEscape = m1.charCodeAt(0);
  return '¨E' + charCodeToEscape + 'E';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.forEach"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>forEach (obj, callback)](#apidoc.element.showdown.helper.forEach)
- description and source-code
```javascript
forEach = function (obj, callback) {
  'use strict';
  // check if obj is defined
  if (showdown.helper.isUndefined(obj)) {
    throw new Error('obj param is required');
  }

  if (showdown.helper.isUndefined(callback)) {
    throw new Error('callback param is required');
  }

  if (!showdown.helper.isFunction(callback)) {
    throw new Error('callback param must be a function/closure');
  }

  if (typeof obj.forEach === 'function') {
    obj.forEach(callback);
  } else if (showdown.helper.isArray(obj)) {
    for (var i = 0; i < obj.length; i++) {
      callback(obj[i], i, obj);
    }
  } else if (typeof (obj) === 'object') {
    for (var prop in obj) {
      if (obj.hasOwnProperty(prop)) {
        callback(obj[prop], prop, obj);
      }
    }
  } else {
    throw new Error('obj does not seem to be an array or an iterable object');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.isArray"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>isArray (a)](#apidoc.element.showdown.helper.isArray)
- description and source-code
```javascript
isArray = function (a) {
  'use strict';
  return a.constructor === Array;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.isFunction"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>isFunction (a)](#apidoc.element.showdown.helper.isFunction)
- description and source-code
```javascript
isFunction = function (a) {
  'use strict';
  var getType = {};
  return a && getType.toString.call(a) === '[object Function]';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.isString"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>isString (a)](#apidoc.element.showdown.helper.isString)
- description and source-code
```javascript
isString = function (a) {
  'use strict';
  return (typeof a === 'string' || a instanceof String);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.isUndefined"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>isUndefined (value)](#apidoc.element.showdown.helper.isUndefined)
- description and source-code
```javascript
isUndefined = function (value) {
  'use strict';
  return typeof value === 'undefined';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.matchRecursiveRegExp"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>matchRecursiveRegExp (str, left, right, flags)](#apidoc.element.showdown.helper.matchRecursiveRegExp)
- description and source-code
```javascript
matchRecursiveRegExp = function (str, left, right, flags) {
  'use strict';

  var matchPos = rgxFindMatchPos (str, left, right, flags),
      results = [];

  for (var i = 0; i < matchPos.length; ++i) {
    results.push([
      str.slice(matchPos[i].wholeMatch.start, matchPos[i].wholeMatch.end),
      str.slice(matchPos[i].match.start, matchPos[i].match.end),
      str.slice(matchPos[i].left.start, matchPos[i].left.end),
      str.slice(matchPos[i].right.start, matchPos[i].right.end)
    ]);
  }
  return results;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.replaceRecursiveRegExp"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>replaceRecursiveRegExp (str, replacement, left, right, flags)](#apidoc.element.showdown.helper.replaceRecursiveRegExp)
- description and source-code
```javascript
replaceRecursiveRegExp = function (str, replacement, left, right, flags) {
  'use strict';

  if (!showdown.helper.isFunction(replacement)) {
    var repStr = replacement;
    replacement = function () {
      return repStr;
    };
  }

  var matchPos = rgxFindMatchPos(str, left, right, flags),
      finalStr = str,
      lng = matchPos.length;

  if (lng > 0) {
    var bits = [];
    if (matchPos[0].wholeMatch.start !== 0) {
      bits.push(str.slice(0, matchPos[0].wholeMatch.start));
    }
    for (var i = 0; i < lng; ++i) {
      bits.push(
        replacement(
          str.slice(matchPos[i].wholeMatch.start, matchPos[i].wholeMatch.end),
          str.slice(matchPos[i].match.start, matchPos[i].match.end),
          str.slice(matchPos[i].left.start, matchPos[i].left.end),
          str.slice(matchPos[i].right.start, matchPos[i].right.end)
        )
      );
      if (i < lng - 1) {
        bits.push(str.slice(matchPos[i].wholeMatch.end, matchPos[i + 1].wholeMatch.start));
      }
    }
    if (matchPos[lng - 1].wholeMatch.end < str.length) {
      bits.push(str.slice(matchPos[lng - 1].wholeMatch.end));
    }
    finalStr = bits.join('');
  }
  return finalStr;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.showdown.helper.stdExtName"></a>[function <span class="apidocSignatureSpan">showdown.helper.</span>stdExtName (s)](#apidoc.element.showdown.helper.stdExtName)
- description and source-code
```javascript
stdExtName = function (s) {
  'use strict';
  return s.replace(/[_?*+\/\\.^-]/g, '').replace(/\s/g, '').toLowerCase();
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
