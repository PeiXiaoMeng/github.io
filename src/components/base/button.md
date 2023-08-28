# Button

<hr>

##### 效果



##### 安装

```
$ npm install fastly-ui -D
```


##### 引入

```
<import name="fast-button" src="@fastly/fast-button/index.ux"></import>
```


##### 使用

```
<fast-button text="大号按钮" size="large" type="primary" @handle-click="btnClick" sty="margin-bottom: 30px;"></fast-button>
<fast-button size="normal" @handle-click="btnClick" sty="margin-bottom: 30px;margin-right: 20px;"></fast-button>
<fast-button text="圆角按钮" size="normal" circle="{{ true }}" type="primary" @handle-click="btnClick" sty="margin-bottom: 30px;margin-right: 20px;"></fast-button>
<fast-button text="小号按钮" size="small" type="primary" @handle-click="btnClick" sty="margin-bottom: 30px;"></fast-button>
```




##### API


参数 | 说明 | 类型 | 可选值 | 默认值
---|---|:---:|:---:|---|:---:
text | 按钮文案 | String | - | 默认按钮
size | 按钮的大小 | String | `normal` `small` `large` | normal
type | 按钮的类型 | String |`primary` `normal` | ''
circle | 设置按钮圆角 | Boolean | - | false
disabled | 设置按钮为禁用态（不可点击） | Boolean | - | false
sty | 补充样式 | String | - | ''
