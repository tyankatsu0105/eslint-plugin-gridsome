🚧WIP🚧

# eslint-plugin-gridsome

[![npm version](https://badge.fury.io/js/eslint-plugin-gridsome.svg)](https://badge.fury.io/js/eslint-plugin-gridsome)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

This is eslint plugin for [Gridsome](https://gridsome.org/).

## usage

```bash
$ yarn add eslint-plugin-gridsome vue-eslint-parser -D
```

```javascript
// .eslintrc.*
// this is .eslintrc.js

module.exports = {
  root: true,
  env: {
    node: true,
    es6: true
  },
  plugins: ["gridsome"],
  rules: {
    "gridsome/page-query": "error"
  },
  parser: "vue-eslint-parser"
};
```
