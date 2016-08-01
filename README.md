# eslint-config-nodejs

[![npm version](https://badge.fury.io/js/eslint-config-nodejs.svg)](https://badge.fury.io/js/eslint-config-nodejs)

This package provides a NodeJS with ES6 .eslintrc as an extensible shared config.

### Prerequisites

Since this package is a Eslint Sharing Config, it requires the npm package of `eslint` and `eslint-plugin-import`.

### Installation

`npm i -D eslint eslint-plugin-import eslint-config-nodejs`

Then add the plugin in your .eslintrc like described in the [eslint's documentation](http://eslint.org/docs/user-guide/configuring#using-the-configuration-from-a-plugin)

```
{
    "extends": [
        "nodejs"
    ]
}
```

### TODO
     - add tests 
