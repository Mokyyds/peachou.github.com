---
layout: post
title: 如何搭建一个独立博客——Github Pages教程
category: Web
date: 2015-12-04
---

这是一篇很详尽的独立博客搭建教程，我将我搭建独立博客的过程在这里尽可能详细的写出来，希望能给后来者一个明确的指引。你可以从中掌握github的Pages功能，以及Jekyll软件的基本用法。更重要的是，你会体会到一种建立网站的全新思路。

<!-- more -->

##Github Pages是什么？##
　　如果你对编程有所了解，就一定听说过github。它号称程序员的Facebook，有着极高的人气，许多重要的项目都托管在上面。简单说，它是一个具有版本管理功能的代码仓库，每个项目都有一个主页，列出项目的源文件。
	![otto design diagram](http://ww1.sinaimg.cn/mw690/a0031a9fjw1eynm407imoj20i30f0gme.jpg)
　　但是对于一个新手来说，看到一大堆源码，只会让人头晕脑涨，不知何处入手。他希望看到的是，一个简明易懂的网页，说明每一步应该怎么做。因此，github就设计了Pages功能，允许用户自定义项目首页，用来替代默认的源码列表。所以，github Pages可以被认为是用户编写的、托管在github上的静态网页。
　　	![otto design diagram](http://ww3.sinaimg.cn/mw690/a0031a9fjw1eynm3dh2bcj20o40i8jun.jpg)
　　github提供模板，允许站内生成网页，但也允许用户自己编写网页，然后上传。有意思的是，这种上传并不是单纯的上传，而是会经过Jekyll程序的再处理。
##Jekyll是什么？##
　　Jekyll（发音/'dʒiːk əl/，"杰克尔"）是一个静态站点生成器，它会根据网页源码生成静态文件。它提供了模板、变量、插件等功能，所以实际上可以用来编写整个网站。
　　	![otto design diagram](http://ww4.sinaimg.cn/mw690/a0031a9fjw1eynm3z9r6yj20hj0abjrm.jpg)
　　整个思路到这里就很明显了。你先在本地编写符合Jekyll规范的网站源码，然后上传到github，由github生成并托管整个网站。
##正式开始##

好了，概念性的东西说了这么多，下面我们就来动手操作一下吧~   

- 1.首先你需要注册一个GitHub的帐号。  
- 2.创建一个username.github.io的project，注意要勾选生成README。
　　	![otto design diagram](http://ww3.sinaimg.cn/mw690/a0031a9fjw1eynm3emtexj20lh0gd754.jpg)

- 3.设置站点主题

---进入资源-setting
　　	![otto design diagram](http://ww4.sinaimg.cn/mw690/a0031a9fjw1eynm3g4bhuj20s203yjrj.jpg)
---更新你的站点
　　	![otto design diagram](http://ww2.sinaimg.cn/mw690/a0031a9fjw1eynm3gx0i4j20ld090glw.jpg)
---选择主题并发布
　　	![otto design diagram](http://ww2.sinaimg.cn/mw690/a0031a9fjw1eyngkpj1e8j20of0b20tt.jpg)




> 未完待续
<br/>

- - -
*本文出自[peach](/)，扫描以下二维码即可关注订阅号。*
![Jekyll](/res/img/two.jpg)