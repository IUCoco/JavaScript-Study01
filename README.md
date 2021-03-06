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
类的样式
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
   
#### [ID]  
[ID]类型样式
```
<div id="header">
<h1>City Gallery</h1>
</div>

<div id="nav">
London<br>
Paris<br>
Tokyo<br>
</div>

<div id="section">
<h1>London</h1>
<p>
London is the capital city of England. It is the most populous city in the United Kingdom,
with a metropolitan area of over 13 million inhabitants.
</p>
<p>
Standing on the River Thames, London has been a major settlement for two millennia,
its history going back to its founding by the Romans, who named it Londinium.
</p>
</div>

<div id="footer">
Copyright W3School.com.cn
</div>
```  
#### 响应式网页  
RWD 指的是响应式 Web 设计（Responsive Web Design）  
RWD 能够以可变尺寸传递网页  
RWD 对于平板和移动设备是必需的  
##### 使用框架Bootstrap  
另一个创建响应式设计的方法，是使用现成的 CSS 框架。  
Bootstrap 是最流行的开发响应式 web 的 HTML, CSS, 和 JS 框架。  
Bootstrap 帮助您开发在任何尺寸都外观出众的站点：显示器、笔记本电脑、平板电脑或手机：  
