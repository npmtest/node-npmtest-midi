# npmtest-midi

#### basic test coverage for  midi (v0.9.5)  [![npm package](https://img.shields.io/npm/v/npmtest-midi.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-midi) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-midi.svg)](https://travis-ci.org/npmtest/node-npmtest-midi)

#### MIDI hardware IO

[![NPM](https://nodei.co/npm/midi.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/midi)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-midi/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-midi/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-midi/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-midi/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-midi/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-midi/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-midi/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-midi/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-midi/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-midi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-midi/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-midi/build/test-report.html](https://npmtest.github.io/node-npmtest-midi/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-midi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-midi/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-midi/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-midi/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-midi/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-midi/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "midi",
    "version": "0.9.5",
    "scripts": {
        "test": "mocha test/unit-tests.js && node test/virtual-loopback-test-automated.js"
    },
    "main": "midi.js",
    "description": "MIDI hardware IO",
    "author": {
        "name": "Justin Latimer",
        "url": "http://www.justinlatimer.com/"
    },
    "contributors": [
        {
            "name": "Elijah Insua"
        },
        {
            "name": "Andrew Morton"
        },
        {
            "name": "Luc Deschenaux"
        },
        {
            "name": "Michael Alyn Miller"
        },
        {
            "name": "Hugo Hromic"
        }
    ],
    "engines": {
        "node": ">=0.8.0"
    },
    "dependencies": {
        "bindings": "~1.2.1",
        "nan": "^2.3.3"
    },
    "devDependencies": {
        "mocha": ">= 2.1.0",
        "should": ">= 5.0.1"
    },
    "repository": {
        "type": "git",
        "url": "https://github.com/justinlatimer/node-midi.git"
    },
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
