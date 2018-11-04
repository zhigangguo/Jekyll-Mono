--- 
layout: post
title: The Eternal Lorem Ipsum Placeholder Text Here
author: ZhigangGuo
---

## 解决Logitech M336 蓝牙鼠标无法自动连接到Ubuntu 18.04的问题? 
-----

笔者的笔记HP笔记本电脑是Windows 10和ubuntu 18.04双系统，新买的的Logitech M336蓝牙鼠标在Windows 10下连接正常，首次连接后每次重启电脑都可以自动连接，在Ubuntu 18
.04 首次连接出现不停的连接断开的现象，重启电脑后也不会自动连接
$ bluetoothctl
$ list
$ select the MAC of your laptop bluetooth adapter
$ show
$ scan on
$ scan off
$ pair the MAC of your bluettooth mouse
$ connect the MAC of your bluettooth mouse
$ trust the MAC of your bluettooth mouse
