# npmtest-ember-buffered-proxy

#### basic test coverage for  [ember-buffered-proxy (v0.7.0)](https://github.com/yapplabs/ember-buffered-proxy#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-ember-buffered-proxy.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ember-buffered-proxy) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ember-buffered-proxy.svg)](https://travis-ci.org/npmtest/node-npmtest-ember-buffered-proxy)

#### An Ember Object Proxy with change buffering

[![NPM](https://nodei.co/npm/ember-buffered-proxy.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ember-buffered-proxy)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ember-buffered-proxy/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ember-buffered-proxy/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/test-report.html](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ember-buffered-proxy/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ember-buffered-proxy/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ember-buffered-proxy/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ember-buffered-proxy/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ember-buffered-proxy/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Kris Selden, Stefan Penner & Yapp Labs"
    },
    "bugs": {
        "url": "https://github.com/yapplabs/ember-buffered-proxy/issues"
    },
    "contributors": [
        {
            "name": "Ben Limmer"
        }
    ],
    "dependencies": {
        "ember-cli-babel": "^5.1.7"
    },
    "description": "An Ember Object Proxy with change buffering",
    "devDependencies": {
        "ember-cli": "^2.12.1",
        "ember-cli-dependency-checker": "^1.3.0",
        "ember-cli-eslint": "^3.0.0",
        "ember-cli-htmlbars": "^1.1.1",
        "ember-cli-htmlbars-inline-precompile": "^0.3.6",
        "ember-cli-inject-live-reload": "^1.4.1",
        "ember-cli-qunit": "^3.1.0",
        "ember-cli-release": "^1.0.0-beta.2",
        "ember-cli-shims": "^1.0.2",
        "ember-disable-prototype-extensions": "^1.1.0",
        "ember-export-application-global": "^1.0.5",
        "ember-load-initializers": "^0.6.0",
        "ember-resolver": "^2.0.3",
        "ember-source": "~2.12.0",
        "loader.js": "^4.2.3"
    },
    "directories": {
        "doc": "doc",
        "test": "tests"
    },
    "dist": {
        "shasum": "966c1cab8906247b0d9c358465cca7d83badbf71",
        "tarball": "https://registry.npmjs.org/ember-buffered-proxy/-/ember-buffered-proxy-0.7.0.tgz"
    },
    "ember-addon": {
        "versionCompatibility": {
            "ember": ">=1.13"
        },
        "configPath": "tests/dummy/config"
    },
    "engines": {
        "node": ">= 4"
    },
    "gitHead": "e02d804a2001d1a32960bd7f8edbd160f8025436",
    "homepage": "https://github.com/yapplabs/ember-buffered-proxy#readme",
    "keywords": [
        "ember-addon"
    ],
    "license": "MIT",
    "maintainers": [
        {
            "name": "blimmer"
        },
        {
            "name": "denisnazarov"
        },
        {
            "name": "krisselden"
        },
        {
            "name": "lukemelia"
        },
        {
            "name": "raycohen"
        },
        {
            "name": "stefanpenner"
        }
    ],
    "name": "ember-buffered-proxy",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yapplabs/ember-buffered-proxy.git"
    },
    "scripts": {
        "build": "ember build",
        "start": "ember server",
        "test": "ember try:each"
    },
    "version": "0.7.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
