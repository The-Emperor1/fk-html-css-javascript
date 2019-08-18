# 1. 第2章 HTML 5 的常用元素与属性

## 1.1. HTML 5 保留的常用元素

### 1.1.1. HTML 5 保留的基本元素
* `<!--...-->`：注释。
* `<html>`：根元素。
* `<head>`：页面头部内容。
* `<title>`：页面标题。
* `<body>`：页面主体，该标签可以指定id、class、style等核心属性，还可以指定onload、onunload、ondblclick、onmousedown、onmouseup、onmouseover、onmousemove、onmouseout、onkeypress、onkeydown、onkeyup等事件属性。
* `<style>`：引入样式。
* `<h1>到<h6>`：标题一到标题六，块级元素。
* `<p>`：段落，块级元素。
* `<br>`：换行。
* `<hr>`：水平线。
* `<div>`：文档中的节，块级元素。
* `<span>`：与`<div>`类似，行内元素。
几乎所有的HTML元素都可以指定id、class和style属性，id属性用于为HTML元素指定唯一的标识，该标识是通过DOM访问HTML元素的重要途径。class和style属性是CSS样式相关的属性。