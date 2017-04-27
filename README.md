# npmtest-request-ip

#### basic test coverage for  [request-ip (v2.0.1)](https://github.com/pbojinov/request-ip)  [![npm package](https://img.shields.io/npm/v/npmtest-request-ip.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-request-ip) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-request-ip.svg)](https://travis-ci.org/npmtest/node-npmtest-request-ip)

#### A small node.js module to retrieve the request's IP address

[![NPM](https://nodei.co/npm/request-ip.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/request-ip)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-request-ip/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-ip/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-request-ip/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-request-ip/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-request-ip/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-request-ip/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-request-ip/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-request-ip/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-request-ip/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-request-ip/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-request-ip/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-request-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-request-ip/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-request-ip/build/test-report.html](https://npmtest.github.io/node-npmtest-request-ip/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-request-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-request-ip/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-request-ip/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-request-ip/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-request-ip/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-request-ip/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-request-ip/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-request-ip/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Petar Bojinov"
    },
    "bugs": {
        "url": "https://github.com/pbojinov/request-ip/issues"
    },
    "contributors": [
        {
            "name": "Jon Peck"
        }
    ],
    "dependencies": {
        "is_js": "^0.9.0"
    },
    "description": "A small node.js module to retrieve the request's IP address",
    "devDependencies": {
        "coveralls": "^2.11.2",
        "eslint": "^3.17.0",
        "eslint-config-airbnb-base": "^11.1.1",
        "eslint-plugin-import": "^2.2.0",
        "nyc": "^10.1.2",
        "request": "^2.54.0",
        "tap-spec": "^4.1.1",
        "tape": "^4.6.3"
    },
    "directories": {},
    "dist": {
        "shasum": "10fbf971ba73e1dd6baf2c325275b6d3d4c10a71",
        "tarball": "https://registry.npmjs.org/request-ip/-/request-ip-2.0.1.tgz"
    },
    "engines": {
        "node": "<6"
    },
    "gitHead": "73cd1ce85a6f4c50f56108a636ba50cac6d02876",
    "homepage": "https://github.com/pbojinov/request-ip",
    "keywords": [
        "request ip",
        "ip",
        "address",
        "request",
        "proxy",
        "client",
        "header",
        "X-Real-IP",
        "X-Client-IP",
        "X-Forwarded-For",
        "connection.remoteAddress",
        "middleware",
        "ipv4",
        "ipv6"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "pbojinov"
        }
    ],
    "name": "request-ip",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/pbojinov/request-ip.git"
    },
    "scripts": {
        "changelog": "github_changelog_generator -t 4c910e93a260e924d44e800b1a4345bf1115c532",
        "coverage": "nyc report --reporter=text-lcov | coveralls",
        "test": "nyc --reporter=html --reporter=text --check-coverage --lines=100 --statements=100 tape ./test/*.js"
    },
    "version": "2.0.1",
    "warnings": [
        {
            "code": "ENOTSUP",
            "required": {
                "node": "<6"
            },
            "pkgid": "request-ip@2.0.1"
        },
        {
            "code": "ENOTSUP",
            "required": {
                "node": "<6"
            },
            "pkgid": "request-ip@2.0.1"
        }
    ],
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
