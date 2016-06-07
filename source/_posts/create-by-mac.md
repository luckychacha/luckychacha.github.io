---
title: create-by-mac
date: 2016-06-07 20:53:56
tags:
- hexo
- mac
- Git

categories:
- 安装方法
---
# 关于在mac下安装hexo之后，使用hexo相关命令报错，如运行 `hexo server` 之后报错，可以运行以下命令

```shell
npm uninstall hexo
npm install hexo --no-optional
npm uninstall hexo-cli -g
npm install hexo-cli -g
```
之后重新启动就可以了。
