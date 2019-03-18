# LearnGitHub
Learn by practicing

## 写在前面

教程的目的是让零基础小白能学会使用GitHub完成工作任务。
我们将通过该教程学会使用Git完成如下内容：

* 安装下载一个Git
* Fork项目到自己的仓库
* 复制一个项目到本地
* Push自己的修改文档
* 同步最新版本



### 下载及安装

在使用Git前我们需要先安装 Git。Git 目前支持 Linux/Unix、Solaris、Mac和 Windows 平台上运行。
Git 各平台安装包下载地址为：http://git-scm.com/downloads 。

安装完成后打开终端输入：
```
> git --version
  git version 2.16.2
```
这就说明已经安装成功了。

然后在自己的PC端建个文件夹，打开这个文件夹，进入终端，输入：
```
> git init
```
初始化文件夹，以后的项目都可以放到这个文件夹。


### Fork这个项目

首先你得有自己的git账号，如果没有请点击最右上角的 "Sign Up" 按钮。
有账号的登录自己的账号。

先 Fork 该教程到自己的仓库，如图点击右上角：
![avatar](./image/clone_git.png)


复制链接，在终端中输入：
```
> git clone https://github.com/******/LearnGitHub.git 
```
经过一系列的操作后，你就可以在自己的仓库中看到这个项目了。