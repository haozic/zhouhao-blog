---
title: '博客主题备忘录'
publishDate: '2025-07-12'
description: '[alert type="green"]本博客使用的是Typecho程序，结合主题PureSuck搭建。[/alert] PureSuck是一款开源主题，感谢作者的开源精神，需要可以了解： https://github.com/MoXiaoXi233/PureSuck-theme 以下记录这款主题的'
tags:
  - 随笔
draft: false
comment: true
---

[alert type="green"]本博客使用的是Typecho程序，结合主题PureSuck搭建。[/alert]

PureSuck是一款开源主题，感谢作者的开源精神，需要可以了解：

https://github.com/MoXiaoXi233/PureSuck-theme

以下记录这款主题的部分功能与组件。

**归档页面**

后台新建一个页面，右边选择归档即可

内置一些组件，使用短代码进行解析，使用格式如下

**引用条**
[alert type="red"]这是一个红色警告。[/alert]
[alert type="yellow"]这是一个黄色警告。[/alert]
[alert type="blue"]这是一个蓝色警告。[/alert]
[alert type="green"]这是一个绿色警告。[/alert]
[alert type="pink"]这是一个粉色警告。[/alert]
五种颜色可选，在 type 中填写，效果图可以看上面合集，普通的灰色样式用自带的 blockquote 即可

**彩色信息窗**
[window type="red" title="信息窗口"]这是一个信息窗口。[/window]
[window type="yellow" title="警告窗口"]这是一个信息窗口。<br>这是一个信息窗口的第二行。[/window]
同样五色可选，type 处填写五种颜色之一，在 title 处填写标题，注意内部如果要换行请用<br>标签

**友链卡片**
[friend-card name="周周好运" ico="/usr/uploads/logo_1x1t.png" url="http://zhouhao.cn"]一个个人博客网站。[/friend-card]
不可选择颜色，默认跟着主题强调色走的（在主题设置里切换），描述信息如果要换行请用<br>标签，描述信息尽量简短避免影响样式

**折叠内容**
[collapsible-panel title="折叠面板标题"]这是面板的内容。[/collapsible-panel]
没有颜色选，灰色，用来折叠比较长的内容

**Tabs选项组**
[tabs]
[tab title="我的博客信息"]这是我的博客信息内容。[/tab]
[tab title="交流群"]这是交流群内容。[/tab]
[tab title="申请友链"]这有其他内容。[/tab]
[tab title="关于我们"]这是关于我们的内容。[/tab]
[/tabs]
按道理来说可以简单嵌套，简单测试了一下没什么问题

**时间线**
[timeline]
[timeline-event date="2023-01-01" title="Event 1"]Description of Event 1.[/timeline-event]
[timeline-event date="2023-02-01" title="Event 2"]Description of Event 2.[/timeline-event]
[/timeline]
在[timeline]中添加子[timeline-event]一直加下去就行，应该没什么大问题

**视频卡片**
目前只做了b站的

[bilibili-card bvid="BV1KJ411C7SB"]
像这样就可以插入一个视频卡片啦！其实就是官方那个 iframe 内嵌代码，更方便更简洁了一点而已，默认不自动播放