# npmtest-eslint-plugin-filenames

#### basic test coverage for  [eslint-plugin-filenames (v1.2.0)](https://github.com/selaux/eslint-plugin-filenames)  [![npm package](https://img.shields.io/npm/v/npmtest-eslint-plugin-filenames.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-eslint-plugin-filenames) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-eslint-plugin-filenames.svg)](https://travis-ci.org/npmtest/node-npmtest-eslint-plugin-filenames)

#### Eslint rule for consistent filenames.

[![NPM](https://nodei.co/npm/eslint-plugin-filenames.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/eslint-plugin-filenames)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-eslint-plugin-filenames/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-eslint-plugin-filenames/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/test-report.html](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-eslint-plugin-filenames/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-eslint-plugin-filenames/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-eslint-plugin-filenames/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-eslint-plugin-filenames/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-eslint-plugin-filenames/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Stefan Lau"
    },
    "bugs": {
        "url": "https://github.com/selaux/eslint-plugin-filenames/issues"
    },
    "dependencies": {
        "lodash.camelcase": "4.3.0",
        "lodash.kebabcase": "4.1.1",
        "lodash.snakecase": "4.1.1",
        "lodash.upperfirst": "4.3.1"
    },
    "description": "Eslint rule for consistent filenames.",
    "devDependencies": {
        "chai": "3.5.0",
        "coveralls": "2.13.0",
        "eslint": "^2.0.0",
        "eslint-plugin-filenames": "^1.0.0",
        "istanbul": "0.4.5",
        "mocha": "3.2.0",
        "sinon": "2.1.0"
    },
    "directories": {},
    "dist": {
        "shasum": "aee9c1c90189c95d2e49902c160eceefecd99f53",
        "tarball": "https://registry.npmjs.org/eslint-plugin-filenames/-/eslint-plugin-filenames-1.2.0.tgz"
    },
    "gitHead": "fa47438366723740a1646f8c04d38fed6ab4254f",
    "homepage": "https://github.com/selaux/eslint-plugin-filenames",
    "keywords": [
        "eslint",
        "eslintplugin",
        "eslint-plugin",
        "file",
        "filename",
        "path"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "selaux"
        }
    ],
    "name": "eslint-plugin-filenames",
    "optionalDependencies": {},
    "peerDependencies": {
        "eslint": "*"
    },
    "repository": {
        "type": "git",
        "url": "git://github.com/selaux/eslint-plugin-filenames.git"
    },
    "scripts": {
        "check-coverage": "istanbul check-coverage --statement 100 --branch 100 --function 100 --lines 100",
        "coveralls": "cat ./build/coverage/lcov.info | coveralls",
        "lint": "eslint .",
        "report-coverage-html": "istanbul report --dir  build/coverage html",
        "test": "npm run lint && npm run unit-test --coverage && npm run check-coverage",
        "unit-test": "istanbul test --dir build/coverage _mocha test -- --recursive --reporter dot"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
