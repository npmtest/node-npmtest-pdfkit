# npmtest-pdfkit

#### basic test coverage for  [pdfkit (v0.8.0)](http://pdfkit.org/)  [![npm package](https://img.shields.io/npm/v/npmtest-pdfkit.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-pdfkit) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-pdfkit.svg)](https://travis-ci.org/npmtest/node-npmtest-pdfkit)

#### A PDF generation library for Node.js

[![NPM](https://nodei.co/npm/pdfkit.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/pdfkit)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-pdfkit/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfkit/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-pdfkit/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-pdfkit/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-pdfkit/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-pdfkit/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-pdfkit/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-pdfkit/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-pdfkit/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-pdfkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-pdfkit/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-pdfkit/build/test-report.html](https://npmtest.github.io/node-npmtest-pdfkit/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-pdfkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-pdfkit/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-pdfkit/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-pdfkit/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-pdfkit/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-pdfkit/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-pdfkit/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-pdfkit/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Devon Govett",
        "url": "http://badassjs.com/"
    },
    "browserify": {
        "transform": [
            "brfs"
        ]
    },
    "bugs": {
        "url": "http://github.com/devongovett/pdfkit/issues"
    },
    "dependencies": {
        "fontkit": "^1.0.0",
        "linebreak": "~0.1.0",
        "png-js": ">=0.1.0"
    },
    "description": "A PDF generation library for Node.js",
    "devDependencies": {
        "blob-stream": "^0.1.2",
        "brace": "^0.2.1",
        "brfs": "~1.0.1",
        "browserify": "^3.39.0",
        "codemirror": "~3.20.0",
        "coffee-script": ">=1.0.1",
        "coffeeify": "^0.6.0",
        "exorcist": "^0.1.5",
        "iconv-lite": "^0.4.13",
        "jade": "~1.1.5",
        "markdown": "~0.5.0"
    },
    "directories": {},
    "dist": {
        "shasum": "0b3f7c0c3b00cc4f7f69e46d85d2a7cbb3818af6",
        "tarball": "https://registry.npmjs.org/pdfkit/-/pdfkit-0.8.0.tgz"
    },
    "engine": [
        "node >= v0.10.0"
    ],
    "gitHead": "08ef766c00ee6cb377322f58f5c388aae0bf36bb",
    "homepage": "http://pdfkit.org/",
    "keywords": [
        "pdf",
        "pdf writer",
        "pdf generator",
        "graphics",
        "document",
        "vector"
    ],
    "main": "js/document",
    "maintainers": [
        {
            "name": "devongovett"
        }
    ],
    "name": "pdfkit",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/devongovett/pdfkit.git"
    },
    "scripts": {
        "postpublish": "make clean",
        "prepublish": "make js"
    },
    "version": "0.8.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
