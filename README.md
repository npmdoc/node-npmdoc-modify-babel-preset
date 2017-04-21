# npmdoc-modify-babel-preset

#### api documentation for  modify-babel-preset (v3.2.1)  [![npm package](https://img.shields.io/npm/v/npmdoc-modify-babel-preset.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-modify-babel-preset) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-modify-babel-preset.svg)](https://travis-ci.org/npmdoc/node-npmdoc-modify-babel-preset)

#### Create a modified babel preset based on an an existing preset.

[![NPM](https://nodei.co/npm/modify-babel-preset.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/modify-babel-preset)

- [https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-modify-babel-preset/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "name": "modify-babel-preset",
    "version": "3.2.1",
    "description": "Create a modified babel preset based on an an existing preset.",
    "main": "index.js",
    "scripts": {
        "prepublish": "cross-env NODE_ENV=development npm test",
        "pretest": "cd test/fixtures/two/node_modules/one && npm i",
        "test": "mocha test/*.js",
        "release": "git commit -am $npm_package_version && git tag $npm_package_version && git push && git push --tags && npm publish"
    },
    "keywords": [
        "babel",
        "preset"
    ],
    "author": "Jason Miller <jason@developit.ca>",
    "repository": {
        "type": "git",
        "url": "https://github.com/developit/modify-babel-preset.git"
    },
    "license": "MIT",
    "dependencies": {
        "require-relative": "^0.8.7"
    },
    "devDependencies": {
        "babel-plugin-transform-react-jsx": "^6.8.0",
        "babel-preset-es2015": "^6.9.0",
        "chai": "^3.5.0",
        "cross-env": "^2.0.0",
        "mocha": "^2.5.3"
    }
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
