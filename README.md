weui.js
=====

### 概述

[WeUI](https://github.com/Tencent/weui.git) 的轻量级 js 封装。

注意：由于微信小程序不支持dom操作，所以weui.js并不适用于小程序。不过WeUI也为小程序开发了另外的版本，详情请看：https://github.com/Tencent/weui-wxss/

### 开发

安装

```shell
git clone https://github.com/Tencent/weui.js.git
cd weui.js
npm install
npm start
```

编译

```shell
npm run build
```


### 使用

#### global 

```html
<link rel="stylesheet" href="https://res.wx.qq.com/open/libs/weui/1.1.2/weui.min.css">
<script type="text/javascript" src="https://res.wx.qq.com/open/libs/weuijs/1.1.2/weui.min.js"></script>
<script type="text/javascript">
    weui.alert('alert');
</script>
```

#### import as module

```javascript
import 'weui';
import weui from 'weui.js';

weui.alert('alert');
```

### 文档

[Documents](https://github.com/Tencent/weui.js/tree/master/docs/README.md)

### 说明

本仓库为本公司业务改造，非腾讯官方 weui
