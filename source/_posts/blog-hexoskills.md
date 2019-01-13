---
title: 开启手机端hexo博客遇到的坑
date: 2019-01-11 05:37:02
tags: 
- Diary
- fun
categories:
- Diary
---
使用华为p10 termux 完全手机端建站 遇到一个问题卡了我一天 
npm install -g hexo-cli 
总是报错  
npm ERR! Cannot read property 'length' of undefined
后来百度半天一直没解决
最后终于发现是 nodejs 安装的有问题

<!--more-->

pkg install nodejs 安装的是最新版本
果断使用
pkg install nodejs-lts 这个是 稳定版本   
使用此行代码是 卸载最新版 安装稳定版本 nodejs 
之后 npm install -g hexo-cli 成功 
这是成功后的手机端 termux vim 编辑的 第一篇博客 
一起来嗨哟  

20190113 天气 晴 

前一天公司年会  

题外话

前两个月一直在学习 廖大神的 python 自学到实战部分懵逼了
质的跨越 可是我资质薄弱 跨不过去呀  迷茫了一段时间 又跟着学爬虫 发现 python 真好玩 可是一直以来想搭建一些自己的网站 我用的是 github 建站全免费  试试手 如果后来技术熟练了  有必要就买个域名 服务器 建站  
