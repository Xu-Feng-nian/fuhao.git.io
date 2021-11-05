---
title: git常用命令总结
date: 2021-11-05 15:21:19
tags:
---
.

## 一、初始化Git仓储/(仓库)与用户配置：

### 初始化Git仓储/(仓库)：git init
### 配置用户名：git config --global user.name "user"
### 配置邮箱:  git config --global user.email "xxx@xxx.com"



## 二、把代码添加到.git仓储中

### 将文件内容添加到索引：git add ./index.html
### 将所有的修改的文件添加到索引：git add ./
### 将索引的文件放到版本库：git commit -m "这是这次更新的说明"
### 将所有修改的文件提交到版本库：git commit --all -m "一些说明"