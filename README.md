# JavaScript-Study
JavaScript 学习  
**************声明该资料来源于w3school以及网络博客整理，仅供学习交流谢谢！******** 

### HTML 注释标签  
您能够通过如下语法向 HTML 源代码添加注释：  
`<!-- 在此处写注释 -->`  

### CSS如何使用样式  
当浏览器读到一个样式表，它就会按照这个样式表来对文档进行格式化。有以下三种方式来插入样式表：  

#### 外部样式表  
当样式需要被应用到很多页面的时候，外部样式表将是理想的选择。使用外部样式表，你就可以通过更改一个文件来改变整个站点的外观。  
`<head>  
<link rel="stylesheet" type="text/css" href="mystyle.css">  
</head>`  

#### 内部样式表  
当单个文件需要特别样式时，就可以使用内部样式表。你可以在 head 部分通过` <style> `标签定义内部样式表.  
```
<head>
<style type="text/css">
body {background-color: red}
p {margin-left: 20px}
</style>
</head>
```
#### 内联样式
当特殊的样式需要应用到个别元素时，就可以使用内联样式。 使用内联样式的方法是在相关的标签中使用样式属性。样式属性可以包含任何 CSS 属性。以下实例显示出如何改变段落的颜色和左外边距。
`<p style="color: red; margin-left: 20px">
This is a paragraph
</p>`  
#### 类  
```
<html>
<head>
<style>
.cities {
    background-color:black;
    color:white;
    margin:20px;
    padding:20px;
} 
</style>
</head>

<body>

<div class="cities">
<h2>London</h2>
<p>
London is the capital city of England. 
It is the most populous city in the United Kingdom, 
with a metropolitan area of over 13 million inhabitants.
</p>
</div> 
</body>
</html>
```
