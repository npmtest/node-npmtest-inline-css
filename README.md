# npmtest-inline-css

#### basic test coverage for  [inline-css (v2.2.2)](https://github.com/jonkemp/inline-css#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-inline-css.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-inline-css) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-inline-css.svg)](https://travis-ci.org/npmtest/node-npmtest-inline-css)

#### Inline css into an html file.

[![NPM](https://nodei.co/npm/inline-css.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/inline-css)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-inline-css/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-inline-css/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-inline-css/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-inline-css/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-inline-css/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-inline-css/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-inline-css/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-inline-css/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-inline-css/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-inline-css/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-inline-css/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-inline-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-inline-css/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-inline-css/build/test-report.html](https://npmtest.github.io/node-npmtest-inline-css/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-inline-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-inline-css/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-inline-css/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-inline-css/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inline-css/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inline-css/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-inline-css/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-inline-css/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jonathan Kemp",
        "url": "http://jonkemp.com/"
    },
    "bugs": {
        "url": "https://github.com/jonkemp/inline-css/issues"
    },
    "dependencies": {
        "bluebird": "^2.9.25",
        "cheerio": "^0.19.0",
        "css-property": "^2.0.0",
        "css-rules": "^1.0.0",
        "extend": "^3.0.0",
        "extract-css": "^1.0.0",
        "flatten": "0.0.1",
        "object.pick": "^1.1.1",
        "style-selector": "^2.0.0"
    },
    "description": "Inline css into an html file.",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "gulp": "^3.9.0",
        "gulp-eslint": "^1.1.1",
        "gulp-mocha": "^2.0.0",
        "gulp-util": "^3.0.2",
        "mocha": "^2.1.0",
        "nyc": "^5.0.0",
        "should": "^5.2.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "da1e4b14e42a14ef55f9332b5ad1b2df657149a6",
        "tarball": "https://registry.npmjs.org/inline-css/-/inline-css-2.2.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "lib"
    ],
    "gitHead": "a796711b9cb4bfaaa3abc63223c73e0f6f793a69",
    "homepage": "https://github.com/jonkemp/inline-css#readme",
    "keywords": [
        "inline",
        "css",
        "html",
        "email"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "jonkemp"
        }
    ],
    "name": "inline-css",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/jonkemp/inline-css.git"
    },
    "scripts": {
        "coverage": "nyc npm test && nyc report",
        "coveralls": "nyc npm test && nyc report --reporter=text-lcov | coveralls",
        "lint": "gulp lint",
        "test": "mocha"
    },
    "version": "2.2.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
