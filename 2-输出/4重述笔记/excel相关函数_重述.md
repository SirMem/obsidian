---
due: 2023-12-18 

title: excel相关函数_重述
tags:
 
- excel
---


> [!summary]+ summary
> 对excel的相关函数进行了总结


# 🤔问题:





# 🤔相关联:




# 📘自我重述
## 清洗类
### left
- Left函数是一个字符串函数，返回具有指定长度的字符串左边部分
- 使用:=Left(文本单元格，字符串长度)

### right
- 与Left函数类似，但返回具有指定长度的字符串右边部分
- 使用:=right(文本单元格,字符串长度)
### mid
- 从指定位置开始，提取用户指定的字符数
- 使用:=mid(文本单元格，起始位置(start_num),字符串长度)
### len
- 返回文本字符串中的字符数
- 使用:Len(文本单元格)
### lenb
- 与len类似，但是中文字符返回两个字节，英文字符返回一个字节
- 使用:Lenb(文本单元格)
### concatenate
- 将多个字符文本或单元格中的数据连接在一起，显示在一个单元格中
- 使用:=concatenate(text1,text2,…)
### text
- 按指定格式讲数值转为文本格式
- 使用:=text(文本单元格(value),value设置格式)
### trim
- 将单元格内容前后的空格去掉，但并不去除字符之间的空格
- 使用:=trim(文本单元格)
### replace
- 将一个字符串中的部分字符用另一个字符串替换
- 使用:=replace(旧文本单元格,起始位置，起始位置后字符的替换数量，新内容)
### substitute
- 对指定的字符串进行替换
- 使用:=substitute(被替换文本单元格，文本单元格内容，新内容，重复替换次数)
### find
- 查找一个字符串在另一个字符串中的位置，区分大小写
- 使用:=Find(查找内容，文本单元格，起始位置)
### search
- 查找一个字符串在另一个字符串中的位置，不区分大小写
- 使用:=Find(查找内容，文本单元格，起始位置)
## 时间类函数
### today
### date
### eomonth
### year
### month
### day
### weekday
### weeknum
## 逻辑类函数
if
and
or
iserror
iferror
true
false
## 关联匹配类
vlookup
hlookup
lookup
index
match
offset
row
column

## 计算统计类
count
counta
countif
countblank
countifs
sum
sumif
sumifs
sumproduct
max
min
average
mod
rank
round
floor
rand
int
randbetween





