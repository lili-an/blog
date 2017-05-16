---
title: git创建github gh-pages分支
date: 2017-05-16 17:22:42
tags: "git"
categories: "git"
---
## 空的仓库 ##
```
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:github用户名/仓库名.git
git push -u origin master
```

## 已有的仓库 ##
```
git remote add origin git@github.com:github用户名/仓库名.git
git push -u origin master
```

## 把指定的dist文件提交到gh-pages分支上， ##
```
git subtree push --prefix=dist origin gh-pages
```

