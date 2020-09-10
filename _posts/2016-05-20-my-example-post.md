---
layout: page
title:  "搭建个人技术博客"
subtitle: "A longer explanation of stuff"
date:   2016-05-20 21:21:21 +0530
categories: ["学习笔记"]
---

> 使用GitHub Pages + Jekyll 快速部署个人博客

> - GitHub Pages
>   - 定义：给所有的git用户提供的个人主页
>   - 如何访问:个人域名 用户名.github.io
>   - 如何编写主页: 建立一个用个人域名为项目名的远程版本仓库，只需要向该远程版本仓库中的master分支提交代码即可
> - Jekyll
>   - 定义：可以将markdown语法自动编译成html语法的一个工具
>   - 安装：不需要自己安装，在github网站当中预安装的
>   - 使用：当你请求你的个人域名的时候，github服务器会读取仓库（以个人域名命名的那个远程版本仓库）中的markdown分支中的代码，如果该代码为markdown语法会自动调用jekyll将其编译为html代码并返回客户端
