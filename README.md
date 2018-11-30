🚧WIP🚧

# eslint-plugin-gridsome

This is eslint plugin for [Gridsome](https://gridsome.org/).

## usage

```bash
$ yarn add eslint-plugin-gridsome vue-eslint-parser -D
```

```javascript
// .eslintrc.*
// this is .eslintrc.js

module.exports = {
  plugins: ["gridsome"],
  rules: {
    "gridsome/page-query": "error"
  },
  parser: "vue-eslint-parser"
};
```
