# hmr-accept-loader

add 'module.hot.accpet()' to entry files


## Installation

```
 npm install hmr-accept-loader --dev-save
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
