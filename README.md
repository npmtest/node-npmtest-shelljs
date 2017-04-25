# npmtest-shelljs

#### basic test coverage for  [shelljs (v0.7.7)](http://github.com/shelljs/shelljs)  [![npm package](https://img.shields.io/npm/v/npmtest-shelljs.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-shelljs) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-shelljs.svg)](https://travis-ci.org/npmtest/node-npmtest-shelljs)

#### Portable Unix shell commands for Node.js

[![NPM](https://nodei.co/npm/shelljs.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/shelljs)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-shelljs/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-shelljs/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-shelljs/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-shelljs/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-shelljs/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-shelljs/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-shelljs/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-shelljs/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-shelljs/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-shelljs/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-shelljs/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-shelljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-shelljs/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-shelljs/build/test-report.html](https://npmtest.github.io/node-npmtest-shelljs/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-shelljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-shelljs/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-shelljs/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-shelljs/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-shelljs/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-shelljs/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-shelljs/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-shelljs/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bin": {
        "shjs": "./bin/shjs"
    },
    "bugs": {
        "url": "https://github.com/shelljs/shelljs/issues"
    },
    "contributors": [
        {
            "name": "Nate Fischer",
            "url": "https://github.com/nfischer"
        },
        {
            "name": "Brandon Freitag",
            "url": "https://github.com/freitagbr"
        }
    ],
    "dependencies": {
        "glob": "^7.0.0",
        "interpret": "^1.0.0",
        "rechoir": "^0.6.2"
    },
    "description": "Portable Unix shell commands for Node.js",
    "devDependencies": {
        "ava": "^0.16.0",
        "codecov": "^1.0.1",
        "coffee-script": "^1.10.0",
        "eslint": "^2.0.0",
        "eslint-config-airbnb-base": "^3.0.0",
        "eslint-plugin-import": "^1.11.1",
        "nyc": "^10.0.0",
        "shelljs-changelog": "^0.2.0",
        "shelljs-release": "^0.2.0",
        "shx": "^0.2.0",
        "travis-check-changes": "^0.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "b2f5c77ef97148f4b4f6e22682e10bba8667cff1",
        "tarball": "https://registry.npmjs.org/shelljs/-/shelljs-0.7.7.tgz"
    },
    "engines": {
        "iojs": "*",
        "node": ">=0.11.0"
    },
    "files": [
        "commands.js",
        "global.js",
        "make.js",
        "plugin.js",
        "shell.js",
        "bin",
        "src"
    ],
    "gitHead": "95638cc773390920a446e383c40ed8104c7d211d",
    "homepage": "http://github.com/shelljs/shelljs",
    "keywords": [
        "shelljs",
        "bash",
        "unix",
        "shell",
        "makefile",
        "make",
        "jake",
        "synchronous"
    ],
    "license": "BSD-3-Clause",
    "main": "./shell.js",
    "maintainers": [
        {
            "name": "artur"
        },
        {
            "name": "freitagbr"
        },
        {
            "name": "nfischer"
        }
    ],
    "name": "shelljs",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git://github.com/shelljs/shelljs.git"
    },
    "scripts": {
        "after-travis": "travis-check-changes",
        "changelog": "shelljs-changelog",
        "codecov": "codecov",
        "gendocs": "node scripts/generate-docs",
        "lint": "eslint .",
        "posttest": "npm run lint",
        "release:major": "shelljs-release major",
        "release:minor": "shelljs-release minor",
        "release:patch": "shelljs-release patch",
        "test": "nyc --reporter=text --reporter=lcov ava --serial test/*.js",
        "test-no-coverage": "ava --serial test/*.js"
    },
    "version": "0.7.7"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
