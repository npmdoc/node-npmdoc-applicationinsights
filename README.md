# api documentation for  [applicationinsights (v0.19.0)](https://github.com/Microsoft/ApplicationInsights-node.js#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-applicationinsights.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-applicationinsights) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-applicationinsights.svg)](https://travis-ci.org/npmdoc/node-npmdoc-applicationinsights)
#### Microsoft Application Insights module for Node.JS

[![NPM](https://nodei.co/npm/applicationinsights.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/applicationinsights)

- [https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-applicationinsights/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "bugs": {
        "url": "https://github.com/Microsoft/ApplicationInsights-node.js/issues"
    },
    "contributors": [
        {
            "name": "Application Insights Developer Support"
        },
        {
            "name": "kszostak"
        },
        {
            "name": "southwood",
            "url": "https://github.com/southwood"
        },
        {
            "name": "bogdanbe"
        },
        {
            "name": "lukim"
        }
    ],
    "dependencies": {
        "zone.js": "0.7.6"
    },
    "description": "Microsoft Application Insights module for Node.JS",
    "devDependencies": {
        "mocha": "3.1.2",
        "node-mocks-http": "1.2.3",
        "sinon": "1.17.6",
        "typescript": "2.0.10",
        "typings": "2.0.0"
    },
    "directories": {},
    "dist": {
        "shasum": "8b3af3d4df05429c127cd64431cb81e406097d83",
        "tarball": "https://registry.npmjs.org/applicationinsights/-/applicationinsights-0.19.0.tgz"
    },
    "gitHead": "2116076baa278dc52b1668ebd5aab96975fb33ec",
    "homepage": "https://github.com/Microsoft/ApplicationInsights-node.js#readme",
    "keywords": [
        "exception monitoring",
        "request monitoring",
        "performance monitoring",
        "application insights",
        "microsoft",
        "azure"
    ],
    "license": "MIT",
    "main": "applicationinsights",
    "maintainers": [
        {
            "name": "msftapplicationinsights"
        }
    ],
    "name": "applicationinsights",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/Microsoft/ApplicationInsights-node.js.git"
    },
    "scripts": {
        "prepublish": "tsc --module commonjs --declaration applicationinsights.ts",
        "pretest": "find Tests -type f -name \"*.ts\" | xargs tsc --module commonjs",
        "test": "./node_modules/mocha/bin/mocha ./Tests --recursive"
    },
    "version": "0.19.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
