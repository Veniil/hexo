---
title: Onedrive直链提取+IDM实现满速下载！
tags: 'Onedrive，直链下载，IDM, 网盘满速'
category: Onedrive
headimg: https://cdn.xenns.com/images/posts/one/headmage-bd3839b8.png?image
description: OneDrive虽然嫖到了5T但是速度慢到极致是不是很不甘心，心里发痒？别急！OneDrive的真正实力远超你想象！今天，我就来教大家如何用oneindex+IDM让你的OneDrive下载速度爆表。话不多说，正文开整！！！
plugins:
  - indent
renderNumberedHeading: true
grammar_cjkRuby: true
abbrlink: a3ad802e
date: 2022-05-16 02:39:16
updated: 2023/04/05
---

## 一、引言
OneDrive虽然嫖到了5T但是速度慢到极致是不是很不甘心，心里发痒？别急！OneDrive的真正实力远超你想象！今天，我就来教大家如何用onedrive+IDM让你的OneDrive下载速度爆表。话不多说，正文开整！！！
## 二、现状
### 2.1 某度与阿里
百度网盘破解版Pandownload开发者被抓的事件，真是闹得红红火火恍恍惚惚了~ 百度爽了，众多~~白嫖~~网盘爱好者却一片哀嚎~ 阿里又玩了一出新花样，号称不限速又整出个非永久容量，还是得开会员才能获得更多容量（虽然有一系列小活动可以获得容量，但是难以满足网友们的需求）
### 2.2 Onedrive
难道真的没有一些优秀的网盘供我们使用了吗？

当然有！肯定有一些朋友早就想起来了Onedrive这个windows的系统级网盘，国内Onedrive用户不在少数，但是Onedrive国际版速度在国内十分不稳定，但是相对来说下载速度能稳定在1M/s以上，比某度强出太多了。同时一众网友又通过开发者计划白嫖（bushi）到了E5的5T容量账号，不拿来挥霍简直浑身发痒。

早在某度限流严重的同时，网上就浮现了众多通过直链下载来达到满速下载的目的。那么对应的，Onedrive当然也可以通过直链来达到满速下载的效果，而且相对于某度来说简直不要方便了太多！
## 三、满速下载

### 3.1 Onedrive直链提取
其实Onedrive有着微软在背后作支撑，它与windows的融合程度无可匹敌。连直链提取都比某度方便了太多。如果不是Onedrive国际版的服务器部署在国外，那简直堪称完美！
话不多说，我们直接开始看怎么进行直链提取。

#### 3.1.1 获取Onedrive共享链接

