# 快速上手

<hr>

##### 安装

```
$ npm install fastly-ui -D 或 
$ yarn add fastly-ui
```


##### 配置

>如果项目不需要兼容`华为机型`的话在项目根目录新建quickapp.config.js，然后添加别名引用alias：

```
const path = require("path");

module.exports = {
  webpack: {
    resolve: {
      alias: {
        "@fastly": path.resolve(__dirname, "src/fastly-ui"),
      },
      modules: ["./src/fastly-ui"],
    },
  },
};
```

##### 使用 Fastly Ui

>引入所需组件：

```
<import name="fast-button" src="@fastly/fast-button/index.ux"></import>

<template>
	<fast-button></fast-button>
</template>
```

<span style="color: red;">注意：如果需要兼容华为机型的话，需要把@fastly修改为相对路径： "../../../node_modules/fastly-ui/fast-button/index.ux"</span>