# Input

<hr>

##### 效果



##### 安装

```
$ npm install fastly-ui -D
```


##### 引入

```
<import name="fast-input" src="@fastly/fast-input/index.ux"></import>
```


##### 使用

```
<custom-label title="默认输入框"></custom-label>
<fast-input placeholder="默认输入框" @input-change="inputChange"></fast-input>

<custom-label title="带下边框的输入框"></custom-label>
<fast-input placeholder="带下边框的输入框" border="{{ true }}"></fast-input>

<custom-label title="带前缀输入框"></custom-label>
<fast-input placeholder="带前缀输入框" prefix="{{ preObj }}" @click-prefix="clickRrefix"></fast-input>

<custom-label title="带后缀输入框"></custom-label>
<fast-input placeholder="带后缀输入框" suffix="{{ suffixObj }}" @click-suffix="clickSuffix"></fast-input>

<custom-label title="禁用输入框"></custom-label>
<fast-input placeholder="禁用输入框" disabled="{{ true }}"></fast-input>
```




##### API


参数 | 说明 | 类型 | 可选值 | 默认值
---|---|:---:|:---:|---|:---:
type | 按钮类型 | String | `text` `number` `password` | `text`
placeholder | placeholder文案 | String | - | ''
border | 是否有下边框 | Boolean | - | false
prefix | input输入框前缀图标配置 | Object | 示例：`{ image: '../../assets/images/clear.png', sty: 'width: 30px;height: 30px;' }` | null 
suffix | input输入框后缀图标配置 | Object | 示例：`{ image: '../../assets/images/clear.png', sty: 'width: 30px;height: 30px;' }` | null 
disabled | 是否禁用 | Boolean | - | false
sty | 补充样式 | String | - | ''
