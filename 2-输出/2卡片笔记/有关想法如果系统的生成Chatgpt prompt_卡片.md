---
due: 2023-10-19 

title: 有关想法如果系统的生成Chatgpt prompt_卡片
tags:
 
- Chatgpt 卡片
---
# 🍎重点摘抄
因为在这众多用途的prompt中，**有一类被称为Prompt Creator（[指令生成器](https://www.zhihu.com/search?q=%E6%8C%87%E4%BB%A4%E7%94%9F%E6%88%90%E5%99%A8&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)）的，即让ChatGPT帮助完成/改善你的prompt的prompt。**

主要的思路是首先让用户简要的描述一下需求，然后通过“ChatGPT提问-用户回答”的方式把需求具体化和[私人定制](https://www.zhihu.com/search?q=%E7%A7%81%E4%BA%BA%E5%AE%9A%E5%88%B6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)化，从而一步一步创建一个专业的、需求明确的prompt。

它比较适合这样的情况：**你想让ChatGPT帮你完成一个（相对复杂的）[任务](https://www.zhihu.com/search?q=%E4%BB%BB%E5%8A%A1&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)，但是你却表达不清楚需求，也没想好都应该考虑哪些方面；或者是你欠缺关于完成这个任务所涉及的专业知识。**

这种情况下通过多轮的问答形式能帮助你把关于这个任务的方方面面都考虑进去，然后创建一个更具体、明确的prompt，从而让ChatGPT生成更好的答案。

上面这个prompt的用途是让ChatGPT扮演一个提示生成器。ChatGPT具体完成这样几件事：

- 用户首先告诉chatgpt想要它完成什么任务，然后ChatGPT根据用户的描述生成一个指令明确的prompt；
- 接着对生成的prompt做个点评，并指出可以从什么方面改进；
- 向用户提问题，获得更多的信息以改进prompt；
- 用户根据需要选择回答问题与否，然后ChatGPT根据用户的回答生成一个改进后的prompt。

重复上述步骤直到获得满意的prompt。

## 举个例子。

> I want you to become my Expert Prompt Creator. Your goal is to help me craft the best possible prompt for my needs. The prompt you provide should be written from the perspective of me making the request to ChatGPT. Consider in your prompt creation that this prompt will be entered into an interface for ChatGPT. The process is as follows:  
> 1. You will generate the following sections:  
>   
> Prompt:  
> {provide the best possible prompt according to my request}  
>   
> Critique:  
> {provide a concise paragraph on how to improve the prompt. Be very critical in your [response](https://www.zhihu.com/search?q=response&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)}  
>   
> Questions:  
> {ask any questions pertaining to what additional information is needed from me to improve the prompt (max of 3). If the prompt needs more clarification or details in certain areas, ask questions to get more information to include in the prompt}  
>   
> 2. I will provide my answers to your response which you will then incorporate into your next response using the same format. We will continue this iterative process with me providing additional information to you and you updating the prompt until the prompt is perfected.  
> Remember, the prompt we are creating should be written from the perspective of me making a request to ChatGPT. Think carefully and use your imagination to create an amazing prompt for me.  
>   
> You're first response should only be a greeting to the user and to ask what the prompt should be about.


## 模版
### 1
I want you to become my Expert Prompt Creator. Your goal is to help me craft the best possible prompt for my needs. The prompt you provide should be written from the perspective of me making the request to ChatGPT. Consider in your prompt creation that this prompt will be entered into an interface for ChatGPT. The process is as follows:
1. You will generate the following sections:

Prompt:
{provide the best possible prompt according to my request}

Critique:
{provide a concise paragraph on how to improve the prompt. Be very critical in your response}

Questions:
{ask any questions pertaining to what additional information is needed from me to improve the prompt (max of 3). If the prompt needs more clarification or details in certain areas, ask questions to get more information to include in the prompt}

2. I will provide my answers to your response which you will then incorporate into your next response using the same format. We will continue this iterative process with me providing additional information to you and you updating the prompt until the prompt is perfected.
Remember, the prompt we are creating should be written from the perspective of me making a request to ChatGPT. 
Please use Chinese to express.

### 2
I want you to become my Prompt Creator. Your goal is to help me craft the best possible prompt for my needs. The prompt will be used by you, ChatGPT. You will follow the following process:
1. Your first response will be to ask me what the prompt should be about. I will provide my answer, but we will need to improve it through continual iterations by going through the next steps.
2. Based on my input, you will generate 3 sections.
a) Revised prompt (provide your rewritten prompt. it should be clear, concise, and easily understood by you),
b) Suggestions (provide suggestions on what details to include in the prompt to improve it), and
c) Questions (ask any relevant questions pertaining to what additional information is needed from me to improve the prompt).
3. We will continue this iterative process with me providing additional information to you and you updating the prompt in the Revised prompt section until it's complete. 
Please use Chinese to express.

### 一个演示

为了方便阅读，我在这个prompt最后加上了一句(Response me in Chinese)，这样就可以直接用中文和ChatGPT交流了（如果大家想使用，我建议还是使用英文）。

比如，

1、我有个想法：“想让ChatGPT帮我用python写一个实现计算器程序”，但我不知道实现这个任务还需要考虑哪些具体方面，所以我先把需求简单描述给ChatGPT。

![](https://picx.zhimg.com/80/v2-d58525c5a38f73aaef051f3b76566100_720w.webp?source=2c26e567)

2，ChatGPT首先根据我的描述生成了一个初版的prompt，然后根据它的理解，对这个prompt提出了一些可能改进的方面，比如说我“没有提供任何关于[界面设计](https://www.zhihu.com/search?q=%E7%95%8C%E9%9D%A2%E8%AE%BE%E8%AE%A1&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)或其他特定功能的要求”。然后在接下来的问题中询问是否需要考虑这些功能。

接着我回答它提出的问题，它根据我提供的信息，再次生成一个改进版的prompt。

![](https://picx.zhimg.com/80/v2-e121cab8183e10ca2527dd3780456101_720w.webp?source=2c26e567)

3，同样的，ChatGPT还会再次点评和提问，我也可以根据需要选择是否继续，直至满意为止。

4，最后测试一下这个prompt。

![](https://pica.zhimg.com/80/v2-b217d47d158194036bdd15441a78417a_720w.webp?source=2c26e567)

效果还不错。

总结一下就是当我的脑中对于一个问题没有太多的概念时，ChatGPT能帮助我提出更多的问题，考虑的更周全，这个过程除了帮助我创建了一个prompt，还相当于领着我梳理一遍思路。

# 📒相关文章
因为在这众多用途的prompt中，**有一类被称为Prompt Creator（[指令生成器](https://www.zhihu.com/search?q=%E6%8C%87%E4%BB%A4%E7%94%9F%E6%88%90%E5%99%A8&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)）的，即让ChatGPT帮助完成/改善你的prompt的prompt。**

主要的思路是首先让用户简要的描述一下需求，然后通过“ChatGPT提问-用户回答”的方式把需求具体化和[私人定制](https://www.zhihu.com/search?q=%E7%A7%81%E4%BA%BA%E5%AE%9A%E5%88%B6&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)化，从而一步一步创建一个专业的、需求明确的prompt。

它比较适合这样的情况：**你想让ChatGPT帮你完成一个（相对复杂的）[任务](https://www.zhihu.com/search?q=%E4%BB%BB%E5%8A%A1&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra=%7B%22sourceType%22%3A%22answer%22%2C%22sourceId%22%3A2956335225%7D)，但是你却表达不清楚需求，也没想好都应该考虑哪些方面；或者是你欠缺关于完成这个任务所涉及的专业知识。**

这种情况下通过多轮的问答形式能帮助你把关于这个任务的方方面面都考虑进去，然后创建一个更具体、明确的prompt，从而让ChatGPT生成更好的答案。


# 🍏引用链接
https://www.zhihu.com/question/584402332/answer/2956335225
