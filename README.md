# npmtest-multiline

#### basic test coverage for  [multiline (v1.0.2)](https://github.com/sindresorhus/multiline)  [![npm package](https://img.shields.io/npm/v/npmtest-multiline.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-multiline) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-multiline.svg)](https://travis-ci.org/npmtest/node-npmtest-multiline)

#### Multiline strings in JavaScript

[![NPM](https://nodei.co/npm/multiline.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/multiline)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-multiline/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-multiline/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-multiline/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-multiline/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-multiline/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-multiline/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-multiline/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-multiline/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-multiline/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-multiline/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-multiline/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-multiline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-multiline/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-multiline/build/test-report.html](https://npmtest.github.io/node-npmtest-multiline/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-multiline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-multiline/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-multiline/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-multiline/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-multiline/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-multiline/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-multiline/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-multiline/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sindre Sorhus",
        "url": "http://sindresorhus.com"
    },
    "bugs": {
        "url": "https://github.com/sindresorhus/multiline/issues"
    },
    "dependencies": {
        "strip-indent": "^1.0.0"
    },
    "description": "Multiline strings in JavaScript",
    "devDependencies": {
        "browserify": "^6.0.2",
        "callsites": "^1.0.0",
        "mocha": "*",
        "uglify-js": "^2.4.13"
    },
    "directories": {},
    "dist": {
        "shasum": "69b1f25ff074d2828904f244ddd06b7d96ef6c93",
        "tarball": "https://registry.npmjs.org/multiline/-/multiline-1.0.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "files": [
        "index.js",
        "browser.js"
    ],
    "gitHead": "bc7665a7f7e6a0c17956bbda532912d09ddb8be1",
    "homepage": "https://github.com/sindresorhus/multiline",
    "keywords": [
        "browser",
        "multiline",
        "multi-line",
        "multiple",
        "line",
        "comment",
        "string",
        "str",
        "text",
        "comment"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "sindresorhus"
        }
    ],
    "name": "multiline",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/sindresorhus/multiline.git"
    },
    "scripts": {
        "browser": "browserify -s $npm_package_name -o browser.js .",
        "test": "mocha"
    },
    "version": "1.0.2",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
