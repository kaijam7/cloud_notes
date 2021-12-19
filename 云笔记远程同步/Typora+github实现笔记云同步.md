# 基于Typora+github实现笔记云同步

## 一、前言

> 
>

## 二、使用工具

- **git**

  一个开源的分布式版本控制系统，可以有效、高速地处理从很小到非常大的项目版本管理

  官网传送门：https://git-scm.com/

  安装及设置教程：

- **Typora**

  一款简洁的本地Markdown编辑器，采用所见即所得的编辑方式，支持Windows/Mac/Linux三大系统

  官网传送门：https://www.typora.net/

  安装及设置教程：

## 三、搭建步骤

### 1.创建一个本地版本库

> 

### 2.建立github远程仓库

> 

### 3.总结

其实只需要进行下面几步就能把本地项目上传到 github 远程仓库上：

1. 在本地创建一个版本库（即文件夹），通过 `git init` 初始化本地仓库；
2. 把项目复制到这个文件夹里面，再通过 `git add .` 把项目添加到暂存区；
3. 再通过 `git commit -m "{注释内容}"` 把项目提交到本地仓库；
4. 在 github 设置好 SSH 密钥后，创建一个远程仓库，通过 `git remote add {别名} {远程地址} ` 将本地仓库和远程仓库进行关联；
5. 最后通过 `git push -u {别名} {分支}` 把本地仓库的项目推送到 github 远程仓库（若新建远程仓库的时候自动创建了README文件会报错，解决办法看上面）。

## 四、日常同步步骤

1. git status
2. git add .
3. git commit -m "云笔记远程同步成功"
4. git push origin master
