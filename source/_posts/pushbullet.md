---
title: Pushbullet —— 推送神器
tags:
  - Google
  - 自动化
  - 软件
id: 927
categories:
  - 应用软件
date: 2014-04-05 00:55:27
---

推送通知可谓是移动通讯中的伟大里程碑之一，它改变了很早之前人们需要隔一段时间打开众多应用程序（那时候的手机软件似乎还不被称作“应用”）被动获取信息的窘境，将备受期待的新消息在产生的第一时间传递给用户，可算极大方便了人们的生活、娱乐。

Pushbullet 就是在“推送”上作了文章，而且还是下足了功夫。Pushbullet 通过 Google 账户登录，目前支持 Windows, iOS, Android 三大平台，还提供 Chrome 浏览器插件给使用其它操作系统的用户。用户在所有平台使用同一账号登录后，可以从任一平台推送几乎任何内容到另一平台。你没看错，几乎是“所有内容”都可以被推送，图片、链接、列表、街道地址等等更不在话下，甚至包括 Windows 桌面上的文件。在收到推送后，Android 和 Chrome 平台会以可扩展通知的方式显示被推送的内容和快捷操作按钮，用户无需进入主程序就可以针对不同通知内容进行不同操作；iOS 受到系统限制，查看和操作推送内容仍需打开应用程序界面。

单一的推送应用见多了，看起来 Pushbullet 并没有什么新意？如果加上好友机制和 IFTTT 支持呢？Pushbullet 的与众不同的亮点之一就是好友机制，只需要输入对方的邮箱地址并互相认证为好友，你们双方就可以互相推送各种内容了。IFTTT 支持是今年二、三月份新加入的功能，结合前几个月另一篇介绍 IFTTT 的文章，大家可以着手建立自己的自动化服务站了，这里不再熬述。

Pushbullet 兴起已经好长时间了。写这篇文章除了最近发现 Pushbullet 加入了 Windows, iOS 和 IFTTT 支持的原因以外，刚看到有一款名为“QPush - 快推”的应用占据了生产力排行榜让我很不爽，就那种只能“推”文字到手机的单一功能应用也好意思说“App Store 生产力工具新品推荐榜第一名”、“破百万五星评价”？让广大 Pushbullet 用户情何以堪？

&nbsp;

后记：Pushbullet 在 iOS 上尚不支持 Google 产品的统一账户认证，目前仍然需要通过浏览器单独登录后授权；其它平台未发现此问题。Pushbullet 在 Android 上使用了 Google Cloud Messaging 推送服务，并不借助于常驻后台进程接收推送，请确认行货手机已安装 Google 相关服务框架。