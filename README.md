# npmtest-vue-router

#### basic test coverage for  [vue-router (v2.4.0)](https://github.com/vuejs/vue-router#readme)  [![npm package](https://img.shields.io/npm/v/npmtest-vue-router.svg?style=flat-square)](https://www.npmjs.org/package/npmtest-vue-router) [![travis-ci.org build-status](https://api.travis-ci.org/npmtest/node-npmtest-vue-router.svg)](https://travis-ci.org/npmtest/node-npmtest-vue-router)

#### Official router for Vue.js 2

[![NPM](https://nodei.co/npm/vue-router.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/vue-router)

| git-branch : | [alpha](https://github.com/npmtest/node-npmtest-vue-router/tree/alpha)|
|--:|:--|
| coverage : | [![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-router/build/coverage.badge.svg)](https://npmtest.github.io/node-npmtest-vue-router/build/coverage.html/index.html)|
| test-report : | [![test-report](https://npmtest.github.io/node-npmtest-vue-router/build/test-report.badge.svg)](https://npmtest.github.io/node-npmtest-vue-router/build/test-report.html)|
| build-artifacts : | [![build-artifacts](https://npmtest.github.io/node-npmtest-vue-router/glyphicons_144_folder_open.png)](https://github.com/npmtest/node-npmtest-vue-router/tree/gh-pages/build)|

- [https://npmtest.github.io/node-npmtest-vue-router/build/coverage.html/index.html](https://npmtest.github.io/node-npmtest-vue-router/build/coverage.html/index.html)

[![istanbul-coverage](https://npmtest.github.io/node-npmtest-vue-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fcoverage.lib.html.png)](https://npmtest.github.io/node-npmtest-vue-router/build/coverage.html/index.html)

- [https://npmtest.github.io/node-npmtest-vue-router/build/test-report.html](https://npmtest.github.io/node-npmtest-vue-router/build/test-report.html)

[![test-report](https://npmtest.github.io/node-npmtest-vue-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Ftest-report.html.png)](https://npmtest.github.io/node-npmtest-vue-router/build/test-report.html)

- [https://npmdoc.github.io/node-npmdoc-vue-router/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-vue-router/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-vue-router/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-vue-router/build/apidoc.html)

![npmPackageListing](https://npmtest.github.io/node-npmtest-vue-router/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmtest.github.io/node-npmtest-vue-router/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "Evan You"
    },
    "bugs": {
        "url": "https://github.com/vuejs/vue-router/issues"
    },
    "dependencies": {},
    "description": "Official router for Vue.js 2",
    "devDependencies": {
        "babel-core": "^6.11.4",
        "babel-eslint": "^7.1.1",
        "babel-loader": "^6.2.4",
        "babel-plugin-syntax-dynamic-import": "^6.18.0",
        "babel-preset-es2015": "^6.9.0",
        "babel-preset-es2015-loose": "^8.0.0",
        "babel-preset-flow-vue": "^1.0.0",
        "buble": "^0.15.2",
        "chromedriver": "^2.21.2",
        "cross-spawn": "^5.0.1",
        "css-loader": "^0.26.1",
        "es6-promise": "^4.0.5",
        "eslint": "^3.0.1",
        "eslint-config-vue": "^2.0.1",
        "eslint-plugin-flow-vars": "^0.5.0",
        "eslint-plugin-vue": "^2.0.1",
        "express": "^4.14.0",
        "express-urlrewrite": "^1.2.0",
        "flow-bin": "^0.40.0",
        "gitbook-plugin-edit-link": "^2.0.2",
        "gitbook-plugin-github": "^3.0.0",
        "jasmine": "2.5.3",
        "nightwatch": "^0.9.5",
        "nightwatch-helpers": "^1.0.0",
        "path-to-regexp": "^1.5.3",
        "phantomjs-prebuilt": "^2.1.7",
        "rollup": "^0.41.4",
        "rollup-plugin-buble": "^0.15.0",
        "rollup-plugin-commonjs": "^7.0.0",
        "rollup-plugin-flow-no-whitespace": "^1.0.0",
        "rollup-plugin-node-resolve": "^2.0.0",
        "rollup-plugin-replace": "^1.1.1",
        "rollup-watch": "^3.2.2",
        "selenium-server": "^2.53.1",
        "typescript": "^2.0.3",
        "uglify-js": "^2.7.0",
        "vue": "^2.1.0",
        "vue-loader": "^11.0.0",
        "vue-template-compiler": "^2.1.0",
        "webpack": "^2.2.0",
        "webpack-dev-middleware": "^1.9.0"
    },
    "directories": {},
    "dist": {
        "shasum": "56a635e1434a1966ac095f2a485bebdcfc36cec5",
        "tarball": "https://registry.npmjs.org/vue-router/-/vue-router-2.4.0.tgz"
    },
    "files": [
        "src",
        "dist/*.js",
        "types/*.d.ts"
    ],
    "gitHead": "e393812e6bc9461e75c3f78d0101fd39af772638",
    "homepage": "https://github.com/vuejs/vue-router#readme",
    "keywords": [
        "vue",
        "router",
        "routing"
    ],
    "license": "MIT",
    "main": "dist/vue-router.common.js",
    "maintainers": [
        {
            "name": "yyx990803"
        }
    ],
    "module": "dist/vue-router.esm.js",
    "name": "vue-router",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/vuejs/vue-router.git"
    },
    "scripts": {
        "build": "node build/build.js",
        "dev": "node examples/server.js",
        "dev:dist": "rollup -wm -c build/dev.config.js",
        "docs": "cd docs && gitbook install && gitbook serve",
        "docs:deploy": "bash ./build/update-docs.sh",
        "lint": "eslint src examples",
        "release": "bash build/release.sh",
        "test": "npm run lint && flow check && npm run test:unit && npm run test:e2e && npm run test:types",
        "test:e2e": "node test/e2e/runner.js",
        "test:types": "tsc -p types/test",
        "test:unit": "jasmine JASMINE_CONFIG_PATH=test/unit/jasmine.json"
    },
    "typings": "types/index.d.ts",
    "unpkg": "dist/vue-router.js",
    "version": "2.4.0",
    "bin": {}
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
