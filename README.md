# api documentation for  [console.table (v0.8.0)](https://github.com/bahmutov/console.table)  [![npm package](https://img.shields.io/npm/v/npmdoc-console.table.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-console.table) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-console.table.svg)](https://travis-ci.org/npmdoc/node-npmdoc-console.table)
#### Adds console.table method that prints an array of objects as a table in console

[![NPM](https://nodei.co/npm/console.table.png?downloads=true)](https://www.npmjs.com/package/console.table)

[![apidoc](https://npmdoc.github.io/node-npmdoc-console.table/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-console.table_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-console.table/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-console.table/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-console.table/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Gleb Bahmutov",
        "email": "gleb.bahmutov@gmail.com"
    },
    "bugs": {
        "url": "https://github.com/bahmutov/console.table/issues"
    },
    "config": {
        "pre-git": {
            "commit-msg": "simple",
            "pre-commit": [
                "npm test"
            ],
            "pre-push": [],
            "post-commit": [],
            "post-checkout": [],
            "post-merge": []
        }
    },
    "contributors": [],
    "dependencies": {
        "easy-table": "1.0.0"
    },
    "description": "Adds console.table method that prints an array of objects as a table in console",
    "devDependencies": {
        "better-assert": "1.0.2",
        "condition-node-version": "1.3.0",
        "expect.js": "0.3.1",
        "grunt": "0.4.5",
        "grunt-banner": "0.3.1",
        "grunt-clean-console": "0.2.0",
        "grunt-cli": "1.2.0",
        "grunt-contrib-concat": "0.5.0",
        "grunt-contrib-copy": "0.7.0",
        "grunt-contrib-jshint": "1.0.0",
        "grunt-contrib-uglify": "0.7.0",
        "grunt-contrib-watch": "0.6.1",
        "grunt-deps-ok": "0.5.2",
        "grunt-mocha-test": "0.12.7",
        "grunt-nice-package": "0.10.3",
        "grunt-npm2bower-sync": "0.8.1",
        "matchdep": "0.3.0",
        "mocha": "2.4.5",
        "pre-git": "3.8.4",
        "semantic-release": "4.3.5",
        "sinon": "1.12.2",
        "time-grunt": "1.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "69e91d2eabfcced9a0c877ea670b251c6bdbd35f",
        "tarball": "https://registry.npmjs.org/console.table/-/console.table-0.8.0.tgz"
    },
    "engines": {
        "node": "> 0.10"
    },
    "files": [
        "index.js",
        "bower.json",
        "LICENSE-MIT",
        "dist"
    ],
    "gitHead": "a94a90e7be97c6f1efb8f7d8c778f77eefbba3ef",
    "homepage": "https://github.com/bahmutov/console.table",
    "keywords": [
        "beautify",
        "browser",
        "console",
        "html",
        "node"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "bahmutov",
            "email": "gleb.bahmutov@gmail.com"
        }
    ],
    "name": "console.table",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "release": {
        "verifyConditions": {
            "path": "condition-node-version",
            "node": "6"
        }
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/bahmutov/console.table.git"
    },
    "scripts": {
        "build": "grunt",
        "commit": "commit-wizard",
        "demo": "node test/test.js",
        "semantic-release": "semantic-release pre && npm publish && semantic-release post",
        "size": "t=\"$(npm pack .)\"; wc -c \"${t}\"; tar tvf \"${t}\"; rm \"${t}\";",
        "test": "node test/test.js && grunt && npm run unit",
        "unit": "node node_modules/mocha/bin/mocha -R spec"
    },
    "version": "0.8.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module console.table](#apidoc.module.console.table)



# <a name="apidoc.module.console.table"></a>[module console.table](#apidoc.module.console.table)



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
