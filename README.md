# test coverage for  [gulp-iconfont (v8.0.1)](https://github.com/nfroidure/gulp-iconfont)  [![npm package](https://img.shields.io/npm/v/npmtest-gulp-iconfont.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-gulp-iconfont) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-gulp-iconfont.svg)](https://travis-ci.org/npmtest/node-npmtest-gulp-iconfont)
#### Create icon fonts from several SVG icons

[![NPM](https://nodei.co/npm/gulp-iconfont.png?downloads=true)](https://www.npmjs.com/package/gulp-iconfont)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-gulp-iconfont/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-gulp-iconfont/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-gulp-iconfont/tree/gh-pages/build)|

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/screenCapture.buildCustomOrg.browser.coverage.html.png)](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/coverage.html/index.html)

[![test-report](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/screenCapture.buildCustomOrg.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmtest%252Fnode-npmtest-gulp-iconfont%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/test-report.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/screenCapture.buildApidoc.browser.%252Fhome%252Ftravis%252Fbuild%252Fnpmdoc%252Fnode-npmdoc-gulp-iconfont%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-gulp-iconfont/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-gulp-iconfont/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Nicolas Froidure",
        "url": "http://www.insertafter.com/blog.html"
    },
    "bugs": {
        "url": "https://github.com/nfroidure/gulp-iconfont/issues"
    },
    "dependencies": {
        "gulp-cond": "^1.0.0",
        "gulp-spawn": "^0.3.0",
        "gulp-svg2ttf": "^2.0.0",
        "gulp-svgicons2svgfont": "^3.0.1",
        "gulp-ttf2eot": "^1.1.1",
        "gulp-ttf2woff": "^1.1.0",
        "gulp-ttf2woff2": "^2.0.2",
        "gulp-util": "^3.0.7",
        "plexer": "^1.0.1",
        "streamfilter": "^1.0.5"
    },
    "description": "Create icon fonts from several SVG icons",
    "devDependencies": {
        "coveralls": "^2.11.6",
        "eslint": "^1.10.1",
        "eslint-config-simplifield": "^1.2.2",
        "gulp": "^3.9.1",
        "istanbul": "^0.4.2",
        "mocha": "^2.4.5",
        "mocha-lcov-reporter": "^1.0.0",
        "neatequal": "^1.0.0",
        "streamtest": "^1.2.1"
    },
    "directories": {},
    "dist": {
        "shasum": "bc32aa6e3ea5ca389fbb014ba8d2c08f0c3c0763",
        "tarball": "https://registry.npmjs.org/gulp-iconfont/-/gulp-iconfont-8.0.1.tgz"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "e7d32eb141f6106a04d03a21ddfc66259983f8f0",
    "homepage": "https://github.com/nfroidure/gulp-iconfont",
    "keywords": [
        "gulpplugin",
        "gulp",
        "icon",
        "font"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "nfroidure",
            "email": "nfroidure@elitwork.com"
        }
    ],
    "name": "gulp-iconfont",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git://github.com/nfroidure/gulp-iconfont.git"
    },
    "scripts": {
        "cli": "env NPM_RUN_CLI=1",
        "cover": "istanbul cover --report html _mocha -- tests/*.mocha.js -R spec -t 5000",
        "coveralls": "istanbul cover _mocha --report lcovonly -- tests/*.mocha.js -R spec -t 5000 && cat ./coverage/lcov.info | coveralls && rm -rf ./coverage",
        "generate-fixtures": "./tests/generate-fixtures.sh",
        "lint": "eslint src/*.js tests/*.js",
        "preversion": "npm run lint && npm test",
        "test": "mocha tests/*.mocha.js"
    },
    "version": "8.0.1"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
