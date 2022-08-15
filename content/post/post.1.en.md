+++
title = 'How to work'
slug = 'post1'
image = 'images/post1/1.jpg'
description = 'how to support nissaya project by computer technology.'
disableComments = true
+++
## Computer Programs Developed for Our Project
## 为项目所开发的程序

我们使用IAPT所开发的[Wikipali](https://www.wikipali.org)三藏电子平台进行工作。该平台可以方便的录入与巴利原文逐句对照的文本。便于以后研究人员查找和使用。nissaya的普遍格式是:“**缅文巴利**,缅文解释。” 

![sample](../../images/sample.jpg)

>这是《经藏-中部》第一本Nissaya的开头一段。可以看出，棕色线标出的是巴利语，而紧随其后的是缅语解释。之间用缅文逗号分隔。

我们对原有的程序进行了补充和修改，以便支持Nissaya的特别的格式。

- 每行一个单词
- 巴利文和缅文之间用 = 分隔
- 将脚注插入到原文正确的位置

虽然录入的时候都是缅文。修改后的程序可以自动将缅文字母拼写的巴利文显示为罗马体。并且可以将缅文表示格位的语尾高亮。增加语尾所代表的格位提示。

![结果](../../images/sample-result.gif)

[该范例的链接](https://www-hk.wikipali.org/app/article/index.php?view=chapter&book=165&par=5&channel=a73e1d78-9666-4cb2-b909-f235aa3362e5&display=sent&mode=edit&direction=col)

## Managament of Project
## 项目管理

Github的*Project*已经被用于软件项目的管理。我们发现，这个工具的看板(Broad)和带有状态的列表合适作为本项目的管理工具。

[项目管理页面](https://github.com/orgs/iapt-platform/projects/6/views/1)

### 状态

1. **Blocking**(冻结) 暂时不录入的文本。不录入的原因是该书有多个版本，我们通常选择专业认识推荐的最佳版本或者印刷比较清晰的版本。在这个方面U Tejanandālaṇkala给予我们很大的帮助。指导我们选择适当的版本。他已经获得dhammācariya头衔。
2. **Difficulty**(困难) 书的印刷质量(或PDF)较差。部分文字缺失笔画到无法辨识的程度。
3. Medium(中等)印刷(或PDF)质量一般。能够辨识，但是有些字母容易辨识错误。
4. **Paperbook-Clear**(纸版书清楚)纸版书印刷清楚。容易录入
5. **PDF Clear**(PDF文件清晰)PDF文件清晰。优先录入。
6. **In Progress**(进行中)正在录入。可以通过详情页面查看录入进度和已经录入的文本。
7. **Done**(初稿完成) 等待校对。

### 标签

值得一提的是有很多书有多个版本。为了区分，使用了开头为"ver:"的标签区分。

### 进度

每个书的详情页面包含录入进度的统计图。统计图由wikiapli服务器统计生成。进度是以页计算。

![统计图](images/github-1.gif)

## Cataloguing 
## 分类与编号

主要参考Masoyin e-Libaray 的收藏进行编号。
一位字母+数字

- p = pali
- a = atthakatha
- t = tika

如 [a-010]


## The Importance of Digitizing Texts
## 数字化文本的重要意义

- 便于复制和传播：可以方便复制到电子邮件，博客甚至是即时通讯软件。
- 修订容易：发现错误不必等待下一次印刷。容易进行迭代升级。即使是原来的纸质书也会有些许错误。只是以纸质版本流通，更正这些错误成本很高。
- 计算机搜索：全部的nissaya文本将超过10万页。计算机查找讲使得研究工作变得更容易。
- 大数据统计：通过计算机处理后将容易的获得诸如某个单词的不同解释在三藏中的分布等信息。

