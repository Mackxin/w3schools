# W3schools-HTML

> 2019-06-04，开始学习
>
> 主要分享的是在W3schools.com上HTML的内容哈

## Home（首页）

基本模板

```html
<!DOCTYPE html>
<html>
<head>
<title>HTML</title>    
</head>
<body>
<h1>这是一个H1标题</h1>
<p>这是一个p标签</p>
</body>
</html>
```

## Introdution（介绍）

看一下我们刚学的新标签哈

```
<!DOCTYPE html>
<html>
<head>
<title>
<body>
<h1>
<p>
```

## Editors（编辑）

我这里用的编辑器是VSCode编辑器哈

## Basic（基本）

```html
<h1>这个是h1标签哈</h1>
<h2>这个是h2标签哈</h2>
<h3>这个是h3标签哈</h3>
<p>这个是p标签</p>
<a href="http://mackxin.com" target="_blank">mackxin</a>
<img src="mackxin.jpg" alt="mackxin" width="200" height="200">
<button>这个是按钮哈</button>
<ul>
    <li>列表一</li>
    <li>列表二</li>
    <li>列表三</li>
</ul>
```

## Elements（元素）

这个主要还是讲的还是上面的元素

## Attributes（属性）

```html
<a href="http://mackxin.com"></a>
<img src="mackxin.png">
<img src="mackxin.png" width="200" height="200">
<img src="mackxin.png" alt="图片无法显示的时候，这个文字就会显示哈">
<p style="color:red;"></p>
<p title="鼠标移到P标签上这里的文字会显示出来哈">把鼠标移到这里来看看效果哈</p>
<p title="xin 'ke' zhan">把鼠标移到这里来看看效果哈</p>
<p title='xin "ke" zhan'>把鼠标移到这里来看看效果哈</p>
```

```html
<!DOCTYPE html>
<html lang="en-US">
<body>
    ···
</body>
</html>
```

## Headings（标题）

```html
<h1>标题 1</h1>
<hr>
<h2>标题 2</h2>
<hr>
<h3>标题 3</h3>
<hr>
<h4>标题 4</h4>
<hr>
<h5>标题 5</h5>
<hr>
<h6>标题 6</h6>
```

```html
<!DOCTYPE html>
<html>
<head>
	<title>馨客栈 | Mackxin</title>
	<meta charset="UTF-8">
</head>
<body>
	 ···
</body>
</html>
```

## Paragraphs（段落）

```html
<p>
关注分享，
关注导航，
关注馨客栈
</p>
<p>关注分享<br>关注导航<br>关注馨客栈</p>
<pre>
关注分享
关注导航
关注馨客栈
</pre>
```

## Styles（样式）

```html
<body style="background-color:powderblue;">
<h1 style="color:purple;font-size:200%;text-align:center;">h1标签</h1>
<p sytle="font-size:25px;font-family:courier;">p标签</p>
</body>
```

## Formatting（格式）

```html
<p><b>文字是加粗的哈</b></p>
<p><i>文字是斜体的哈</i></p>
<p>馨客栈<sub>下标小字</sub>Mackxin<sup>上标小字</sup></p>
<p><strong>文字也是加粗的哈</strong></p>
<p><em>文字也是斜体的哈</em></p>
<h2>正常的文字哈<small>比较小的文字哈</small>标签h2文字哈</h2>
<h2>关注分享，关注导航，关注<mark>馨客栈</mark>，有么有看到有文字突显出来了哈</h2>
<p>看看文字有什么变化哈<del>删除线的文字</del></p>
<p>文字下面是有一个横线哈，注意看<ins>文字下面横线哈</ins></p>
```

## Quotation（引号）

```php+HTML
<p>一段文字：<q>文字左右两边有引号哈，注意了栈友们</q></p>
<blockquote cite="http://mackxin.com">
    关注分享，关注导航，关注馨客栈
</blockquote>
<p>定义首字母缩写<abbr title="witer cursor">wc</abbr></p>
<address>
广东省<br> 
广州市<br>
天河区<br>
体育西路<br>
关注分享，关注导航，关注馨客栈
</address>
<p><cite>标题</cite>主要定义了作品的标题哈</p>
<bdo dir="rtl">关注分享，关注导航，关注馨客栈</bdo>
```

## Comments（注释）

html文件的注释

```html
<!-- 这里写的注释的内容哈 -->
```

css文件的注释

```css
/* css文件的注释哈 */
```

## Colors（颜色）

