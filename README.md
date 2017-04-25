# npmdoc-node-config-manager

#### basic api documentation for  [node-config-manager (v1.2.0)](https://github.com/Valko54/node-config-manager#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-node-config-manager.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-node-config-manager) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-node-config-manager.svg)](https://travis-ci.org/npmdoc/node-npmdoc-node-config-manager)

#### A configuration manager for NodeJS. It helps you to organize your project and the different configurations of your environments.

[![NPM](https://nodei.co/npm/node-config-manager.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/node-config-manager)

- [https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-node-config-manager/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Damien Picard",
        "url": "https://github.com/valko54"
    },
    "bugs": {
        "url": "https://github.com/Valko54/node-config-manager/issues"
    },
    "contributors": [
        {
            "name": "Laurine Schuster",
            "url": "https://github.com/lsr57"
        },
        {
            "name": "Antoine Detante",
            "url": "https://github.com/adetante"
        }
    ],
    "dependencies": {
        "debug": "2.6.1",
        "js-yaml": "3.8.1"
    },
    "description": "A configuration manager for NodeJS. It helps you to organize your project and the different configurations of your environments.",
    "devDependencies": {
        "chai": "3.5.0",
        "coveralls": "2.11.16",
        "istanbul": "0.4.5",
        "jshint": "2.9.4",
        "mocha": "3.2.0",
        "mocha-lcov-reporter": "1.2.0",
        "rewire": "2.5.2"
    },
    "directories": {},
    "dist": {
        "shasum": "52c4128b85a5728117c82f55f7083ccb45ecc547",
        "tarball": "https://registry.npmjs.org/node-config-manager/-/node-config-manager-1.2.0.tgz"
    },
    "gitHead": "60b3cab0c51d6b8e40e45ef6f96d5345a0e91d4b",
    "homepage": "https://github.com/Valko54/node-config-manager#readme",
    "keywords": [
        "util",
        "config",
        "environment",
        "manager"
    ],
    "license": "MIT",
    "main": "index.js",
    "maintainers": [
        {
            "name": "valko54"
        }
    ],
    "name": "node-config-manager",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Valko54/node-config-manager.git"
    },
    "scripts": {
        "pretest": "./node_modules/jshint/bin/jshint .",
        "test": "NODE_ENV='test' ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha test",
        "test-on-travis": "NODE_ENV='test' ./node_modules/.bin/istanbul cover ./node_modules/.bin/_mocha test && cat ./coverage/lcov.info | ./node_modules/coveralls/bin/coveralls.js"
    },
    "version": "1.2.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
