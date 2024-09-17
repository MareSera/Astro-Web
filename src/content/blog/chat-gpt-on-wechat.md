---
title: '将你的AI接入微信？'
description: '人工智能'
pubDate: 'Aug 11 2024'
image: '/home.webp'
tags:
  - 人工智能
badge: 想要将各种AI接入你的微信？
categories:
  - 技术
---
> 建议视频文字教程搭配使用

## 视频教程：

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=112947103862208&bvid=BV1HEeceJEAc&cid=500001646610941&p=1" allowfullscreen="allowfullscreen" width="100%" height="500" scrolling="no" frameborder="0" sandbox="allow-top-navigation allow-same-origin allow-forms allow-scripts"></iframe>


## 文字教程

### 前言

本文使用到了这个仓库-> [YuliangXiu/chatgpt-on-wechat](https://github.com/YuliangXiu/chatgpt-on-wechat)

如果你想要更便捷的使用，可以下载我提供的[一键包](https://pan.quark.cn/s/fee19905e690)！(提取码：b2Gq，别问为什么是夸克网盘了，别的我没VIP)

本文使用[讯飞星火大模型](https://xinghuo.xfyun.cn/)为例

为什么选用讯飞星火大模型而不是别的什么呢，因为它的Spark4.0 Ultra可以让我们**白嫖**200万token！

![](/chatgpt-on-wechat/6.png)

二百万token什么概念呢？每个英文字母约为0.8token，中文汉字约1.5token/个，我开着和朋友连续玩了两天消耗了20000token

### 注册/登录

进入网址登录后点击->API免费试用

![](/chatgpt-on-wechat/1.png)

点击管理服务

### 配置

![](/chatgpt-on-wechat/2.png)

找到自己需要的模型，记录下右侧的`Websocket服务接口认证信息`

![](/chatgpt-on-wechat/3.png)

找到下载的一键包，打开` config.json ` ，配置如下信息

![](/chatgpt-on-wechat/4.jpg)

刚才记录的Websocket服务接口认证信息

"xunfei_app_id": "5******8",

"xunfei_api_key": "59******************7c9",

"xunfei_api_secret": "MTJmZD**************M3MDA1",

> 注意别填错了xunfei_api_secret和xunfei_api_key填反了会报401错误。

模型名称

"xunfei_domain": "4.0Ultra",

### 使用


配置完以后看到一键包文件夹里的` 一键启动脚本.bat `了吗？点开他！

![](/chatgpt-on-wechat/5.png)

扫描这个二维码，登录即可！

> <font color=red>特别注意！1.因为开源的是云端项目，所以隐私安全还有待考究 2.必须一直开着才能使用，关掉电脑以后就不能用了....  3.AI反应需要时间发完消息等最多3分</font>，我是直接开了个小号全职作为AI的

完成以上步骤以后就可以爽玩AI辣！

群聊内效果：<img src="/chatgpt-on-wechat/group.jpg"  width="300" />
私信内效果：<img src="/chatgpt-on-wechat/man.jpg"  width="300" />
