# HTMLCSSSample
![html5css3](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1495797215189&di=041a6d50f496dae65a7eff39317f84da&imgtype=0&src=http%3A%2F%2Fwww.youjoys.com%2Fuploads%2Fallimg%2F141110%2F0151403062-1.jpg)

---

重新学习HTML5和CSS3的代码示例

1.   `<!--...-->	`定义注释。
     * __定义和用法__
        ```html
        <script type="text/javascript">
        <!--
        function displayMsg()
        {
            alert("Hello World!")
        }
        //-->
        </script>
        ```
     * __属性__  
        无
     * __事件__  
        无
2.   `<!DOCTYPE> 	`定义文档类型。
     * __定义和用法__    
     声明必须在HTML文档第一行，位于`<html>`标签之前  
     声明不是HTML标签
     * __HTML 元素和文档类型（Doctype）__  
     [元素和文档类型对照表](http://www.w3school.com.cn/tags/html_ref_dtd.asp)  
     * __提示和注释__  
     声明没有结束标签
     对大小写不敏感
     * __常用的 DOCTYPE 声明__   
        * __HTML 5__       
        ```html
        <!DOCTYPE html>
        ```
        * __HTML 4.01 Strict__        
        该 DTD 包含所有 HTML 元素和属性，但不包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。
        ```html
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01//EN" "http://www.w3.org/TR/html4/strict.dtd">
        ```
        * __HTML 4.01 Transitional__  
        该 DTD 包含所有 HTML 元素和属性，包括展示性的和弃用的元素（比如 font）。不允许框架集（Framesets）。  
        ```html
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
        ``` 
        * __HTML 4.01 Frameset__  
        该 DTD 等同于 HTML 4.01 Transitional，但允许框架集内容。  
        ```html
        <!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Frameset//EN" "http://www.w3.org/TR/html4/frameset.dtd">
        ```
        * __XHTML 1.x+ 请参照[w3chool](http://www.w3school.com.cn/tags/tag_doctype.asp)该项文档__


3.   `<a>			`定义锚。
     * __定义和用法__  
     ```html
     <a href="http://www.w3school.com.cn">W3School</a>
     ```
     最重要的属性是 href 属性，它指示链接的目标。    
     在所有浏览器中，链接的默认外观是：  
        * 未被访问的链接带有下划线而且是蓝色的  
        * 已被访问的链接带有下划线而且是紫色的   
        * 活动链接带有下划线而且是红色的
4.   `<abbr>		`定义缩写。
5.   `<acronym>		`定义只取首字母的缩写。
6.   `<address>		`定义文档作者或拥有者的联系信息。
7.   `<applet>		`不赞成使用。定义嵌入的 applet。
8.   `<area>		`定义图像映射内部的区域。
9.   `<article>		`定义文章。
10.  `<aside>		`定义页面内容之外的内容。
11.  `<audio>		`定义声音内容。
12.  `<b>			`定义粗体字。
13.  `<base>		`定义页面中所有链接的默认地址或默认目标。
14.  `<basefont>	`不赞成使用。定义页面中文本的默认字体、颜色或尺寸。
15.  `<bdi>			`定义文本的文本方向，使其脱离其周围文本的方向设置。
16.  `<bdo>			`定义文字方向。
17.  `<big>			`定义大号文本。
18.  `<blockquote>	`定义长的引用。
19.  `<body>		`定义文档的主体。
20.  `<br>			`定义简单的折行。
21.  `<button>		`定义按钮 (push button)。
22.  `<canvas>		`定义图形。
23.  `<caption>		`定义表格标题。
24.  `<center>		`不赞成使用。定义居中文本。
25.  `<cite>		`定义引用(citation)。
26.  `<code>		`定义计算机代码文本。
27.  `<col>			`定义表格中一个或多个列的属性值。
28.  `<colgroup>	`定义表格中供格式化的列组。
29.  `<command>		`定义命令按钮。
30.  `<datalist>	`定义下拉列表。
31.  `<dd>			`定义定义列表中项目的描述。
32.  `<del>			`定义被删除文本。
33.  `<details>		`定义元素的细节。
34.  `<dir>			`不赞成使用。定义目录列表。
35.  `<div>			`定义文档中的节。
36.  `<dfn>			`定义定义项目。
37.  `<dialog>		`定义对话框或窗口。
38.  `<dl>			`定义定义列表。
39.  `<dt>			`定义定义列表中的项目。
40.  `<em>			`定义强调文本。
41.  `<embed>		`定义外部交互内容或插件。
42.  `<fieldset>	`定义围绕表单中元素的边框。
43.  `<figcaption>	`定义 figure 元素的标题。
44.  `<figure>		`定义媒介内容的分组，以及它们的标题。
45.  `<font>		`不赞成使用。定义文字的字体、尺寸和颜色。
46.  `<footer>		`定义 section 或 page 的页脚。
47.  `<form>		`定义供用户输入的 HTML 表单。
48.  `<frame>		`定义框架集的窗口或框架。
49.  `<frameset>	`定义框架集。
50.  `<h1> to <h6>	`定义 HTML 标题。
51.  `<head>		`定义关于文档的信息。
52.  `<header>		`定义 section 或 page 的页眉。
53.  `<hr>			`定义水平线。
54.  `<html>		`定义 HTML 文档。
55.  `<i>			`定义斜体字。
56.  `<iframe>		`定义内联框架。
57.  `<img>			`定义图像。
58.  `<input>		`定义输入控件。
59.  `<ins>			`定义被插入文本。
60.  `<isindex>		`不赞成使用。定义与文档相关的可搜索索引。
61.  `<kbd>			`定义键盘文本。
62.  `<keygen>		`定义生成密钥。
63.  `<label>		`定义 input 元素的标注。
64.  `<legend>		`定义 fieldset 元素的标题。
65.  `2<li>			`定义列表的项目。
66.  `<link>		`定义文档与外部资源的关系。
67.  `<map>			`定义图像映射。
68.  `<mark>		`定义有记号的文本。
69.  `<menu>		`定义命令的列表或菜单。
70.  `<menuitem>	`定义用户可以从弹出菜单调用的命令/菜单项目。
71.  `<meta>		`定义关于 HTML 文档的元信息。
72.  `<meter>		`定义预定义范围内的度量。
73.  `<nav>			`定义导航链接。
74.  `<noframes>	`定义针对不支持框架的用户的替代内容。
75.  `<noscript>	`定义针对不支持客户端脚本的用户的替代内容。
76.  `<object>		`定义内嵌对象。
77.  `<ol>			`定义有序列表。
78.  `<optgroup>	`定义选择列表中相关选项的组合。
79.  `<option>		`定义选择列表中的选项。
80.  `<output>		`定义输出的一些类型。
81.  `<p>			`定义段落。
82.  `<param>		`定义对象的参数。
83.  `<pre>			`定义预格式文本。
84.  `<progress>	`定义任何类型的任务的进度。
85.  `<q>			`定义短的引用。
86.  `<rp>			`定义若浏览器不支持 ruby 元素显示的内容。
87.  `<rt>			`定义 ruby 注释的解释。
88.  `<ruby>		`定义 ruby 注释。
89.  `<s>			`不赞成使用。定义加删除线的文本。
90.  `<samp>		`定义计算机代码样本。
91.  `<script>		`定义客户端脚本。
92.  `<section>		`定义 section。
93.  `<select>		`定义选择列表（下拉列表）。
94.  `<small>		`定义小号文本。
95.  `<source>		`定义媒介源。
96.  `<span>		`定义文档中的节。
97.  `<strike>		`不赞成使用。定义加删除线文本。
98.  `<strong>		`定义强调文本。
99.  `<style>		`定义文档的样式信息。
100. `<sub>			`定义下标文本。
101. `<summary>		`为 `<details>` 元素定义可见的标题。
102. `<sup>			`定义上标文本。
103. `<table>		`定义表格。
104. `<tbody>		`定义表格中的主体内容。
105. `<td>			`定义表格中的单元。
106. `<textarea>	`定义多行的文本输入控件。
107. `<tfoot>		`定义表格中的表注内容（脚注）。
108. `<th>			`定义表格中的表头单元格。
109. `<thead>		`定义表格中的表头内容。
110. `<time>		`定义日期/时间。
111. `<title>		`定义文档的标题。
112. `<tr>			`定义表格中的行。
113. `<track>		`定义用在媒体播放器中的文本轨道。
114. `<tt>			`定义打字机文本。
115. `<u>			`不赞成使用。定义下划线文本。
116. `<ul>			`定义无序列表。
117. `<var>			`定义文本的变量部分。
118. `<video>		`定义视频。
119. `<wbr>			`定义可能的换行符。
120. `<xmp>			`不赞成使用。定义预格式文本。
