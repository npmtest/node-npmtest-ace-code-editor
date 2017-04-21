# npmtest-ace-code-editor

#### basic test coverage for  [ace-code-editor (v1.2.3)](http://github.com/ajaxorg/ace)  [![npm package](https://img.shields.io/npm/v/npmtest-ace-code-editor.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-ace-code-editor) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-ace-code-editor.svg)](https://travis-ci.org/npmtest/node-npmtest-ace-code-editor)

#### Ajax.org Code Editor is a full featured source code highlighting editor that powers the Cloud9 IDE

[![NPM](https://nodei.co/npm/ace-code-editor.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/ace-code-editor)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-ace-code-editor/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-ace-code-editor/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-ace-code-editor/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-ace-code-editor/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-ace-code-editor/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-ace-code-editor/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-ace-code-editor/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-ace-code-editor/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-ace-code-editor/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-ace-code-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-ace-code-editor/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-ace-code-editor/build/test-report.html](https://npmtest.github.io/node-npmtest-ace-code-editor/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-ace-code-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-ace-code-editor/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-ace-code-editor/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-ace-code-editor/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-ace-code-editor/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-ace-code-editor/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-ace-code-editor/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-ace-code-editor/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "ace-code-editor",
    "description": "Ajax.org Code Editor is a full featured source code highlighting editor that powers the Cloud9 IDE",
    "version": "1.2.3",
    "homepage": "http://github.com/ajaxorg/ace",
    "engines": {
        "node": ">= 0.6.0"
    },
    "author": "Fabian Jakobs <fabian@c9.io>",
    "main": "lib/ace",
    "repository": {
        "type": "git",
        "url": "http://github.com/ajaxorg/ace.git"
    },
    "dependencies": {
        "mime": "1.2.x"
    },
    "devDependencies": {
        "asyncjs": "0.0.x",
        "node-jsdom": "3.1.5",
        "amd-loader": "~0.0.4",
        "dryice": "0.4.11",
        "architect-build": "https://github.com/c9/architect-build/tarball/17268dce65"
    },
    "mappings": {
        "ace": "."
    },
    "licenses": [
        {
            "type": "BSD New",
            "url": "http://opensource.org/licenses/BSD-3-Clause"
        }
    ],
    "directories": {
        "lib": "lib/ace"
    },
    "scripts": {
        "start": "node static.js",
        "test": "node lib/ace/test/all.js"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
