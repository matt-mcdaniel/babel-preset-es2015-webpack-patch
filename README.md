# babel-preset-es2015-webpack-patch

This is a forked version of [`babel-preset-es2015-webpack`](https://github.com/gajus/babel-preset-es2015-webpack) used to solve package dependency issues when using npm 3+ or when also including [`babel-preset-es2015`](https://www.npmjs.com/package/babel-preset-es2015) as a dependency.

The [issue](https://github.com/gajus/babel-preset-es2015-webpack/issues/10) typically manifests with the following error:
>"Cannot remove 'babel-plugin-transform-es2015-modules-commonjs' from the plugin list."

## Copyright
Copyright (c) 2016, Gajus Kuizinas
All rights reserved.

## License
https://github.com/matt-mcdaniel/babel-preset-es2015-webpack-patch/blob/master/LICENSE
