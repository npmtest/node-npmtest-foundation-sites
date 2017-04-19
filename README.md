# npmtest-foundation-sites

#### test coverage for  [foundation-sites (v6.3.1)](http://foundation.zurb.com/sites)  [![npm package](https://img.shields.io/npm/v/npmtest-foundation-sites.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-foundation-sites) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-foundation-sites.svg)](https://travis-ci.org/npmtest/node-npmtest-foundation-sites)

#### The most advanced responsive front-end framework in the world.

[![NPM](https://nodei.co/npm/foundation-sites.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/foundation-sites)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-foundation-sites/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-foundation-sites/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-foundation-sites/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-foundation-sites/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-foundation-sites/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-foundation-sites/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-foundation-sites/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-foundation-sites/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-foundation-sites/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-foundation-sites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-foundation-sites/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-foundation-sites/build/test-report.html](https://npmtest.github.io/node-npmtest-foundation-sites/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-foundation-sites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-foundation-sites/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-foundation-sites/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-foundation-sites/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-foundation-sites/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-foundation-sites/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-foundation-sites/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-foundation-sites/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "ZURB",
        "url": "http://foundation.zurb.com"
    },
    "browserify": {
        "transform": [
            [
                "babelify",
                {
                    "presets": [
                        "es2015"
                    ]
                }
            ]
        ]
    },
    "bugs": {
        "url": "https://github.com/zurb/foundation-sites/issues"
    },
    "dependencies": {
        "jquery": ">=2.2.0",
        "what-input": "^4.0.3"
    },
    "description": "The most advanced responsive front-end framework in the world.",
    "devDependencies": {
        "array-uniq": "^1.0.2",
        "autoprefixer": "^6.5.3",
        "babel-core": "^6.3.26",
        "babel-plugin-transform-es2015-arrow-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoped-functions": "^6.3.13",
        "babel-plugin-transform-es2015-block-scoping": "^6.4.0",
        "babel-plugin-transform-es2015-classes": "^6.3.15",
        "babel-plugin-transform-es2015-destructuring": "^6.3.15",
        "babel-plugin-transform-es2015-parameters": "^6.3.26",
        "babel-plugin-transform-es2015-shorthand-properties": "^6.5.0",
        "babel-plugin-transform-es2015-spread": "^6.4.0",
        "babel-plugin-transform-es2015-template-literals": "^6.3.13",
        "browser-sync": "^2.8.2",
        "chai-jquery": "^2.0.0",
        "chalk": "^1.1.1",
        "clipboard": "^1.5.5",
        "corejs-typeahead": "^1.0.1",
        "doiuse": "^2.5.0",
        "foundation-docs": "github:zurb/foundation-docs",
        "gulp": "^3.8.10",
        "gulp-add-src": "^0.2.0",
        "gulp-babel": "^6.1.1",
        "gulp-cache-bust": "~1.0.2",
        "gulp-check-deps": "^1.4.1",
        "gulp-concat": "^2.4.3",
        "gulp-cssnano": "^2.1.0",
        "gulp-eslint": "^3.0.1",
        "gulp-filter": "^4.0.0",
        "gulp-if": "^2.0.0",
        "gulp-load-plugins": "^1.2.0",
        "gulp-newer": "^1.1.0",
        "gulp-plumber": "^1.0.1",
        "gulp-postcss": "^6.2.0",
        "gulp-prompt": "^0.2.0",
        "gulp-rename": "^1.2.2",
        "gulp-replace": "^0.5.4",
        "gulp-rsync": "^0.0.7",
        "gulp-ruby-sass": "^2.0.6",
        "gulp-sass": "^2.1.0",
        "gulp-sass-lint": "^1.3.2",
        "gulp-sourcemaps": "^2.2.1",
        "gulp-uglify": "^2.0.0",
        "gulp-zip": "^3.2.0",
        "inquirer": "^2.0.0",
        "is-empty-object": "^1.1.1",
        "js-yaml": "^3.5.4",
        "mocha": "^3.2.0",
        "mocha-phantomjs": "^4.0.2",
        "motion-ui": "^1.1.0",
        "multiline": "^1.0.2",
        "normalize-scss": "6.0.0",
        "octophant": "^1.0.0",
        "opener": "^1.4.1",
        "panini": "^1.3.0",
        "parker": "^1.0.0-alpha.0",
        "prettyjson": "^1.1.3",
        "require-dir": "^0.3.0",
        "rimraf": "^2.3.2",
        "run-sequence": "^1.1.4",
        "sass-true": "^2.0.3",
        "sassy-lists": "3.0.0",
        "sinon": "^1.17.3",
        "supercollider": "^1.4.0",
        "touch": "^1.0.0",
        "vinyl": "^2.0.1",
        "vinyl-source-stream": "^1.1.0",
        "yargs": "^6.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "23853372deb9480c13b426499eaf0c8f90cdbe1d",
        "tarball": "https://registry.npmjs.org/foundation-sites/-/foundation-sites-6.3.1.tgz"
    },
    "engines": {
        "node": ">=4.0",
        "npm": ">=2.14.2"
    },
    "eyeglass": {
        "name": "foundation",
        "sassDir": "scss",
        "needs": "^0.8.0",
        "exports": false
    },
    "gitHead": "9bdf0817e70fec15b1df643d6651ecdd5fe0ad02",
    "homepage": "http://foundation.zurb.com/sites",
    "jspm": {
        "format": "global",
        "shim": {
            "dist/js/foundation": {
                "deps": [
                    "jquery"
                ]
            }
        }
    },
    "keywords": [
        "eyeglass-module",
        "handlebars-helper-rel",
        "handlebars-helper-slugify"
    ],
    "license": "MIT",
    "main": "dist/js/foundation.js",
    "maintainers": [
        {
            "name": "arthurzurb"
        },
        {
            "name": "eddiedean"
        },
        {
            "name": "gakimball"
        },
        {
            "name": "kbal11"
        },
        {
            "name": "rafibomb"
        }
    ],
    "name": "foundation-sites",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/zurb/foundation-sites.git"
    },
    "scripts": {
        "deploy": "gulp deploy",
        "deploy:docs": "gulp deploy:docs",
        "deploy:prep": "gulp deploy:prep",
        "start": "gulp",
        "test": "npm run test:sass && npm run test:javascript",
        "test:javascript": "gulp sass:foundation && gulp test:transpile-js && mocha-phantomjs --ignore-resource-errors test/javascript/index.html",
        "test:sass": "mocha test/sass/test_sass.js",
        "test:visual": "gulp test"
    },
    "typings": "dist/js/foundation.d.ts",
    "version": "6.3.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
