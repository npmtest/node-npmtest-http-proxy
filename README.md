# npmtest-http-proxy

#### basic test coverage for  [http-proxy (v1.16.2)](https://github.com/nodejitsu/node-http-proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-http-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-http-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-http-proxy.svg)](https://travis-ci.org/npmtest/node-npmtest-http-proxy)

#### HTTP proxying for the masses

[![NPM](https://nodei.co/npm/http-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/http-proxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-http-proxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-proxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-http-proxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-http-proxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-http-proxy/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-http-proxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-http-proxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-http-proxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-http-proxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-http-proxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-http-proxy/build/test-report.html](https://npmtest.github.io/node-npmtest-http-proxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-http-proxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-http-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-http-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-http-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-http-proxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-http-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-http-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Charlie Robbins"
    },
    "bugs": {
        "url": "https://github.com/nodejitsu/node-http-proxy/issues"
    },
    "dependencies": {
        "eventemitter3": "1.x.x",
        "requires-port": "1.x.x"
    },
    "description": "HTTP proxying for the masses",
    "devDependencies": {
        "async": "*",
        "blanket": "*",
        "coveralls": "*",
        "dox": "*",
        "expect.js": "*",
        "mocha": "*",
        "mocha-lcov-reporter": "*",
        "semver": "^5.0.3",
        "socket.io": "*",
        "socket.io-client": "*",
        "sse": "0.0.6",
        "ws": "^0.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "06dff292952bf64dbe8471fa9df73066d4f37742",
        "tarball": "https://registry.npmjs.org/http-proxy/-/http-proxy-1.16.2.tgz"
    },
    "engines": {
        "node": ">=0.10.0"
    },
    "gitHead": "c1fb596b856df971d291585ccf105233f7deca51",
    "homepage": "https://github.com/nodejitsu/node-http-proxy#readme",
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "indexzero"
        },
        {
            "name": "cronopio"
        },
        {
            "name": "yawnt"
        },
        {
            "name": "jcrugzz"
        }
    ],
    "name": "http-proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/nodejitsu/node-http-proxy.git"
    },
    "scripts": {
        "coveralls": "mocha --require blanket --reporter mocha-lcov-reporter | ./node_modules/coveralls/bin/coveralls.js",
        "test": "mocha test/*-test.js",
        "test-cov": "mocha --require blanket -R html-cov > cov/coverage.html"
    },
    "version": "1.16.2"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