```html
<h1 style="background-color:Tomato;">Tomato</h1>
<h1 style="background-color:Orange;">Orange</h1>
<h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
<h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
<h1 style="background-color:Gray;">Gray</h1>
<h1 style="background-color:SlateBlue;">SlateBlue</h1>
<h1 style="background-color:Violet;">Violet</h1>
<h1 style="background-color:LightGray;">LightGray</h1>
<h1 style="color:Tomato;">Hello Mackxin</h1>
<p style="color:DodgerBlue;">馨客栈分享</p>
<p style="color:MediumSeaGreen;">馨客栈情报局</p>
<h1 style="border:2px solid Tomato;">馨客栈赞助</h1>
<h1 style="border:2px solid DodgerBlue;">馨客栈导航</h1>
<h1 style="border:2px solid Violet;">馨客栈前端导航</h1>
<h1 style="background-color:rgb(255, 99, 71);">馨客栈破冰导航</h1>
<h1 style="background-color:#ff6347;">馨客栈电商导航</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">馨客栈设计导航</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">馨客栈学习导航</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">馨客栈更新页面</h1>
```

## CSS

```css
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="style.css">
<style>
body {background-color: powderblue;}
h1   {color: blue;font-size:18px;}
p    {color: red;border:1px solid red;padding:20px;margin:50px;}
#fx {color:purple;}
.qbj {color:orange;}
</style>
</head>
<body>
<h1>馨客栈导航</h1>
<p class="qbj">馨客栈情报局</p>
<p id="fx">馨客栈分享</p>
</body>
</html>
```

## Links（链接）

```css
<style>
a:link {
  color: green; 
  background-color: transparent; 
  text-decoration: none;
}
a:visited {
  color: pink;
  background-color: transparent;
  text-decoration: none;
}
a:hover {
  color: red;
  background-color: transparent;
  text-decoration: underline;
}
a:active {
  color: yellow;
  background-color: transparent;
  text-decoration: underline;
}
</style>
<a href="https://www.w3schools.com/html/">w3schools-HTML</a>
<a href="index.html">
  <img src="mackxin.png" alt="mackxin" style="width:42px;height:42px;border:0;">
</a>
```

```css
<h2 id="me">定位到了这里哈</h2>
<a href="#me">点击定位到me的内容那里哈</a>

```

## Images（图片）

```css
<img src="mackxin.jpg" alt="馨客栈">
<img src="mackxin.jpg" alt="xininn" style="width:500px;height:600px;">
<img src="mackxin.jpg" alt="xinkezhan" width="500" height="600">
<body style="background-image:url('mackxin.jpg');">
```

```css
<p>点击图片上划定的三个区域可以跳转到相对应的页面</p>

<img src="workplace.jpg" alt="Workplace" usemap="#tu" width="400" height="379">

<map name="tu">
  <area shape="rect" coords="34,44,270,350" alt="电脑" href="computer.html">
  <area shape="rect" coords="290,172,333,250" alt="手机" href="phone.html">
  <area shape="circle" coords="337,300,44" alt="咖啡" href="coffee.html">
</map>
```

```css
<picture>
  <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">
  <source media="(min-width: 465px)" srcset="img_white_flower.jpg">
  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">
</picture>
```

## Tables（表格）

```html
<style>
table {
  font-family: arial, sans-serif;
  border-collapse: collapse; /*合并表格的边框不分开，默认值是separate表格的边框是分开的*/
  width: 100%;  /*表格是占满整个屏幕的*/
  border-spacing: 5px;/*边框之间的距离是5像素，如果设置了border-collapse: collapse;，那么这个属性不会生效的哈*/
}

td, th {
  border: 1px solid #dddddd;
  text-align: left;
  padding: 8px;
}

tr:nth-child(even) {
  background-color: #dddddd;
}
</style>
<table>
  <tr><!--表头哈-->
    <th>Company</th>
    <th>Contact</th>
    <th>Country</th>
  </tr>
  <tr>
    <td>Alfreds Futterkiste</td>
    <td>Maria Anders</td>
    <td>Germany</td>
  </tr>
  <tr>
    <td>Centro comercial Moctezuma</td>
    <td>Francisco Chang</td>
    <td>Mexico</td>
  </tr>
  <tr>
    <td>Ernst Handel</td>
    <td>Roland Mendel</td>
    <td>Austria</td>
  </tr>
  <tr>
    <td>Island Trading</td>
    <td>Helen Bennett</td>
    <td>UK</td>
  </tr>
</table>
```

表格横向合并

