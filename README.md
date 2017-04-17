# test coverage for  [cli-color (v1.2.0)](https://github.com/medikoo/cli-color#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-cli-color.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-cli-color) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-cli-color.svg)](https://travis-ci.org/npmtest/node-npmtest-cli-color)
#### Colors, formatting and other tools for the console

[![NPM](https://nodei.co/npm/cli-color.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/cli-color)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-cli-color/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-cli-color/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-cli-color/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-cli-color/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-cli-color/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-cli-color/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-cli-color/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-cli-color/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-cli-color/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-cli-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-cli-color/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-cli-color/build/test-report.html](https://npmtest.github.io/node-npmtest-cli-color/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-cli-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-cli-color/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-cli-color/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-cli-color/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-cli-color/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-cli-color/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-cli-color/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-cli-color/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Mariusz Nowak",
        "url": "http://www.medikoo.com/"
    },
    "bugs": {
        "url": "https://github.com/medikoo/cli-color/issues"
    },
    "dependencies": {
        "ansi-regex": "^2.1.1",
        "d": "1",
        "es5-ext": "^0.10.12",
        "es6-iterator": "2",
        "memoizee": "^0.4.3",
        "timers-ext": "0.1"
    },
    "description": "Colors, formatting and other tools for the console",
    "devDependencies": {
        "tad": "^0.2.7",
        "xlint": "^0.2.2",
        "xlint-jslint-medikoo": "^0.1.4"
    },
    "directories": {},
    "dist": {
        "shasum": "3a5ae74fd76b6267af666e69e2afbbd01def34d1",
        "tarball": "https://registry.npmjs.org/cli-color/-/cli-color-1.2.0.tgz"
    },
    "gitHead": "7aae8aa90f59140d243fdd6d02253880d5281ad9",
    "homepage": "https://github.com/medikoo/cli-color#readme",
    "keywords": [
        "ansi",
        "color",
        "console",
        "terminal",
        "cli",
        "shell",
        "log",
        "logging",
        "xterm"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "medikoo"
        }
    ],
    "name": "cli-color",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/medikoo/cli-color.git"
    },
    "scripts": {
        "lint": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --no-cache --no-stream",
        "lint-console": "node node_modules/xlint/bin/xlint --linter=node_modules/xlint-jslint-medikoo/index.js --watch",
        "test": "node ./node_modules/tad/bin/tad"
    },
    "version": "1.2.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
