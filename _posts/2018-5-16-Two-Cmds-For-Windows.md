---
layout: post
title: Windows下两个有用的小命令
---

1. 打印当前目录
Linux下我们一般使用pwd，Windows下我们用什么呢？
查了一下，原来我们使用“chdir”就可以了，后面啥都不跟，当前目录就被打印出来了
<hr>

2. 显示文件内容
Linux下我们可以用cat，Windows下以前没用过，难道也是cat？
谷歌了一把，用type就可以了：
<br>
type filename
<br>
type filename | more
