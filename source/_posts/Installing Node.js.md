---
title: Linux 16.04 安装Node.js
date: 2017-11-01 11:11:11
tags: study
---
***
### 1.下载
在[官网](https://nodejs.org/en/download/)选择编译好的Linux Binaries文件，使用wget命令下载。
```
    wget http://nodejs.org/dist/v8.9.0/node-v8.9.0-linux-x64.tar.xz
```
### 2.解压文件。
```
    tar -xJf node-v8.9.0-linux-x64.tar.xz
```
### 3.设置为全局变量
```
    sudo ln -s /home/ping/software/node/bin/node /usr/local/bin/node
    sudo ln -s /home/ping/software/node/bin/npm /usr/local/bin/npm
```
