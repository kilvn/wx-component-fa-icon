# wx-component-fa-icon
微信小程序 fa-icon 图标插件

基于 Font-Awesome 4.7.0 版构建，个人觉得uni-icon使用方便，所以参考了uni-icon的形式，使用方式和 uni-icon 插件类似。

组件名：fa-icon

## 使用方式：
在 `script` 中引用组件

```
import faIcon from "@/components/fa-icon/fa-icon.vue"
export default {
    components: {
        faIcon
    }
}
```

在 `template` 中使用组件

```
<fa-icon type="home" size="22" color="#666" @click="testJS"></fa-icon>
```

图标效果参考：[图标库 – Font Awesome 中文网](http://www.fontawesome.com.cn/faicons/) www.fontawesome.com.cn

## Icon 属性说明：

| 属性名 | 类型 | 默认值 | 说明 |
|:------:|:------:|:------:|:------|
| type |string | - |图标图案，在Font Awesome 中文网4.7.0版本中的图标都可以，不需要 fa- 前缀|
| color |string|-|图标颜色|
| size | int | 24 |图标大小|
| @click | EventHandle |-|点击 Icon 触发事件|

组件集成了一些bootstrap 4 的默认颜色，可以直接调用：

$\color{#007bff}{text-primary}$
$\color{#6c757d}{text-secondary}$
$\color{#28a745}{text-success}$
$\color{#dc3545}{text-danger}$
$\color{#ffc107}{text-warning}$
$\color{#17a2b8}{text-info}$
$\color{#f8f9fa}{text-light}$
$\color{#343a40}{text-dark}$
$\color{rgb(138, 147, 155)}{text-muted}$
$\color{#fff}{text-white}$
$\color{#ddd}{text-grey}$
