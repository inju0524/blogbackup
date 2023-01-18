---
title: 关于termux手机终端与python
tags:
  - termux
  - 技术
  - 手机终端
top_img: img/baizhu.png
cover: img/baizhu.png
abbrlink: 9edfe7ae
date: 2019-09-13 18:52:18
swiper_index: 1
---
诸君快乐！
今天给各位介绍一款linux终端模拟器
name>             # TERMUX
［我已经测试并成功用其编辑并运行了python，这意味着它真的好用］它可将你的手机打造成一台linux电脑
手机本就是linux内核，这款软件可让你的手机返璞归真
可以当电脑用就意味着可以当电脑编程，比Qpython什么的强大高级多了
既然像电脑那功能就不多说了
可以用pkg命令安装一个更完美的linux发行版
————————————————————————
下面是我学习linux命令后的测试过程：
诸位可参考此教程熟悉安装后软件的python安装以及编译
[为了做一个体面人，我把失败的过程删去]
首先安装后进入Termux软件，等待软件首次install下载，大约1分钟后完成，之后输入
```
pwd
```
回车
会返回当前路径
```
pkg install vim
```
回车
这个是安装指令，后面的vim是要安装的文本编辑器
```
pkg install python
```
这是安装python编译器，用来编译python语言的
安装后可以直接输入python进入控制台编译模式输入exit()退出此模式
如果想写python程序就输入
```
mkdir oncetest
```
文件夹名随意啦
这个文件夹就用于写python程序啦
```
ls
```
这个用于查看当前目录文件，看下文件夹创建成功没
创建成功后
```
cd oncetest
```
cd是用于进入某个路径
进入文件夹后
```
touch test.py
```
创建一个python文件用于写程序
```
ls
```
查看是否创建成功
```
rm 文件名
```
用于删除文件，rm是remove的缩写
好，接下来
```
vim test.py
```
进去刚才创建的py文件编辑，vim是刚才下的文本编辑器
接下来进入vim编辑模式，还不能直接编辑，现在光标在控制台，输入i
进入编辑模式，可以写代码了，写完后按软件自带的Esc，进入命令模式，输入
```
:wq
```
这个命令用于保存并退出
如果保存不了就输入
```
:w!
```
强制保存并退出
接下来输入
```
Python test.py
```
下面就会有程序编译的结果了
![termux](img/termux.jpg)
呼～～～～写完了
此教程送给一窍不通又不好好自学的小白们，所以比较啰嗦，见谅。