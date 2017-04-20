# npmtest-backbone.radio

#### basic test coverage for  [backbone.radio (v2.0.0)](https://github.com/marionettejs/backbone.radio)  [![npm package](https://img.shields.io/npm/v/npmtest-backbone.radio.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-backbone.radio) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-backbone.radio.svg)](https://travis-ci.org/npmtest/node-npmtest-backbone.radio)

#### Messaging patterns for Backbone applications.

[![NPM](https://nodei.co/npm/backbone.radio.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/backbone.radio)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-backbone.radio/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone.radio/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-backbone.radio/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-backbone.radio/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-backbone.radio/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-backbone.radio/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-backbone.radio/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-backbone.radio/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-backbone.radio/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-backbone.radio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-backbone.radio/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-backbone.radio/build/test-report.html](https://npmtest.github.io/node-npmtest-backbone.radio/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-backbone.radio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-backbone.radio/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-backbone.radio/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-backbone.radio/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-backbone.radio/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-backbone.radio/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-backbone.radio/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-backbone.radio/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "backbone.radio",
    "description": "Messaging patterns for Backbone applications.",
    "homepage": "https://github.com/marionettejs/backbone.radio",
    "version": "2.0.0",
    "main": "build/backbone.radio.js",
    "keywords": [
        "backbone",
        "marionette",
        "decoupled",
        "pubsub",
        "publish",
        "subscribe",
        "messaging",
        "architecture",
        "spa"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/marionettejs/backbone.radio/blob/master/LICENSE"
        }
    ],
    "scripts": {
        "test": "gulp",
        "test-browser": "gulp test-browser",
        "build": "gulp build",
        "coverage": "gulp coverage"
    },
    "author": {
        "name": "Jmeas",
        "web": "http://jmeas.com"
    },
    "bugs": {
        "url": "https://github.com/marionettejs/backbone.radio/issues"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/marionettejs/backbone.radio.git"
    },
    "github": "https://github.com/marionettejs/backbone.radio",
    "peerDependencies": {
        "backbone": "^1.3.3",
        "underscore": "^1.8.3"
    },
    "devDependencies": {
        "babel-core": "6.7.0",
        "babel-eslint": "6.0.4",
        "babel-loader": "6.2.0",
        "babel-polyfill": "6.6.1",
        "babel-preset-es2015": "6.3.13",
        "babel-preset-es2015-rollup": "1.1.1",
        "babel-register": "6.4.3",
        "backbone": ">=1.3.3 <1.4.0",
        "chai": "3.4.1",
        "del": "2.2.0",
        "eslint": "3.2.2",
        "glob": "6.0.3",
        "gulp": "3.9.0",
        "gulp-eslint": "3.0.1",
        "gulp-file": "0.2.0",
        "gulp-filter": "3.0.0",
        "gulp-header": "1.7.1",
        "gulp-istanbul": "0.10.3",
        "gulp-jscs": "3.0.0",
        "gulp-livereload": "3.8.1",
        "gulp-load-plugins": "1.1.0",
        "gulp-mocha": "2.2.0",
        "gulp-plumber": "1.0.1",
        "gulp-rename": "1.2.2",
        "gulp-sourcemaps": "1.6.0",
        "gulp-uglify": "1.5.1",
        "gulp-util": "3.0.7",
        "isparta": "4.0.0",
        "json-loader": "0.5.3",
        "mkdirp": "0.5.1",
        "mocha": "2.3.4",
        "rollup": "0.25.4",
        "rollup-plugin-babel": "2.4.0",
        "sinon": "1.17.2",
        "sinon-chai": "2.8.0",
        "underscore": "1.8.3",
        "webpack": "1.12.9",
        "webpack-stream": "3.1.0"
    },
    "babelBoilerplateOptions": {
        "entryFileName": "backbone.radio",
        "mainVarName": "Backbone.Radio"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
