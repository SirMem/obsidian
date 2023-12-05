---
due: 2023-12-04 

title: html的结构解析_重述
tags:
 
- html 重述
---


> [!summary]+ summary
> 简要说明了html的基本结构


# 🤔问题:





# 🤔相关联:
[[HtmlMOC]]



# 📘自我重述
## HTML简介
HTML 是用来描述网页的一种语言。
- HTML 指的是超文本标记语言: **H**yper**T**ext **M**arkup **L**anguage
- HTML 不是一种编程语言，而是一种**标记**语言
- 标记语言是一套**标记标签** (markup tag)
- HTML 使用标记标签来**描述**网页
- HTML 文档包含了HTML **标签**及**文本**内容
- HTML文档也叫做 **web 页面**

## HTML的基本结构
![](https://www.runoob.com/wp-content/uploads/2013/06/02A7DD95-22B4-4FB9-B994-DDB5393F7F03.jpg)
```html
<html>
	<head>
		<title>页面标题</title>
	</head>
	<body>
		<h1>这是一个标题</h1>
		<p>这是一个段落。</p>
		<p>这是另外一个段落。</p>
	</body>
</html>
```

## <!doctype>声明
<!DOCTYPE>声明有助于浏览器中正确显示网页。
网络上有很多不同的文件，如果能够正确声明HTML的版本，浏览器就能正确显示网页内容。
# 💻代码区