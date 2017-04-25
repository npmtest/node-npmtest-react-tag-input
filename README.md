# npmtest-react-tag-input

#### basic test coverage for  [react-tag-input (v4.7.1)](https://github.com/prakhar1989/react-tags#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-react-tag-input.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-react-tag-input) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-react-tag-input.svg)](https://travis-ci.org/npmtest/node-npmtest-react-tag-input)

#### React tags is a fantastically simple tagging component for your React projects

[![NPM](https://nodei.co/npm/react-tag-input.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/react-tag-input)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-react-tag-input/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tag-input/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-react-tag-input/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-react-tag-input/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-react-tag-input/build/test-report.html)|
| test-server-github : | [![github.com test-server](https://npmtest.github.io/node-npmtest-react-tag-input/GitHub-Mark-32px.png)](https://npmtest.github.io/node-npmtest-react-tag-input/build/app/index.html) | | build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-react-tag-input/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-react-tag-input/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-react-tag-input/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-react-tag-input/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-react-tag-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-react-tag-input/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-react-tag-input/build/test-report.html](https://npmtest.github.io/node-npmtest-react-tag-input/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-react-tag-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-react-tag-input/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-react-tag-input/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-react-tag-input/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-react-tag-input/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-react-tag-input/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-react-tag-input/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-react-tag-input/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Prakhar Srivastav"
    },
    "bugs": {
        "url": "https://github.com/prakhar1989/react-tags/issues"
    },
    "dependencies": {
        "lodash": "^4.14.1",
        "prop-types": "^15.5.8",
        "react-dnd": "^2.0.2",
        "react-dnd-html5-backend": "^2.0.0"
    },
    "description": "React tags is a fantastically simple tagging component for your React projects",
    "devDependencies": {
        "babel-cli": "^6.9.0",
        "babel-core": "^6.0.20",
        "babel-loader": "^6.0.1",
        "babel-preset-es2015": "^6.0.15",
        "babel-preset-react": "^6.0.15",
        "babel-preset-stage-0": "^6.0.15",
        "babel-register": "^6.9.0",
        "chai": "^3.5.0",
        "enzyme": "^2.3.0",
        "jest": "^19.0.2",
        "jsdom": "^9.4.0",
        "lodash": "4.17.4",
        "npm-run-all": "^4.0.2",
        "opn": "^4.0.2",
        "prettier": "^1.1.0",
        "react": "^15.1.0",
        "react-addons-test-utils": "^15.1.0",
        "react-dnd-test-backend": "^2.3.0",
        "react-dom": "^15.5.4",
        "react-test-renderer": "^15.5.4",
        "sinon": "^2.1.0",
        "webpack": "^2.4.1",
        "webpack-dev-server": "^2.4.2"
    },
    "directories": {},
    "dist": {
        "shasum": "016f9f57f6bf916f6ee6a1591cdac97784e5b50d",
        "tarball": "https://registry.npmjs.org/react-tag-input/-/react-tag-input-4.7.1.tgz"
    },
    "engines": {
        "node": ">=5.0.0"
    },
    "gitHead": "d3e5c36c8f4ca8cb9367cda10c28c619b4361fb4",
    "homepage": "https://github.com/prakhar1989/react-tags#readme",
    "keywords": [
        "react",
        "drag-drop",
        "tags",
        "tag input",
        "react-component",
        "autosuggest"
    ],
    "license": "MIT",
    "main": "dist-modules/ReactTags.js",
    "maintainers": [
        {
            "name": "prakhar1989"
        }
    ],
    "name": "react-tag-input",
    "optionalDependencies": {},
    "peerDependencies": {
        "react": "^0.14.0 || ^15.0.0-rc",
        "react-dom": "^0.14.0 || ^15.0.0-rc"
    },
    "repository": {
        "type": "git",
        "url": "git+https://github.com/prakhar1989/react-tags.git"
    },
    "scripts": {
        "build": "webpack --config webpack-production.config.js --progress --colors && babel lib --out-dir dist-modules",
        "dev": "webpack-dev-server --config webpack-dev-server.config.js --progress --inline --colors",
        "format": "prettier  --write --jsx-bracket-same-line --trailing-comma es5 lib/*.js test/*.js",
        "open-localhost": "node -e 'require(\"opn\")(\"http://localhost:8090/example/index.html\")'",
        "start": "npm-run-all --parallel open-localhost dev",
        "test": "jest --notify --coverage test/*",
        "test-watch": "jest --watch --notify test/*"
    },
    "version": "4.7.1",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
