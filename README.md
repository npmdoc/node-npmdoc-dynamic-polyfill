# npmdoc-dynamic-polyfill

#### api documentation for  dynamic-polyfill (v1.0.0)  [![npm package](https://img.shields.io/npm/v/npmdoc-dynamic-polyfill.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-dynamic-polyfill) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-dynamic-polyfill.svg)](https://travis-ci.org/npmdoc/node-npmdoc-dynamic-polyfill)

#### Dynamically polyfill only when needed by the browser. Complementary to Polyfill.io

[![NPM](https://nodei.co/npm/dynamic-polyfill.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/dynamic-polyfill)

- [https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-dynamic-polyfill/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "dynamic-polyfill",
    "version": "1.0.0",
    "description": "Dynamically polyfill only when needed by the browser. Complementary to Polyfill.io",
    "main": "index.js",
    "scripts": {
        "build": "babel src --presets babel-preset-es2015 --out-dir ./"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/pascalaoms/dynamic-polyfill"
    },
    "keywords": [
        "es6",
        "es7",
        "es2015",
        "es2016",
        "polyfill",
        "dynamic",
        "polfill.io"
    ],
    "author": "Pascal Klau <email@artofmyself.com> (http://artofmyself.com)",
    "license": "MIT",
    "devDependencies": {
        "babel-cli": "^6.22.2",
        "babel-preset-es2015": "^6.22.0"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
