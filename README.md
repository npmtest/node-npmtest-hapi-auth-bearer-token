# npmtest-hapi-auth-bearer-token

#### basic test coverage for  [hapi-auth-bearer-token (v5.0.0)](https://github.com/johnbrett/hapi-auth-bearer-token)  [![npm package](https://img.shields.io/npm/v/npmtest-hapi-auth-bearer-token.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-hapi-auth-bearer-token) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-hapi-auth-bearer-token.svg)](https://travis-ci.org/npmtest/node-npmtest-hapi-auth-bearer-token)

#### Simple Bearer authentication scheme plugin for hapi, accepts token by Header, Cookie or Query parameter.

[![NPM](https://nodei.co/npm/hapi-auth-bearer-token.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/hapi-auth-bearer-token)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-hapi-auth-bearer-token/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-hapi-auth-bearer-token/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/test-report.html](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-hapi-auth-bearer-token/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-hapi-auth-bearer-token/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-hapi-auth-bearer-token/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-hapi-auth-bearer-token/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-hapi-auth-bearer-token/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "John Brett",
        "url": "https://johnbrett.me"
    },
    "bugs": {
        "url": "https://github.com/johnbrett/hapi-auth-bearer-token/issues"
    },
    "dependencies": {
        "boom": "^4.1.0",
        "hoek": "^4.1.0",
        "joi": "^10.0.0"
    },
    "description": "Simple Bearer authentication scheme plugin for hapi, accepts token by Header, Cookie or Query parameter.",
    "devDependencies": {
        "code": "^4.0.0",
        "hapi": "^16.0.0",
        "lab": "^11.0.0"
    },
    "directories": {
        "test": "test"
    },
    "dist": {
        "shasum": "0129888ed53d06ef1fe7bc7bbb43eabcc9977d51",
        "tarball": "https://registry.npmjs.org/hapi-auth-bearer-token/-/hapi-auth-bearer-token-5.0.0.tgz"
    },
    "engines": {
        "node": ">=4.0.0"
    },
    "gitHead": "15d5932cc3988b0663f10fe5921920c61a48e932",
    "homepage": "https://github.com/johnbrett/hapi-auth-bearer-token",
    "keywords": [
        "hapi",
        "plugin",
        "auth",
        "scheme",
        "bearer",
        "token",
        "cookie",
        "authentication"
    ],
    "license": "MIT",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "johnbrett"
        }
    ],
    "name": "hapi-auth-bearer-token",
    "optionalDependencies": {},
    "peerDependencies": {
        "hapi": ">=8.x.x"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/johnbrett/hapi-auth-bearer-token.git"
    },
    "scripts": {
        "test": "lab -a code -t 100 -L",
        "test-cov-html": "lab -a code -r html -o coverage.html"
    },
    "version": "5.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
