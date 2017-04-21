# npmtest-superagent-as-promised

#### basic test coverage for  superagent-as-promised (v4.0.0)  [![npm package](https://img.shields.io/npm/v/npmtest-superagent-as-promised.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-superagent-as-promised) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-superagent-as-promised.svg)](https://travis-ci.org/npmtest/node-npmtest-superagent-as-promised)

#### SuperAgent with a Promise twist

[![NPM](https://nodei.co/npm/superagent-as-promised.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/superagent-as-promised)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-superagent-as-promised/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-superagent-as-promised/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-superagent-as-promised/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-superagent-as-promised/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-superagent-as-promised/build/test-report.html](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-superagent-as-promised/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-superagent-as-promised/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-superagent-as-promised/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-superagent-as-promised/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-superagent-as-promised/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "superagent-as-promised",
    "version": "4.0.0",
    "description": "SuperAgent with a Promise twist",
    "main": "index.js",
    "scripts": {
        "prepublish": "coffee -c index.coffee.md",
        "pretest": "npm install",
        "test": "mocha"
    },
    "keywords": [
        "superagent",
        "promise"
    ],
    "author": "Stéphane Alnet <stephane@shimaore.net> (http://stephane.shimaore.net/)",
    "license": "MIT",
    "devDependencies": {
        "bluebird": "^3.0.5",
        "chai": "^3.4.1",
        "chai-as-promised": "^5.1.0",
        "coffee-script": "^1.10.0",
        "express": "^4.13.3",
        "mocha": "^2.3.3",
        "superagent": "^1.4.0"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
