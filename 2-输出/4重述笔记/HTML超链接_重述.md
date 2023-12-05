---
due: 2023-12-04 

title: HTML超链接_重述
tags:
 
- html 重述
---


> [!summary]+ summary
> 说明html超链接的参数


# 🤔问题:





# 🤔相关联:
[[HtmlMOC]]



# 📘自我重述
## 定义
HTML超链接（Hyperlink）是一种在网页中创建链接到其他网页、文件、位置或资源的元素。超链接可用于使用户在网页之间进行导航，点击超链接可以跳转到其他页面、同一页面内的不同位置、下载文件或者发送电子邮件等操作。
在HTML中，使用`<a>`标签来创建超链接。

## `<a>`的用法以及基本参数
`<a>` 标签是用于创建超链接的 HTML 元素，它有一些常用的属性，以下是其中一些主要的属性：

1. `href`：必需的属性，用于指定链接的目标地址。可以是 URL、文件路径、电子邮件地址等。示例：`<a href="https://www.example.com">Link Text</a>`

2. `target`：可选属性，用于指定链接如何打开。常用取值包括：
   - `_self`：在当前窗口打开链接（默认行为）。
   - `_blank`：在新窗口或新标签页中打开链接。
   - `_parent`：在父框架中打开链接。
   - `_top`：在整个窗口中打开链接。
   
   示例：`<a href="https://www.example.com" target="_blank">Link Text</a>`

3. `rel`：可选属性，定义链接与目标之间的关系。常用取值包括：
   - `nofollow`：指示搜索引擎不要追踪链接。用于告知搜索引擎不要传递权重。
   - `noopener`：防止打开链接的页面对新页面的引用，提高安全性。
   - `noreferrer`：防止浏览器发送HTTP头部信息，也是一种安全性考虑。
   
   示例：`<a href="https://www.example.com" rel="nofollow noopener">Link Text</a>`

4. `title`：可选属性，提供关于链接的额外信息，通常会在用户将鼠标悬停在链接上时显示为工具提示。
   
   示例：`<a href="https://www.example.com" title="Visit Example">Link Text</a>`

这些属性可以根据需要在`<a>`标签中进行组合使用，以创建具有不同行为和属性的超链接。




# 💻代码区