# npmtest-speakingurl

#### basic test coverage for  [speakingurl (v13.0.0)](http://pid.github.io/speakingurl/)  [![npm package](https://img.shields.io/npm/v/npmtest-speakingurl.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-speakingurl) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-speakingurl.svg)](https://travis-ci.org/npmtest/node-npmtest-speakingurl)

#### Generate a slug – transliteration with a lot of options

[![NPM](https://nodei.co/npm/speakingurl.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/speakingurl)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-speakingurl/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-speakingurl/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-speakingurl/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-speakingurl/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-speakingurl/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-speakingurl/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-speakingurl/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-speakingurl/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-speakingurl/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-speakingurl/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-speakingurl/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-speakingurl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-speakingurl/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-speakingurl/build/test-report.html](https://npmtest.github.io/node-npmtest-speakingurl/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-speakingurl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-speakingurl/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-speakingurl/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-speakingurl/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-speakingurl/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-speakingurl/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-speakingurl/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-speakingurl/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Sascha Droste",
        "url": "https://twitter.com/SaschaDroste"
    },
    "bugs": {
        "url": "https://github.com/pid/speakingurl/issues"
    },
    "categories": [
        "Utilities",
        "Parsers & Compilers"
    ],
    "dependencies": {},
    "description": "Generate a slug – transliteration with a lot of options",
    "devDependencies": {
        "gulp": "^3.8.8",
        "gulp-bump": "^2.4.0",
        "gulp-header": "^1.2.2",
        "gulp-jsbeautifier": "^2.0.3",
        "gulp-jshint": "^2.0.0",
        "gulp-load-plugins": "^1.1.0",
        "gulp-mocha": "^3.0.1",
        "gulp-rename": "^1.2.0",
        "gulp-replace": "^0.5.0",
        "gulp-uglify": "^2.0.0",
        "jshint": "^2.8.0",
        "jshint-stylish": "^2.0.0",
        "minimist": "^1.1.0",
        "mocha": "^3.0.2",
        "should": "^11.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "266c52d2b47585375af058e4783c8d1097a2d3db",
        "tarball": "https://registry.npmjs.org/speakingurl/-/speakingurl-13.0.0.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "filename": "speakingurl.min.js",
    "gitHead": "31c5b7ce85a69a7721acd090f73235c97890a4a9",
    "github": "http://github.com/pid/speakingurl",
    "homepage": "http://pid.github.io/speakingurl/",
    "jam": {
        "dependencies": {},
        "main": "speakingurl.min.js",
        "shim": {
            "deps": [],
            "exports": [
                "getSlug",
                "createSlug"
            ]
        },
        "include": [
            "speakingurl.min.js",
            "README.md"
        ]
    },
    "keywords": [
        "slug",
        "slugify",
        "speakingurl",
        "transliteration",
        "permalink",
        "seo",
        "url",
        "nice url",
        "static url",
        "clean url",
        "pretty url",
        "nice looking url",
        "user friendly url",
        "seo friendly url"
    ],
    "license": "BSD-3-Clause",
    "licenses": [
        {
            "type": "BSD",
            "url": "https://raw.github.com/pid/speakingurl/master/LICENSE"
        }
    ],
    "main": "index",
    "maintainers": [
        {
            "name": "pid"
        }
    ],
    "name": "speakingurl",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/%3Apid/speakingurl.git"
    },
    "scripts": {
        "test": "mocha"
    },
    "version": "13.0.0",
    "volo": {
        "url": "//cdnjs.cloudflare.com/ajax/libs/speakingurl/{version}/speakingurl.min.js"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
