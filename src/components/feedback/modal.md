# Modal

<hr>

##### 效果



##### 安装

```
$ npm install fastly-ui -D
```


##### 引入

```
<import name="fast-modal" src="@fastly/fast-modal/index.ux"></import>
```


##### 使用

```
<fast-modal 
      title="标题" 
      content="这里是正文内容，欢迎访问FastlyUi 有任何关于ui库的问题可加入讨论群或通过issue提问"
      is-opend="{{ isOpend }}"
      @btn-cancel="btnCancel"
      @btn-confirm="btnConfirm"></fast-modal>
```




##### API


参数 | 说明 | 类型 | 可选值 | 默认值
---|---|:---:|:---:|---|:---:
title | 模态框标题 | String | - | ''
content | 模态框内容 | String | - | ''
is-opend | 是否显示模态框 | Boolean | - | false
cancel-text | 取消按钮文案 | String | - | ''
confirm-text | 确认按钮文案 | String | - | ''
