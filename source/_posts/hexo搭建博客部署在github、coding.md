---
title: 'hexo搭建博客部署在github、coding'
date: 2017-05-16 13:23:23
tags: 'hexo'
categories: 'hexo'
---
## 查看本地ssh ##
```
cd .ssh
```
### 复制ssh粘贴到GitHub和coding的ssh公钥处 ###

## 问题 ##

** 如果是github新建仓库,执行下面命令创建版本控制
```
git init
```

### 两个链接后面 一定要有' ; ' ###
```
deploy:
  type: git
  repo:
    github: git@github.com:lili-an/lili-an.github.io.git,master;
    coding: git@git.coding.net:stto/stto.git,master 
```