```html
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 5px;
  text-align: left;    
}
</style>
<table style="width:100%">
  <tr>
    <th>名字</th>
    <th colspan="2">电话</th>
  </tr>
  <tr>
    <td>馨客栈</td>
    <td>88888888</td>
    <td>66666666</td>
  </tr>
</table>
```

表格纵向合并

```html
<style>
table, th, td {
  border: 1px solid black;
  border-collapse: collapse;
}
th, td {
  padding: 5px;
  text-align: left;    
}
</style>
<table style="width:100%">
  <caption>这里是表格的标题</caption>
  <tr>
    <th>名字:</th>
    <td>mackxin</td>
  </tr>
  <tr>
    <th rowspan="2">电话:</th>
    <td>55577854</td>
  </tr>
  <tr>
    <td>55577855</td>
  </tr>
</table>
```

## Lists（列表）

无序列表

```css
<ul>
  <li>咖啡</li>
  <li>茶li>
  <li>牛奶</li>
</ul>
<ul style="list-style-type:disc;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<ul style="list-style-type:square;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
<ul style="list-style-type:none;">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ul>
```

有序列表

```css
<ol>
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="1">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="A">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="a">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="I">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="i">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>
<ol type="I" start="50">
  <li>Coffee</li>
  <li>Tea</li>
  <li>Milk</li>
</ol>

```

描述列表

```css
<dl>
  <dt>Coffee</dt>
  <dd>- black hot drink</dd>
  <dt>Milk</dt>
  <dd>- white cold drink</dd>
</dl>
```

## Blocks（块）

块状元素

```html
<address>
<article>
<aside>
<blockquote>
<canvas>
<dd>
<div>
<dl>
<dt>
<fieldset>
<figcaption>
<figure>
<footer>
<form>
<h1>-<h6>
<header>
<hr>
<li>
<main>
<nav>
<noscript>
<ol>
<p>
<pre>
<section>
<table>
<tfoot>
<ul>
<video>
```

行级元素

```
<a> 
<abbr>
<acronym>
<b>
<bdo>
<big>	大号字体
<br>	换行
<button>	按钮
<cite>
<code>	代码块
<dfn>
<em>
<i>	斜体
<img>
<input>
<kbd>
<label>
<map>
<object>
<output>
<q>
<samp>
<script>
<select>
<small>
<span>
<strong>
<sub>
<sup>
<textarea>
```

## Classes

```html
<style>
span.note {
  font-size: 120%;
  color: red;
}
</style>
<p>This is some <span class="note">important</span> text.</p>
```

```html
<style>
.city {
  background-color: tomato;
  color: white;
  padding: 10px;
} 
</style>
<h2 class="city main">London</h2>
<h2 class="city">Paris</h2>
<h2 class="city">Tokyo</h2>
```

## Id

```css
<style>
#xin {
  background-color: lightblue;
  color: black;
  padding: 40px;
  text-align: center;
} 
</style>

<h1 id="xin">Mackxin</h1>
```

## Iframes（框架）

```css
<iframe src="URL"></iframe>
<iframe src="index.html" height="200" width="300"></iframe>
<iframe src="index.html" style="height:200px;width:300px;"></iframe>
<iframe src="index.html" style="border:none;"></iframe>
<iframe src="index.html" style="border:2px solid red;"></iframe>
```

```css
<iframe src="index.html" name="mackxin"></iframe>
<p><a href="https://www.w3schools.com" target="mackxin">mackxin.com</a></p>
```

## Javascript

```javascript
<script>
    document.getElementById('demo').innerHTML = 'Hello Mackxin';
	document.getElementById('demo').style.fontSize = '25px';
	document.getElementById('demo').style.color = 'red';
	document.getElementById('demo').sytle.backgroundColor = 'purple';
	document.getElementById('demo').style.src = 'mackixn.png';
</script>
```

## File Paths（文件路径）

```html
<img src = 'mackxin.png'>
<img src = 'img/mackxin.png'>
<img src = '/img/mackxin.png'>
<img src = '../mackxin.png'>
<img src = 'http://mackxin.com/img/20190329-2.png' alt='mackxin'>
```

## Head（头）

