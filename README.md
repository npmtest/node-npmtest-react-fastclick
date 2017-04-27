# npmtest-react-fastclick

#### basic test coverage for  [react-fastclick (v3.0.1)](https://github.com/JakeSidSmith/react-fastclick)  [![npm package](https://img.shields.io/npm/v/npmtest-react-fastclick.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-fastclick) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-fastclick.svg)](https://travis-ci.org/npmtest/node-npmtest-react-fastclick)

#### Fast Touch Events for React

[![NPM](https://nodei.co/npm/react-fastclick.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-fastclick)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-fastclick/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-fastclick/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-fastclick/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-fastclick/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-fastclick/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-fastclick/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-fastclick/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-fastclick/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-fastclick/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-fastclick/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-fastclick/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-fastclick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-fastclick/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-fastclick/build/test-report.html](https://npmtest.github.io/node-npmtest-react-fastclick/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-fastclick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-fastclick/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-fastclick/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-fastclick/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-fastclick/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-fastclick/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-fastclick/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-fastclick/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Jake 'Sid' Smith"
    },
    "bugs": {
        "url": "https://github.com/JakeSidSmith/react-fastclick/issues"
    },
    "dependencies": {},
    "description": "Fast Touch Events for React",
    "devDependencies": {
        "chai": "=3.5.0",
        "eslintrc": "git+https://github.com/JakeSidSmith/eslintrc.git#v0.0.1",
        "jsdom": "=8.4.1",
        "mocha": "=2.4.5",
        "nyc": "=10.1.2",
        "react": "=15.4.2",
        "react-addons-test-utils": "=15.4.2",
        "react-dom": "=15.4.2",
        "sinon": "=1.17.3",
        "sinon-chai": "=2.8.0"
    },
    "directories": {},
    "dist": {
        "shasum": "e438f9a63cad77c0bb61bb7fa4fd6668451ed83d",
        "tarball": "https://registry.npmjs.org/react-fastclick/-/react-fastclick-3.0.1.tgz"
    },
    "engines": {
        "node": "*"
    },
    "gitHead": "69a5cee55f106c4758069101d63321d451996a01",
    "homepage": "https://github.com/JakeSidSmith/react-fastclick",
    "keywords": [
        "react",
        "fastclick",
        "fast",
        "click",
        "touch",
        "events",
        "event",
        "mobile"
    ],
    "license": "MIT",
    "main": "src/index.js",
    "maintainers": [
        {
            "name": "jakesidsmith"
        }
    ],
    "name": "react-fastclick",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "*"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/JakeSidSmith/react-fastclick.git"
    },
    "scripts": {
        "lint-src": "eslint -c node_modules/eslintrc/.eslintrc-es5 src/",
        "lint-tests": "eslint -c node_modules/eslintrc/.eslintrc-es5-mocha tests/",
        "mocha": "nyc mocha --bail --recursive 'tests/**/*.test.js'",
        "test": "npm run lint-src && npm run lint-tests && npm run mocha"
    },
    "version": "3.0.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
