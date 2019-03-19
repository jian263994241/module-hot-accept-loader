# module-hot-accept-loader

Need webpack@4.

Add 'module.hot.accpet()' to entry files



## Installation

```
 npm install module-hot-accept-loader --dev-save
```


## Usage

```javascript
{
  test: /\.(js|jsx|es)$/,
  exclude: /(node_modules|bower_components)/,
  enforce: 'post',
  use: [
    {
      loader: require.resolve('hmr-accept-loader')
    }
  ]
}
```
