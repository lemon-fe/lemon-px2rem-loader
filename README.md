# lemon-px2rem-loader

a [webpack](http://webpack.github.io/) loader for [px2rem](https://github.com/lemon-fe/lemon-px2rem-loader.git)

[![npm](https://img.shields.io/npm/v/lemon-px2rem-loader.svg?maxAge=3600)](https://www.npmjs.com/package/lemon-px2rem-loader)
![JS gzip size](http://img.badgesize.io/lemon-fe/lemon-px2rem-loader/master/lib/index.js.svg?compression=gzip&label=gzip%20size:%20JS)

## Install

`npm install lemon-px2rem-loader`

## webpack config

```
{
  loaders: [{ test: /\.css$/, loader: 'style!css!lemon-px2rem?remUnit=75&remPrecision=8' }]
}
```
