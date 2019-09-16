# Markdown
## Markdown的基础知识
### 学好编程的重要性
#### 论打字速度的重要性
##### 论学好英语的重要性
**文本加粗**  

*斜体文字*

<u>下划线</u>  

~~删除线~~ 

***
> 这是一段介绍Markdown语法的文字。

    *  圆点符号
    1. 数字序列
    2. 数字序列

````
    * [ ] JavaScript
    * [ ] PHP
    * [ ] C#
    * [x] Markdown
````
      [VSCode官网](https://code.visualstudio.com/)

    [MarkDown百度百科](https://baike.baidu.com/item/markdown/3245829?fr=aladdin)

***

**常用快捷键**  

Ctrl + Shift + E 资源管理器  
Ctrl + Shift + F 搜索  
Ctrl + Shift + G 源代码管理器  
Ctrl + Shift + D 调试  
Ctrl + Shift + X 插件扩展  
F1 或 Ctrl+ Shift + p 打开命令面板  
Shift + Alt + F 代码格式化  
Ctrl+ F 查找  
Ctrl+ H 查找替换  
Ctrl+ N 新建文件  
Ctrl+ S 保存  
Alt + ↑ 或 Alt + ↓ 上下移动一行  
Shift + Alt + ↑ 或 Shift + Alt + ↓ 向上向下复制一行  
F11 全屏  


**常用插件**  
**中文语言包** Chinese (Simplified) Language Pack for Visual Studio Code   
**MarkDown预览增强** Markdown Preview Enhanced   
**代码拼写检查器** Code Spell Checker   
**VS Code图标** vscode-icons   
**格式化代码工具** beautify   
**HTML代码提示器** HTML Snippets   
**CSS样式提升器** HTML CSS Support   
**各种皮肤主题 例如：** One Dark Pro，Bimbo，Atom One Dark Theme 
 
 ***

    | 帐户类型 | 免费帐户 | 标准帐户 | 高级帐户 |
    | --- | --- | --- | --- |
    | 帐户流量 | 60M | 1GB | 10GB |
    | 设备数目 | 2台 | 无限制 | 无限制 |
    | 当前价格 | 免费 | ￥8.17/月 | ￥12.33/月|

![](P=SImfBuw88txiXNwc5mJ26M=cDnIroxJ2wS7Dw83hYhR1534925902734compressflag.jpg)

***
**MarkDown编辑工具**
VSCode  
Typora  
印象笔记  
Cmd Markdown 作业部落  

# git & github 入门
## git简介
![](git.png)

Git是什么？Git 是 Linux 的创始人 Linus Torvalds 开源的一款分布式版本控制系统，以帮助开发者更好的对项目进行版本管理。每一个优秀的开发者在进行项目开发时都会第一时间给自己的项目加上 Git，以便能更好的追踪代码修改，进行版本回溯等操作。在多人协作的开发过程中，Git 更是必不可少的。因此，本书中将使用 Git 来管理项目的所有代码，让你在阅读本书的时候能够体会到 Git 的强大，了解实际开发中我们对 Git 的应用。
在现代化的项目开发中，Git 基本上是标配。

## git bash 命令行模式的基本特点:

简洁，迅速，高效 

## git bash 基础命令 

-pwd (print working directory) 查看当前所在路径--绝对路径   
-cd (change directory) 切换目标   
-ls (list) 查看当前目录下的内容   
-mkdir (make directory) 创建目录   
-clear 清屏   
-q 退出   

## git基本原理：

git版本管理工具，有3个工作区：

1.工作目录   
2.暂存区-----存放工作中更改的文件，避免项目代码丢失。   
3.代码仓库-----当开发功能足够成为一个版本时，提交到仓库。其实就是将暂存区中代码复制一份存储到代码仓库中。 

## git常用命令

配置git用户名和邮件 
git config --global user.name sun   
git config --global user.email sun@qq.com   
将工作目录中的文件添加到暂存区   
git add sun.html（这个命令上传一个文件） git add .(这个命令会将当前目标下所有文件上传) git add a.txt b.txt (如果上传多个，文件名之间用空格)   
将暂存区中的代码提交到本地仓库，形成一个版本   
git commit -m "备 注"（如果备注内容带空格，则需要加“”）   
查看本地仓库中的历史提交版本   
git log 
