## rolldate [![npm](https://img.shields.io/npm/v/rolldate.svg)](https://www.npmjs.com/package/rolldate) [![npm](https://img.shields.io/npm/dm/rolldate.svg)](https://www.npmjs.com/package/rolldate)
此插件为[jquery-date](https://github.com/weijhfly/jqueryDatePlugin "jquery-date")的全新版本，主要为了解决旧版参数设计不够合理、滑动效率不高、依赖jquery、没有可选的主题风格等问题。
## rolldate的整体设计如下
![rolldate](https://weijhfly.github.io/images/rolldate.png)
## 使用方式
### commonJS
```js
var rolldate = require('rolldate');
new rolldate.Date({
  el:'#date'
})
```
### require.js
```js
require(['rolldate'],function(rolldate){
  new rolldate.Date({
    el:'#date'
  })
})
```
### browser
```js
new rolldate.Date({
  el:'#date'
})
```
## 演示
[rolldate](https://weijhfly.github.io/rolldate-index.html "rolldate")(pc端建议使用浏览器的手机模式打开)