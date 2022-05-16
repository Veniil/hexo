---
title: Onedrive直链提取+IDM实现满速下载！
tags: 'Onedrive，直链下载，IDM, 网盘满速'
updated: 2022/05/16
category: /Onedrive
plugins:
  - indent
renderNumberedHeading: true
grammar_cjkRuby: true
music:
  server: netease
  type: song
  id: 1908189152
abbrlink: a3ad802e
date: 2022-05-16 02:39:16
---

# Onedrive直链提取+IDM实现满速下载！
OneDrive虽然嫖到了5T但是速度慢到极致是不是很不甘心，心里发痒？别急！OneDrive的真正实力远超你想象！今天，我就来教大家如何用oneindex+IDM让你的OneDrive下载速度爆表。话不多说，正文开整！！！
## 国内网盘现状
### 某度与阿里
百度网盘破解版Pandownload开发者被抓的事件，真是闹得红红火火恍恍惚惚了~ 百度爽了，众多~~白嫖~~网盘爱好者却一片哀嚎~ 阿里又玩了一出新花样，号称不限速又整出个非永久容量，还是得开会员才能获得更多容量（虽然有一系列小活动可以获得容量，但是网友们会满意吗！？）
### Onedrive
难道真的没有一些优秀的网盘供我们使用了吗？

当然有！肯定有一些朋友早就想起来了Onedrive这个windows的系统级网盘，国内Onedrive用户不在少数，但是Onedrive国际版速度在国内十分不稳定，但是相对来说下载速度能稳定在1M/s以上，比某度强出太多了。同时一众网友又通过开发者计划白嫖（bushi）到了E5的5T容量账号，不拿来挥霍简直浑身发痒。

早在某度限流严重的同时，网上就浮现了众多通过直链下载来达到满速下载的目的。那么对应的，Onedrive当然也可以通过直链来达到满速下载的效果，而且相对于某度来说简直不要方便了太多！
#### Onedrive直链提取
其实Onedrive有着微软在背后作支撑，它与windows的融合程度堪称完美。连直链提取都比某度方便了太多。如果不是Onedrive国际版的服务器部署在国外，那简直堪称完美！
话不多说，我们直接开始看怎么进行直链提取。

##### 第一步

第一步我们直接在onedrive文件夹里找到自己想要提取连接的文件，然后右击它
[![OROOvF.md.png](https://s1.ax1x.com/2022/05/16/OROOvF.md.png)](https://imgtu.com/i/OROOvF)

我们鼠标选到Onedrive，它会弹出来要做的操作
[![OROxb9.md.png](https://s1.ax1x.com/2022/05/16/OROxb9.md.png)](https://imgtu.com/i/OROxb9)
#### 共享

我们点击共享，然后找到下面的复制链接，点击旁边的复制
[![ORX94x.md.png](https://s1.ax1x.com/2022/05/16/ORX94x.md.png)](https://imgtu.com/i/ORX94x)
#### 复制

看到这样的字样就是复制到了Onedrive的分享连接。
[![ORXi8K.md.png](https://s1.ax1x.com/2022/05/16/ORXi8K.md.png)](https://imgtu.com/i/ORXi8K)
#### 获取直链
然后最关键的步骤在这里，我们该怎样把分享链接转为下载直链呢？其实很简单。
将 OneDrive分享地址中"https://1drv.ms/" 调整为 "http://1drv.stdfirm.com/"，后面的后缀不要动，实现直链获取。

即，将1drv.ms --> 1drv.stdfirm.com

或者，为了图方便我们可以直接打开[直链转换网站](http://1drv.stdfirm.com/)
{% link Onedrive直链提取::http://1drv.stdfirm.com/::https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets@master/logo/256/safari.png %}
[![ORXHZd.md.png](https://s1.ax1x.com/2022/05/16/ORXHZd.md.png)](https://imgtu.com/i/ORXHZd)

将自己复制到的链接粘贴到上面然后直接点击提取后，把下面的链接复制起来就是直链啦~
### 利用IDM实现满速下载

拿到直链后，我们直接打开IDM（Internet Download Manager）,没有的朋友点[这里](https://nxingcloud.co/api/raw/?path=/IDM%20-6.38.7.2%20%20%E4%B8%AD%E6%96%87%E7%BB%BF%E8%89%B2%E7%89%B9%E5%88%AB%E7%89%88.rar)进行下载哦。
{% link IDM-中文绿色版::https://nxingcloud.co/api/raw/?path=/IDM%20-6.38.7.2%20%20中文绿色特别版.rar::https://s1.ax1x.com/2022/05/16/ORv74I.png %}

下载之后找一个习惯的文件夹解压出来，解压出来后先点击绿化，然后打开下面的**IDMan.exe**文件就可以用啦
[![ORvq8P.md.png](https://s1.ax1x.com/2022/05/16/ORvq8P.md.png)](https://imgtu.com/i/ORvq8P)

{% note warning::解压出来后一定要先点击绿化！！ %}

打开后我们直接点击新建任务。
[![ORXzQS.md.png](https://s1.ax1x.com/2022/05/16/ORXzQS.md.png)](https://imgtu.com/i/ORXzQS)

然后把刚才复制到的直链粘贴进去后点击确定。
[![ORjAJ0.md.png](https://s1.ax1x.com/2022/05/16/ORjAJ0.md.png)](https://imgtu.com/i/ORjAJ0)

弹出确认下载窗口后等待右边出现文件图标和大小信息（很快），直接点击开始下载就可以享受Onedrive满速下载啦（具体下载速度依个人网络环境而定）
[![ORjnL4.md.png](https://s1.ax1x.com/2022/05/16/ORjnL4.md.png)](https://imgtu.com/i/ORjnL4)

在这里最好是等它出现具体文件信息后再点击下载，会直接进入飞速模式~

### 结束
看起来图和字这么多，其实是我为了讲解详细一点把每一步过程都写进来了。实际操作起来很快~ 快去试试吧~ 感谢大家的观看~

我的藏宝阁里有更多实用资源哦~
{% link 南星的藏宝阁::https://nxingcloud.co/zh-CN/::https://s1.ax1x.com/2022/05/13/OyS53F.jpg %}