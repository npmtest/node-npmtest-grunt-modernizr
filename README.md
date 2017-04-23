# npmtest-grunt-modernizr

#### basic test coverage for  [grunt-modernizr (v1.0.2)](https://github.com/Modernizr/grunt-modernizr)  [![npm package](https://img.shields.io/npm/v/npmtest-grunt-modernizr.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-grunt-modernizr) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-grunt-modernizr.svg)](https://travis-ci.org/npmtest/node-npmtest-grunt-modernizr)

#### Build out a lean, mean Modernizr machine.

[![NPM](https://nodei.co/npm/grunt-modernizr.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/grunt-modernizr)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-grunt-modernizr/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-grunt-modernizr/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-grunt-modernizr/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-grunt-modernizr/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-grunt-modernizr/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-grunt-modernizr/build/test-report.html](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-grunt-modernizr/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-grunt-modernizr/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-grunt-modernizr/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-grunt-modernizr/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-grunt-modernizr/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Richard Herrera",
        "url": "http://doctyper.com"
    },
    "bin": {
        "grunt-modernizr": "bin/grunt-modernizr"
    },
    "bugs": {
        "url": "https://github.com/Modernizr/grunt-modernizr/issues"
    },
    "dependencies": {
        "customizr": "https://github.com/doctyper/customizr/tarball/develop",
        "lodash.merge": "^4.0.1"
    },
    "description": "Build out a lean, mean Modernizr machine.",
    "devDependencies": {
        "assert": "~1.1.0",
        "grunt": "~0.4.2",
        "grunt-contrib-clean": "~0.5.0",
        "grunt-contrib-jshint": "~0.7.0",
        "grunt-contrib-nodeunit": "0.4.1",
        "grunt-contrib-watch": "~0.3.1",
        "mocha": "~1.17.0",
        "modernizr": "https://github.com/Modernizr/Modernizr/tarball/master",
        "nexpect": "~0.3.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "1a3a9a021dede12122d24b000142adcd9dfc9847",
        "tarball": "https://registry.npmjs.org/grunt-modernizr/-/grunt-modernizr-1.0.2.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "e9da3d1f18d0444a141ee29c2422cd1167127e64",
    "homepage": "https://github.com/Modernizr/grunt-modernizr",
    "keywords": [
        "gruntplugin",
        "modernizr",
        "customizr"
    ],
    "licenses": [
        {
            "type": "MIT",
            "url": "https://github.com/doctyper/grunt-modernizr/blob/master/LICENSE-MIT"
        }
    ],
    "main": "Gruntfile.js",
    "maintainers": [
        {
            "name": "doctyper"
        },
        {
            "name": "patrickkettner"
        }
    ],
    "name": "grunt-modernizr",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/Modernizr/grunt-modernizr.git"
    },
    "scripts": {
        "postinstall": "node postinstall.js",
        "test": "grunt clean; node test/runner.js"
    },
    "version": "1.0.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