```html
<head>
    <title>Mackxin</title>
    <meta charset='UTF-8'>
    <meta name='description' content='mackxin'>
    <meta name='keywords' content='xininn，馨客栈，导航，分享，情报局'>
    <meta name='author' content='Mackxin'>
    <meta http-equiv='refresh' content='30'><!--每30秒刷新网页-->
    <base href="http://www.mackxin.com/img/" target="_blank">
    <!--这个标签规定了页面中所有相对URL的基本URL和基本目标-->
    <link rel='stylesheet' href='mackxin.css'>
    <style>··· ···</style>
</head>
<body>
   	<img src = 'mackxin.png'>  <!--因为上面base标签设定了，所以这里找的我网站根目录下的img目录下的图片哈-->
</body>
```

## Layout（布局）

> head 定义页面（文档）的头部或标题
>
> nav 定义页面（文档）的导航哈
>
> section 定义页面（文档）的某一块（区域）
>
> article 定义页面（文档）的文章块（区域）
>
> aside 定义页面（文档）的侧边栏
>
> footer 定义页面（文档）的页脚

```html
<style>
* {
  box-sizing: border-box;
}
body {
  font-family: Arial, Helvetica, sans-serif;
}
header {
  background-color: #666;
  padding: 30px;
  text-align: center;
  font-size: 35px;
  color: white;
}
section {
  display: -webkit-flex;
  display: flex;
}
nav {
  -webkit-flex: 1;
  -ms-flex: 1;
  flex: 1;
  background: #ccc;
  padding: 20px;
}
nav ul {
  list-style-type: none;
  padding: 0;
}
article {
  -webkit-flex: 3;
  -ms-flex: 3;
  flex: 3;
  background-color: #f1f1f1;
  padding: 10px;
}
footer {
  background-color: #777;
  padding: 10px;
  text-align: center;
  color: white;
}

@media (max-width: 600px) {
  section {
    -webkit-flex-direction: column;
    flex-direction: column;
  }
}
</style>
<body>
<h2>CSS Layout Flexbox</h2>
<p>In this example, we have created a header, two columns/boxes and a footer. On smaller screens, the columns will stack on top of each other.</p>
<p>Resize the browser window to see the responsive effect.</p>
<p><strong>Note:</strong> Flexbox is not supported in Internet Explorer 10 and earlier versions.
</p>
<header>
  <h2>Cities</h2>
</header>
<section>
  <nav>
    <ul>
      <li><a href="#">London</a></li>
      <li><a href="#">Paris</a></li>
      <li><a href="#">Tokyo</a></li>
    </ul>
  </nav>
  <article>
    <h1>London</h1>
    <p>London is the capital city of England. It is the most populous city in the  United Kingdom, with a metropolitan area of over 13 million inhabitants.		</p>
    <p>Standing on the River Thames, London has been a major settlement for two millennia, its history going back to its founding by the Romans, who named it Londinium.
	</p>
  </article>
</section>
<footer>
  <p>Footer</p>
</footer>
</body>
```

## Responsive（响应）

```html
<meta name='viewport' content='width=device-width, initial-scale=1.0'>
<img src="mackxin.jpg" style="width:100%;">
<img src="mackxin.jpg" style="max-width:100%;height:auto;">
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
  <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
  <source srcset="flowers.jpg">
  <img src="img_smallflower.jpg" alt="Flowers">
</picture>
<h1 style="font-size:10vw">Hello World</h1>
```

Media Queries（媒体查询）

```html
<style>
* {
  box-sizing:border-box;
}
.left {
  background-color:#2196F3;
  padding:20px;
  float:left;
  width:20%;
}
.main {
  background-color:#f1f1f1;
  padding:20px;
  float:left;
  width:60%;
}
.right {
  background-color:#4CAF50;
  padding:20px;
  float:left;
  width:20%;
}
@media screen and (max-width:800px) {
  .left, .main, .right {
    width:100%; 
  }
}
</style>
</head>
<body>
<h2>Media Queries</h2>
<p>Resize the browser window.</p>
<p>Make sure you reach the breakpoint at 800px when resizing this frame.</p>
<div class="left">
  <p>Left Menu</p>
</div>
<div class="main">
  <p>Main Content</p>
</div>
<div class="right">
  <p>Right Content</p>
</div>
</body>
```

## Computercode（计算机代码）

```html
<code>
x = 5;<br>
y = 6;<br>
z = x + y;
</code>
```

键盘输入

```html
<p>Save the document by pressing <kbd>Ctrl + S</kbd></p>
```

程序输出

```html
<p>If you input wrong value, the program will return <samp>Error!</samp></p>
```

代码换行显示

```html
<pre>
<code>
x = 5;
y = 6;
z = x + y;
</code>
</pre>
```

```html
Einstein wrote: <var>E</var> = <var>mc</var><sup>2</sup>
```

