---
title: 建立hexo博客
date: 2017-11-01 12:00:00
tags: study
---

### 安装前提
安装前，您必须检查电脑中是否已安装下列应用程序：
```
    Node.js
    Git
```

### 安装 Hexo
```
    npm install -g hexo-cli
```

### 建站
```
    hexo init blog
    cd blog
    npm install
```

### 新建文章
```
    hexo new [layout] <title>
```
### 生成静态文件
```
    hexo generate
```

### 启动服务器
```
    hexo server
```

### 部署
将文章部署到github
```
    hexo deploy
```