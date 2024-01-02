---
title: 记一次别开生面的家庭mesh组网
date: 2021-02-19 17:09:30
# tags:
---

家里的路由器事从初高中开始一直用到现在的TP-Link的TL-WR941N，还要运营商送的水星路由器。一直都有换路由器的想法，但家里190平的面积需要两个路由器才能实现无死角的覆盖。之前是以AP的方式直接对光猫进行扩展，因为没有去折腾AC + AP模式（因为原本的路由器本来就落伍，并且一个AC的价格足够买一台新的路由器了）所以两个路由器的SSID都是不一样的。
知道Wifi6 的出现和mesh组网 的概念进入我的视野，我就知道家里的路由器该换了。

<!-- more -->

## 组网的需求

* 两个路由器一个SSID，并且自动切换到信号最好的路由器

mesh组网可以完美的解决这个问题。

* 在房间拉一条网线到书桌

当时装修的时候，每个房间都预埋了网线（还好是超五类线，身边太多人因为只是五类线被迫降级到百兆）。然而网口和书桌分别在房间的两侧。

## 组网方案的选择

* 最理想的情况

## 路由器的选择

* 小米AX3600

Q: 为什么不选择AX6000

A: 因为是从LAN口带宽考虑的，AX6000有一个LAN口是2.5G网口而其余三个LAN口共享1G，而AX3600四个LAN口都可以跑满四个LAN口，那么考虑到未来可能加入的NAS AX3600可能更符合我的选择。其次我认为既然决定mesh组网AX3600的信号就不是首选（看评测AX3600信号没有AX6000好，并且有两侧信号低洼的问题）。

* 红米AX6

和AX3600一样的配置，砍掉了AIoT 天线，貌似信号有所削弱，但是同样砍半的价格让它非常适合做mesh的子路由。