## Entities（字符）

| 显示 | 字符代码 |
| :--: | :------: |
|  >   |  \&gt;   |
|  <   |  \&lt;   |
|  &   |  \&amp;  |
|  "   | \&quot;  |
|  '   | \&apos;  |
|  ©   | \&copy;  |
|  ®   |  \&reg;  |

## Symbols（符号）

```html
<p>I will display &euro;</p>
<p>I will display &#8364;</p>
<p>I will display &#x20AC;</p>
```

| 显示 | 符号一   | 符号二    |
| ---- | -------- | --------- |
| ∈    | \&#8712; | \&isin;   |
| ©    | \&#169;  | \&copy;   |
| ®    | \&#174;  | \&reg;    |
| ™    | \&#8482; | \&trade;  |
| ♥    | \&#9829; | \&hearts; |
| ←    | \&#8592; | \&larr;   |

## Charset（字符集）

这里不太细讲了

## URL Encode（译码）

这里也不太细讲

## XHTML

模板

```html
<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN"
"http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <title>Title of document</title>
</head>
<body>
  some content 
</body>
</html>
```

## Forms（表单）

```html
<form action='/action.php' target="_blank">
    名字：<br>
    <input type='text' name='firstname' value='mackxin'><br>
    姓氏：<br>
    <input type='text' name='lastname' value='li'><br>
    <input type='submit' value='提交'>
</form>
```

```html
<input type='text'>
<input type='radio'>
<input type='submit'>
```

```html
<form><!--这个表单只能选一个哈，就是因为加了相同的name属性才行哈-->
  <input type="radio" name="gender" value="male" checked> Male<br>
  <input type="radio" name="gender" value="female"> Female<br>
  <input type="radio" name="gender" value="other"> Other
</form>
```

```html
<!--数据提交时要使用的http方法（get/post）-->
<form action="/action_page.php" method="get">
<form action="/action_page.php" method="post">

```

```html
<form action="/action_page.php">
  <fieldset><!--fieldset元素用于将相关数据分组为一个表单。-->
    <legend>Personal information:</legend>
      <!--legend元素为fieldset元素定义标题-->
    First name:<br>
    <input type="text" name="firstname" value="Mickey">
    <br>
    Last name:<br>
    <input type="text" name="lastname" value="Mouse">
    <br><br>
    <input type="submit" value="Submit">
  </fieldset>
</form>
```

## Form Elements（表单元素）

定义下拉列表

```html
<select name="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

```html
<form action="/action_page.php">
  <select name="cars">
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat" selected>Fiat</option><!--默认选择的是这个，加selected就好了-->
    <option value="audi">Audi</option>
  </select>
  <br><br>
  <input type="submit">
</form>
```

```html
<form action="/action_page.php">
  <select name="cars" size="3"> <!--下拉默认显示3个哈-->
    <option value="volvo">Volvo</option>
    <option value="saab">Saab</option>
    <option value="fiat">Fiat</option>
    <option value="audi">Audi</option>
  </select>
  <br><br>
  <input type="submit">
</form>
```

可以多选的表单

```html
<!--只要加了multiple属性，然后按住键盘上的ctrl键就可以多选了，试一下吧哈-->
<select name="cars" size="4" multiple>
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="fiat">Fiat</option>
  <option value="audi">Audi</option>
</select>
```

自定义多行输入文本区域

```html
<form action="/action_page.php">
  <textarea name="message" rows="10" cols="30">文本区域</textarea>
  <br>
  <input type="submit" value='提交'>
</form>
```

```html
<form action="/action_page.php">
  <textarea name="message" style="width:200px; height:600px;">文本区域</textarea>
  <br>
  <input type="submit">
</form>
```

button按钮

```html
<button type="button" onclick="alert('mackxin')">点击我</button>
```

空白选框，选中显示在选框中哈

```html
<form action="/action_page.php">
  <input list="browsers" name="browser">
  <datalist id="browsers">
    <option value="Internet Explorer">
    <option value="Firefox">
    <option value="Chrome">
    <option value="Opera">
    <option value="Safari">
  </datalist>
  <input type="submit">
</form>
```

```html
<form action="/action_page.php"
oninput="x.value=parseInt(a.value)+parseInt(b.value)">
  0
  <input type="range" id="a" name="a" value="50">
  100 +
  <input type="number" id="b" name="b" value="50">
  =
  <output name="x" for="a b"></output>
  <br><br>
  <input type="submit">
</form>

```

