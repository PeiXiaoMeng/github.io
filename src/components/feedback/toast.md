# Toast

<hr>

##### 效果



##### 安装

```
$ npm install fastly-ui -D
```


##### 引入

```
<import name="fast-toast" src="@fastly/fast-toast/index.ux"></import>
```


##### 使用

```
<fast-toast id="Toast" text="{{ toastText }}" duration="{{ toastDuration }}" icon="{{ toastIcon }}" image="{{ cutomImage }}"></fast-toast>
```




##### API


参数 | 说明 | 类型 | 可选值 | 默认值
---|---|:---:|:---:|---|:---:
text | Toast文案 | String | - | 文本内容
duration | 元素持续的时间（设置为 0 将不会自动消失） | Number | - | 2000
icon | icon类型 | String |`success` `error` | 'none'
image | 自定义图片路径 | String | - | false
