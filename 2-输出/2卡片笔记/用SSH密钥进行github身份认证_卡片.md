---
due: 2023-12-03 

title: 用SSH密钥进行github身份认证_卡片
tags:
 
- git 卡片
---
# 🍎重点摘抄
## 主要内容
1. 生成ssh密钥对
2. 配置github公钥
3. 测试连接
4. 实测


## 创建密钥对
```git
ssh-keygen
or
ssh-keygen -t rsa -C 'git key for github' -f ~/.ssh/id_rsa

//t参数说明加密方式，c参数说明密钥注释，f参数说明存储位置
```
## 配置github公钥
> 登陆github后台，在用户设置中找到 “SSH and GPG keys” → “New SSH key”,输入公钥

## 本地使用git-bash



# 📒相关文章




# 🍏引用链接

