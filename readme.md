# is-path  [![experimental](https://img.shields.io/badge/stability-unstable-yellow.svg)](http://github.com/badges/stability-badges) [![Build Status](https://img.shields.io/travis/dfcreative/is-path.svg)](https://travis-ci.org/dfcreative/is-path)

Check if string is relative or absolute path and not URL.

[![npm install is-path](https://nodei.co/npm/is-path.png?mini=true)](https://npmjs.org/package/is-path/)

```js
const isPath = require('is-path')

isPath('C:\\xxx') //true
isPath('./something') //true
isPath('../something') //true
isPath('https://github.com/xyz') //false
```

If you find edge case, please address [issues]().
