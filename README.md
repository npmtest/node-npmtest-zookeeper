# npmtest-zookeeper

#### basic test coverage for  [zookeeper (v3.4.9-3)](https://github.com/yfinkelstein/node-zookeeper#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-zookeeper.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-zookeeper) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-zookeeper.svg)](https://travis-ci.org/npmtest/node-npmtest-zookeeper)

#### apache zookeeper client (zookeeper async API >= 3.4.0)

[![NPM](https://nodei.co/npm/zookeeper.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/zookeeper)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-zookeeper/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-zookeeper/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-zookeeper/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-zookeeper/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-zookeeper/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-zookeeper/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-zookeeper/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-zookeeper/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-zookeeper/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-zookeeper/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-zookeeper/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-zookeeper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-zookeeper/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-zookeeper/build/test-report.html](https://npmtest.github.io/node-npmtest-zookeeper/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-zookeeper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-zookeeper/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-zookeeper/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-zookeeper/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-zookeeper/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-zookeeper/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Yuri Finkelstein"
    },
    "bugs": {
        "url": "https://github.com/yfinkelstein/node-zookeeper/issues"
    },
    "contributors": [
        {
            "name": "Yuri Finkelstein"
        },
        {
            "name": "Woody Anderson"
        },
        {
            "name": "Mark Cavage"
        },
        {
            "name": "Dave Dopson"
        },
        {
            "name": "David Trejo"
        },
        {
            "name": "Pooya Karimian"
        },
        {
            "name": "Jakub Lekstan"
        },
        {
            "name": "Matt Lavin"
        },
        {
            "name": "Roy Cheng"
        }
    ],
    "dependencies": {
        "async": "~2.1.4",
        "lodash": "~4.17.2",
        "nan": "~2.5.0"
    },
    "description": "apache zookeeper client (zookeeper async API >= 3.4.0)",
    "devDependencies": {
        "log4js": "~1.0.1",
        "webworker": ">=0.8.4"
    },
    "directories": {},
    "dist": {
        "shasum": "124fe40110b994a4a455c2bdd4e325899d55663a",
        "tarball": "https://registry.npmjs.org/zookeeper/-/zookeeper-3.4.9-3.tgz"
    },
    "engines": {
        "node": ">=0.10"
    },
    "gitHead": "831916783dfd0bf0a211eb1750e23aea6ce1f501",
    "gypfile": true,
    "homepage": "https://github.com/yfinkelstein/node-zookeeper#readme",
    "keywords": [
        "apache",
        "zookeeper",
        "client"
    ],
    "main": "lib/index",
    "maintainers": [
        {
            "name": "woodya"
        },
        {
            "name": "ddopson"
        },
        {
            "name": "yfinkelstein"
        },
        {
            "name": "josephmoniz"
        },
        {
            "name": "mcavage"
        },
        {
            "name": "kuebk"
        },
        {
            "name": "mdlavin"
        }
    ],
    "name": "zookeeper",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/yfinkelstein/node-zookeeper.git"
    },
    "scripts": {
        "build": "node-gyp configure build",
        "install": "node-gyp rebuild",
        "prepublish": "./scripts/prepublish.sh",
        "test": "pushd test; ./test; popd"
    },
    "version": "3.4.9-3",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
