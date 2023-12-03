---
due: 2023-11-28 

title: git_卡片
tags:
 
- 计算机 卡片
---
# 🍎重点摘抄
## 跟踪
git add 
git rm –cache

## 暂存
git reset HEAD <>

## 提交
git commit –m “注释”

## 状态
git status
git status –list
## 查询状态
git diff

## 查询提交
git log
–pretty
格式化 
%h 简化哈希值
%an作者名字
%ar修订日期(距今)
%ad修订日期
%s提交说明
gragh  图形化
## 仓库回溯
git commit –m 哈希值

## github(托管平台)
git remote  对github仓库进行链接

git push 远程仓库 本地分支 
对远程仓库进行推送

### 令牌
将分支推送到远程仓库需要登录，登录需要令牌。在github setting developer settings Tokens获取令牌

### SSH协议

## 提交对象
### 提交
在 Git 中，提交（commit）是指将代码库中的更改保存为一个新的版本，并记录了这些更改的详细信息。每次提交会生成一个提交对象（commit object），它包含了一组文件变更的快照、作者信息、提交时间、提交信息等元数据。

提交在版本控制中扮演着重要的角色，它允许开发者在代码库中创建历史记录，并跟踪代码的演变过程。通过提交，你可以记录项目中的每个重要更改，包括但不限于新功能的添加、bug修复、代码重构等。

每次提交都包括以下关键信息：

1. **文件快照（Snapshot of Changes）：** 提交记录了在提交时所有文件的状态快照，包括了被修改、添加或删除的文件内容。

2. **作者和提交者信息（Author and Committer Information）：** 包括了提交的作者信息（谁做了这些更改）和提交者信息（谁进行了提交操作），通常包括姓名、邮箱地址和时间戳等。

3. **提交信息（Commit Message）：** 是提交时作者提供的一段描述性文本，通常简要描述了所做更改的内容，以便其他开发者能够理解这个提交的目的和变更。

4. **父提交引用（Parent Commit Reference）：** 除了第一个提交（根提交）外，每个提交都指向一个或多个父提交。这种结构形成了一个有向无环图（DAG），展示了项目历史的分支和合并情况。

提交对象的唯一标识符是其哈希值（SHA-1哈希），通过这个哈希值可以唯一标识和引用一个特定的提交。提交允许开发者追踪项目的发展历程、管理版本、进行合并和回滚操作等。

总的来说，提交在 Git 中代表了一次代码更改的保存点，它记录了项目在某个时间点上的状态，并允许开发者回溯查看代码库的演变历史。
### 提交对象
在 Git 中，以下操作会创建提交对象（commit object）：

1. **git commit：** 最常见的方式是使用 `git commit` 命令创建提交对象。在使用该命令时，你需要提交你所做的更改，Git 会将这些更改记录为一个新的提交对象，并将其添加到版本历史中。

    ```bash
    git add <file(s)>
    git commit -m "Commit message describing changes"
    ```

2. **git merge：** 当你执行分支合并操作（比如将一个分支合并到另一个分支时），Git 会生成一个新的合并提交对象。这个提交对象将合并的两个分支的内容合并起来，并记录下这个合并操作的信息。

    ```bash
    git merge <branch-name>
    ```

3. **git rebase：** 在进行分支重写时，使用 `git rebase` 将提交对象重新应用到另一个基础提交上，会创建新的提交对象，形成一个新的提交历史。

    ```bash
    git rebase <base-branch>
    ```

4. **git cherry-pick：** 使用 `git cherry-pick` 命令选择性地将指定提交对象的更改应用到当前分支中，这也会产生新的提交对象。

    ```bash
    git cherry-pick <commit-hash>
    ```

5. **git commit --amend：** 如果你在上一次提交后发现需要修改提交信息或者添加额外的更改，使用 `git commit --amend` 会创建一个新的提交对象来替代上一次的提交。

    ```bash
    git add <file(s)>
    git commit --amend -m "New commit message"
    ```

6. **git revert：** 用于撤销一个已有的提交，它会创建一个新的提交来反转某个特定提交的更改，而不会直接修改历史记录。

    ```bash
    git revert <commit-hash>
    ```

以上这些操作会在版本控制历史中创建新的提交对象，记录项目在不同时间点的状态和更改，帮助你追踪和管理代码的演进过程。

## 分支
跟踪整个代码库中文件的状态和历史
对象:具有哈希值
提交对象
分支是包含一个哈希值文件
指向一个==提交对象==的指针
### 操作分支
创建分支 git branch name
查询分支 git branch –list
切换分支 git checkout name或者git switch name
合并分支 git merge

## 推送
git push
# 📒相关文章
checkout reset head


# 🍏引用链接

```git
(HEAD -> master,origin/master远端仓库的分支master)
```