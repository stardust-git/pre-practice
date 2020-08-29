# **Vue**

<h2 align="right">构建用户界面的渐进式框架</h2>

## **0.课程准备：**

在谷歌商店下载安装vue-devtools，由https://vuejs.org提供

获取笔记：https://github.com/DuYi-Edu/DuYi-VUE

官网：https://vuejs.org/

下载：1.直接通过script标签引用vue.js;2.cdn;3.npm安装

使用：

1.引入vue.js后，得到一个构造函数 Vue

2.在js中实例化Vue对象：**const vm = new Vue()**

3.开始使用

## **一、vue语法**

	### 	**1.传入参数：**

```js
{
    el:"css选择器"   
    配置控制元素，也可以手动添加：  vm.$mount('css选择器');
    data:{
        key:'value' //用于差值表达式
        以下简称这里的内容为vue-data
    }
}
```

