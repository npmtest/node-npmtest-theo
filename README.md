# npmtest-theo

#### basic test coverage for  [theo (v5.0.0)](https://github.com/salesforce-ux/theo)  [![npm package](https://img.shields.io/npm/v/npmtest-theo.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-theo) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-theo.svg)](https://travis-ci.org/npmtest/node-npmtest-theo)

#### A set of Gulp plugins for transforming and formatting Design Tokens

[![NPM](https://nodei.co/npm/theo.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/theo)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-theo/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-theo/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-theo/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-theo/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-theo/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-theo/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-theo/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-theo/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-theo/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-theo/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-theo/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-theo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-theo/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-theo/build/test-report.html](https://npmtest.github.io/node-npmtest-theo/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-theo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-theo/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-theo/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-theo/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-theo/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-theo/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-theo/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-theo/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "authors": [
        "Salesforce and contributors",
        "Adam Putinski",
        "Sönke Rohde <soenke.rohde@gmail.com>"
    ],
    "bugs": {
        "url": "https://github.com/salesforce-ux/theo/issues"
    },
    "dependencies": {
        "gulp-util": "^3.0.8",
        "js-yaml": "^3.7.0",
        "json5": "^0.5.1",
        "lodash": "^4.17.4",
        "no-case": "^2.3.1",
        "through2": "^2.0.3",
        "tinycolor2": "~1.4.1",
        "xml2js": "^0.4.17"
    },
    "description": "A set of Gulp plugins for transforming and formatting Design Tokens",
    "devDependencies": {
        "eslint": "^3.13.1",
        "eslint-config-standard": "^6.2.1",
        "eslint-plugin-promise": "^3.4.0",
        "eslint-plugin-standard": "^2.0.1",
        "gulp": "^3.9.1",
        "jest": "^18.1.0",
        "sinon": "^1.17.7"
    },
    "directories": {},
    "dist": {
        "shasum": "f0467ceb5ec96a949f1f6c1aeb6655dba3fe2f94",
        "tarball": "https://registry.npmjs.org/theo/-/theo-5.0.0.tgz"
    },
    "engines": {
        "node": ">=6.3.1"
    },
    "gitHead": "05e71ce29f0f269b30889056a708d7e6f2f2c703",
    "homepage": "https://github.com/salesforce-ux/theo",
    "jest": {
        "testRegex": "/__tests__/.*\\.test\\.js$"
    },
    "keywords": [
        "css",
        "design",
        "properties",
        "tokens",
        "sass",
        "scss",
        "stylus",
        "less",
        "iOS",
        "Android",
        "aura"
    ],
    "license": "SEE LICENSE IN README.md",
    "main": "lib/index.js",
    "maintainers": [
        {
            "name": "aputinski"
        },
        {
            "name": "salesforce-ux"
        },
        {
            "name": "srohde"
        }
    ],
    "name": "theo",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/salesforce-ux/theo.git"
    },
    "scripts": {
        "lint": "eslint . --ext .js --format codeframe",
        "test": "jest"
    },
    "version": "5.0.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
