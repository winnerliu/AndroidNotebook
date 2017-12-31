# VIM Config（Vim 配置）

## 一、安装VIM

Ubuntu 16.04中安装Vim 8.0
```
sudo add-apt-repository ppa:jonathonf/vim
sudo apt update
sudo apt install vim
```
卸载vim
```
sudo apt-get purge vim vim-*
```
## 二、插件简介

简单介绍各插件功能及下载地址

---


---
cscope：

一款开源免费的 C/C++浏览工具，自带一个基于文本的用户界面，通过cscope可以很方便地找到某个函数或变量的定义位置、被调用的位置等信息。Cscope对 C /C++支持较好，也可以自己定制来支持Java和Perl、Python等脚本语言。Vim和gvim都提供了cscope接口，通过适当的配置，可以在Unix/Linux下实现变量、函数、文件等之间跳转，就像Windows下的Source Insight一样灵活易用。由于cscope是开源免费的，而且配合vim可以脱离鼠标，实现全键盘操作，方便快捷地浏览源代码，深受程序员、Geek等人士的喜爱。
```
sudo apt-get install cscope
```
---

ctags：扫描指定的源文件，找出其中所包含的语法元素，并将找到的相关内容记录下来。
```
sudo apt-get install ctags
```