第一步我们直接在onedrive文件夹里找到自己想要提取连接的文件，然后右击它
{% gallery %}
[![OROOvF.md.png](https://s1.ax1x.com/2022/05/16/OROOvF.md.png)](https://imgtu.com/i/OROOvF)
{% endgallery %}

我们鼠标选到Onedrive，它会弹出来要做的操作
{% gallery %}
[![OROxb9.md.png](https://s1.ax1x.com/2022/05/16/OROxb9.md.png)](https://imgtu.com/i/OROxb9)
{% endgallery %}

我们点击共享，然后找到下面的复制链接，点击旁边的复制
{% gallery %}
[![ORX94x.md.png](https://s1.ax1x.com/2022/05/16/ORX94x.md.png)](https://imgtu.com/i/ORX94x)
{% endgallery %}

看到这样的字样就是复制到了Onedrive的分享连接。
{% gallery %}
[![ORXi8K.md.png](https://s1.ax1x.com/2022/05/16/ORXi8K.md.png)](https://imgtu.com/i/ORXi8K)
{% endgallery %}

#### 3.1.2 共享链接转换为直链

然后最关键的步骤在这里，将获取的Onedrive分享链接转换为下载直链。

打开[网盘永久外链地址生成工具 OneDrive,Google Drive, Dropbox直链在线生成 | Gimhoy Studio](https://link.gimhoy.com/)
{% link Onedrive直链提取::https://link.gimhoy.com/::https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets@master/logo/256/safari.png %}

{% note warning::注意，此网站非本人运营，仅作推荐，对于其中的内容与安全性不作保障，是否使用请网友们自行选择。本人对于使用此网站产生的一切问题概不负责。另外，如该网站负责人不希望本人在此引用则请联系本人删除。本站详细网站政策请参见[政策](https://xenns.com/pages/policy/)一页。 %}

将自己复制到的链接粘贴到上面然后直接点击提取后，把下面的链接复制起来就是直链啦~
### 3.2 利用IDM/Motrix实现满速下载

针对Onedrive不同文件的直链，下载速度也会有所偏差。基本上IDM和Motrix都有可能达到满速的效果。这里以IDM为例来展示下载过程。
#### 3.2.1 安装IDM

拿到直链后，我们直接打开IDM（Internet Download Manager）,没有的朋友点[这里](https://pan.xenns.com/d/AliYun/Public/IDM%20-6.38.7.2%20%20%E4%B8%AD%E6%96%87%E7%BB%BF%E8%89%B2%E7%89%B9%E5%88%AB%E7%89%88.rar?sign=uwCAFv8re4D48CXCS2g1zkXQTnUIWhh-k8tBteR6bGA=:0)进行下载。
{% link IDM-中文绿色版::https://pan.xenns.com/d/AliYun/Public/IDM%20-6.38.7.2%20%20%E4%B8%AD%E6%96%87%E7%BB%BF%E8%89%B2%E7%89%B9%E5%88%AB%E7%89%88.rar?sign=uwCAFv8re4D48CXCS2g1zkXQTnUIWhh-k8tBteR6bGA=:0::https://cdn.xenns.com/kod-static/images/icon/icon_192.png %}

下载之后找一个习惯的文件夹解压出来，解压出来后**先点击绿化**，然后打开下面的**IDMan.exe**文件就可以用了
{% gallery %}
[![ORvq8P.md.png](https://s1.ax1x.com/2022/05/16/ORvq8P.md.png)](https://imgtu.com/i/ORvq8P)
{% endgallery %}

{% note warning::解压出来后一定要先点击绿化！！ %}

#### 3.2.2 建立下载任务

打开后我们直接点击新建任务。
{% gallery %}
[![ORXzQS.md.png](https://s1.ax1x.com/2022/05/16/ORXzQS.md.png)](https://imgtu.com/i/ORXzQS)
{% endgallery %}

然后把刚才复制到的直链粘贴进去后点击确定。
{% gallery %}
[![ORjAJ0.md.png](https://s1.ax1x.com/2022/05/16/ORjAJ0.md.png)](https://imgtu.com/i/ORjAJ0)
{% endgallery %}

弹出确认下载窗口后等待右边出现文件图标和大小信息（很快），直接点击开始下载就可以享受Onedrive满速下载（具体下载速度依个人网络环境而定）
{% gallery %}
[![ORjnL4.md.png](https://s1.ax1x.com/2022/05/16/ORjnL4.md.png)](https://imgtu.com/i/ORjnL4)
{% endgallery %}

## 四、结语

每一款网盘软件的出现都会有其生命周期，都会面临它的荣光与衰落。作为消费者的我们究其根本也只是想寻找一款符合自己使用需求的网盘。谨慎选用，理性支持。众多网盘解决方案中总会有符合自己需求的那一个。

## 五、局限性

{% note warning::注意，经过本人和网友测试，发现此种方法只适用于下载onedrive中的单个文件而不能下载整个文件夹，当用文件夹的共享链接下载时会变为apx文件。目前这个漏洞源于Onedrive的局限性，尚无法修复 %}

## 六、最新消息

{% note::2022年9月8日更新： %}

我自己经常用onedrive，有一个开发者账号和一个个人家庭版账号，今天惊喜地发现Onedrive客户端的下载速度居然逼近了20M/s。

{% gallery %}
![](https://cdn.xenns.com/images/posts/one/tisu-1714b373cecc338dbbc1a36b45374119-344557.png)
{% endgallery %}

不过就在我惊喜之余去ping了一下onedrive的官网，发现结果还是一如既往。

{% gallery %}
![](https://cdn.xenns.com/images/posts/one/ping-1d5ae41ee0df3f2f10115377277aa594-7efe7a.png)
{% endgallery %}

好在客户端的下载速度算是提了上来，无论稳定与否，终归也是看见了不限速的曙光。

那就浅浅地期待一下吧~
