# test coverage for  [pug (v0.1.0)](http://jade-lang.com)  [![npm package](https://img.shields.io/npm/v/npmtest-pug.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pug) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pug.svg)](https://travis-ci.org/npmtest/node-npmtest-pug)
#### A clean, whitespace-sensitive template language for writing HTML

[![NPM](https://nodei.co/npm/pug.png?downloads=true)](https://www.npmjs.com/package/pug)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pug/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pug/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pug/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pug/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pug/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pug/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pug/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pug/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-pug/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-pug/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-pug%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pug/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pug/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-pug%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pug/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pug/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pug/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bin": {
        "jade": "./bin/jade.js"
    },
    "browser": {
        "fs": false
    },
    "bugs": {
        "url": "https://github.com/jadejs/jade/issues"
    },
    "dependencies": {
        "pug-code-gen": "0.0.0",
        "pug-filters": "1.1.0",
        "pug-lexer": "0.0.0",
        "pug-linker": "0.0.0",
        "pug-loader": "0.0.0",
        "pug-parser": "0.0.0",
        "pug-runtime": "0.0.0",
        "pug-strip-comments": "0.0.1"
    },
    "deprecated": "Please update to the latest version of pug, at time of writing that is pug@2.0.0-alpha6",
    "description": "A clean, whitespace-sensitive template language for writing HTML",
    "devDependencies": {
        "browserify": "*",
        "browserify-middleware": "~4.1.0",
        "code-mirror": "~3.22.0",
        "coveralls": "^2.11.2",
        "doctypes": "^1.0.0",
        "express": "^4.10.4",
        "github-basic": "^5.0.0",
        "highlight-codemirror": "^4.6.1",
        "inconsolata": "0.0.2",
        "istanbul": "*",
        "jade-code-mirror": "~1.0.5",
        "jade-highlighter": "~1.0.5",
        "jquery": "^2.1.4",
        "jstransformer-cdata": "^1.0.0",
        "jstransformer-coffee-script": "^1.0.0",
        "jstransformer-less": "^2.1.0",
        "jstransformer-markdown-it": "^0.2.2",
        "jstransformer-stylus": "^1.0.0",
        "jstransformer-uglify-js": "^1.1.1",
        "jstransformer-verbatim": "^1.0.0",
        "less-file": "0.0.9",
        "linify": "*",
        "lsr": "^1.0.0",
        "markdown-it": "^5.0.1",
        "mocha": "*",
        "pull-request": "^3.0.0",
        "rimraf": "^2.2.8",
        "should": "*",
        "stop": "^3.0.0-rc1",
        "stylus": "*",
        "twbs": "0.0.6",
        "uglify-js": "^2.6.1"
    },
    "directories": {},
    "dist": {
        "shasum": "6958bf32ad56378b048f01949b380d470d8b5cc9",
        "tarball": "https://registry.npmjs.org/pug/-/pug-0.1.0.tgz"
    },
    "gitHead": "3ec1aea509172e1c79589487814bd4b0ffce8451",
    "homepage": "http://jade-lang.com",
    "license": "MIT",
    "main": "lib",
    "maintainers": [
        {
            "name": "davidglivar",
            "email": "davidglivar@gmail.com"
        },
        {
            "name": "forbeslindesay",
            "email": "forbes@lindesay.co.uk"
        }
    ],
    "name": "pug",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/jadejs/jade.git"
    },
    "scripts": {
        "coverage": "istanbul cover node_modules/mocha/bin/_mocha -- -R dot",
        "coveralls": "npm run coverage && cat ./coverage/lcov.info | coveralls",
        "prepublish": "npm prune && linify transform bin",
        "test": "mocha -R spec"
    },
    "version": "0.1.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
