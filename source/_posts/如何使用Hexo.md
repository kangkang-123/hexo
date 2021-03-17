---
title: 如何使用Hexo
date: 2021-03-15 17:16:20
tags:
---

## Hexo 
是一个快速、简洁且高效的博客框架。Hexo 使用 Markdown（或其他渲染引擎）解析文章，在几秒内，即可利用靓丽的主题生成静态网页。

# 安装 + 启动

- 前提： Node.js + Git
- 安装：全局安装
```bash
npm install -g hexo-cli
进阶安装： 
npm install hexo
``` 

- 创建：
```bash
hexo init <folder>
cd <folder>
npm install
hexo server
```

# 指令
- 新建网站 
```bash
hexo init [folder]
```
- 新建文件 
```bash
hexo new [layout] <title>
```
- 生成静态文件 
```bash
hexo generate
```
- 发表草稿 
```bash
hexo publish [layout] <filename>
```
- 启动服务器 
```bash
hexo server
```