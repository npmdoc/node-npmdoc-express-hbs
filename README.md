# npmdoc-express-hbs

#### api documentation for  [express-hbs (v1.0.4)](https://github.com/barc/express-hbs#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-express-hbs.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-express-hbs) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-express-hbs.svg)](https://travis-ci.org/npmdoc/node-npmdoc-express-hbs)

#### Express 3 handlebars template engine complete with multiple layouts, partials and blocks.

[![NPM](https://nodei.co/npm/express-hbs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/express-hbs)

- [https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-express-hbs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-express-hbs/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-express-hbs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-express-hbs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mario Gutierrez"
    },
    "bugs": {
        "url": "https://github.com/barc/express-hbs/issues"
    },
    "dependencies": {
        "handlebars": "4.0.6",
        "js-beautify": "1.6.8",
        "readdirp": "2.1.0"
    },
    "description": "Express 3 handlebars template engine complete with multiple layouts, partials and blocks.",
    "devDependencies": {
        "cookie-parser": "1.4.3",
        "express": "4.14.0",
        "grunt": "1.0.1",
        "grunt-mocha-cli": "3.0.0",
        "grunt-release": "0.14.0",
        "i18n": "0.8.3",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "rewire": "2.5.2",
        "supertest": "2.0.1"
    },
    "directories": {
        "example": "example"
    },
    "dist": {
        "shasum": "c4480d6e8a9f8c23500d3b1a1394f17eae451786",
        "tarball": "https://registry.npmjs.org/express-hbs/-/express-hbs-1.0.4.tgz"
    },
    "gitHead": "76b997802d57e683eb4d90e6c02225e3c7b5e584",
    "homepage": "https://github.com/barc/express-hbs#readme",
    "keywords": [
        "express3",
        "express",
        "handlebars",
        "layout",
        "partials"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "mgutz"
        },
        {
            "name": "erisds"
        }
    ],
    "name": "express-hbs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/barc/express-hbs.git"
    },
    "scripts": {
        "coverage": "NODE_ENV=testing ./node_modules/.bin/istanbul cover --dir test/coverage -x 'example/**' ./node_modules/.bin/_mocha",
        "test": "grunt"
    },
    "version": "1.0.4"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
