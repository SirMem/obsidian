---
due: 2023-10-19 

title: 根据一个文章模版生成Chatgpt prompt_卡片
tags:
 
- chatgpt 卡片
---
# 🍎重点摘抄
作者：段小草  
链接：https://www.zhihu.com/question/570765297/answer/2956586737  
来源：知乎  
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。  
  

我们首先可以问一下 ChatGPT，如何进行 Prompt 逆向工程，它的回答是：

1. 分析文本内容：首先，我们需要详细阅读和理解给定的文本，以了解其中的主题、观点和表达方式。
2. 提炼关键词：在理解文本内容的基础上，提炼出文本中的关键词或关键短语。这些关键词将有助于我们构建与原文相关的Prompt。
3. 思考可能的问题：根据提炼出的关键词和文本内容，尝试思考可能会引导生成这篇文本的问题。例如，文本可能是回答一个特定问题、解释一个概念或描述一个现象的。
4. 构建多个Prompt：为了提高找到合适Prompt的概率，可以尝试构建多个与文本主题和关键词相关的Prompt。这些Prompt可以包括[开放式问题](https://www.zhihu.com/search?q=%E5%BC%80%E6%94%BE%E5%BC%8F%E9%97%AE%E9%A2%98&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956586737%7D)、是非问题或特定的指令。
5. 检验Prompt：将构建的Prompt与原文进行对比，评估它们是否能够引导生成类似的文本。如果某个Prompt似乎更接近原文的主题和风格，那么它可能是一个更好的选择。
6. 优化和调整：根据对比结果，对已构建的Prompt进行优化和调整，以便更接近原文。如果需要，可以重复这一步骤，直至找到最符合要求的Prompt。

> 请注意，逆向工程并不总是能够找到完全符合原文的Prompt，因为原文可能是在多个Prompt的启发下生成的。然而，这些步骤应该能帮助你找到与原文内容和风格相近的Prompt。


  

想要让 ChatGPT 自己实现 Prompt 逆向工程，我们需要遵循如下步骤（你也可以进一步优化这个过程）：

1、把 ChatGPT 作为一个[逆向工程师](https://www.zhihu.com/search?q=%E9%80%86%E5%90%91%E5%B7%A5%E7%A8%8B%E5%B8%88&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956586737%7D)来培养，可以预置几个步骤来解锁能力/提升效果

> Let's think step by step. Prompt 逆向工程是指通过分析给定的文本，返回可以由ChatGPT生成这些文本的 Prompt。现在，请你给出一个 Prompt 逆向工程的例子。  
> 好的，现在，我们一起思考一下，为了提高生成内容的质量，一个好的Prompt都需要考虑哪些内容？  
> 好的，现在，请给出3条你认为的高质量Prompt

2、给出实际场景中的具体例子，要求 ChatGPT 反写出 Prompt

> 现在，请分析以下文本的角色、风格、语气、长度、段落和emoji使用等特点，给出可以生成这个文本的 Prompt：

3、新建 Chat，验证 Prompt 效果，如果效果不好，可以反复修改，直到满足效果为止

4、要求 ChatGPT 重写 Prompt 成为模板，使其更加通用（可以使用一定的[占位符](https://www.zhihu.com/search?q=%E5%8D%A0%E4%BD%8D%E7%AC%A6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956586737%7D)来做格式化）

> 这个Prompt的效果很棒！现在，请优化这个Prompt，使其适用于更通用的商品推荐场景。你可以在适当的地方插入占位符，以便用户在以后得使用中替换其中的内容。

5、使用 Prompt 模板，提供另一个具体场景，测试其效果，效果不好可以继续修改；效果不错的话，我们就找到了一条适用于某个场景的更为通用的 Prompt

## 模版
内容
现在，请分析以下文本的角色、风格、语气、长度、段落和[emoji](https://www.zhihu.com/search?q=emoji&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956586737%7D)使用等特点，给出可以生成这个文本的 Prompt
这个Prompt的效果很棒！现在，请优化这个Prompt,使其话用于xxx场景。你可以在适当的地方插入占位符，以便用户在以后得使用中替换其中的内容。

# 📒相关文章
https://www.zhihu.com/question/570765297/answer/3212883681



# 🍏引用链接
https://www.zhihu.com/question/570765297/answer/3212883681
