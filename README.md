Forked version, it has its package name changed as to not conflict with latest react version

# react

An npm package to get you immediate access to [React](https://facebook.github.io/react/),
without also requiring the JSX transformer. This is especially useful for cases where you
want to [`browserify`](https://github.com/substack/node-browserify) your module using
`React`.

**Note:** by default, React will be in development mode. The development version includes extra warnings about common mistakes, whereas the production version includes extra performance optimizations and strips all error messages.

To use React in production mode, set the environment variable `NODE_ENV` to `production`. A minifier that performs dead-code elimination such as [UglifyJS](https://github.com/mishoo/UglifyJS2) is recommended to completely remove the extra code present in development mode.

## Example Usage

```js
var React = require('react');

// You can also access ReactWithAddons.
var React = require('react/addons');
```

