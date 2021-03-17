---
title: Hexo指令
date: 2021-03-17 15:38:20
tags:
---
# 指令
新建网站
```
hexo init [folder]
```
新建文件
```
hexo new [layout] <title>
```
生成静态文件
```
hexo generate
```
发表草稿
```
hexo publish [layout] <filename>
```
启动服务器
```
hexo server
```
部署网站
```
hexo depoly
```
渲染文件
```
hexo render <file1>[file2]...
```
从其他博客系统迁移内容
```
hexo migrate
```
清楚缓存文件和已生成的静态文件
```
hexo clean
```
列出网站资料
```
hexo list
```
显示hexo版本
```
hexo version
```
## 选项
安全模式
```
hexo --safe
```
调试模式
```
hexo --debug
```
简洁模式
```
hexo --silent
```
自定义配置文件的路径
```
hexo server --config custom.yml
hexo generate --config custom.yml,custom2.json...
```
显示草稿
```
hexo --draft
```
自定义CWD(current working directory)
```
hexo --cwd /path/to/cwd
```