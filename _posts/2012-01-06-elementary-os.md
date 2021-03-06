---
title: elementary OS，另一个思路
author: killpanda
layout: post
---

要是没记错的话，elementary Project 最开始只有一个 elementary 主题，之后延伸出了很多项目，形成了 elementary Project 项目组，并有了 elementary OS。

在之前用过 elementary OS 的第一个版本，基于 Ubuntu 10.04。里面删除了 Ubuntu 原版中很少用到的程序，并预装自己开发的浏览器，邮件客户端，通讯录等程序。这个发行版相对于原版改变还是比较小的，并且自己开发的程序还很粗糙。但它对 Ubuntu 的改版很小，从各种 PPA 里安装程序不会出现各种兼容问题。

作为一个 Linux 桌面爱好者，还是很关注这个项目，在 Facebook 上关注他们的动态，在官网看了他们的日志。

项目组的创始者是一个英国的 UI 设计师。他用的机器是一台 Mac，从最开始的 elementary Theme 的Mac风格，到后来的 elementary OS 的设计思路，都可以看出苹果的风格对他的影响很大。项目组成员也不拘泥于 Linuxer 的传统思维。

在开发方面，为了保持与系统的高度集成性，eLementary OS 没有直接预装已经存在的软件，而是重新写了很多自己的程序，并且都是 GTK＋与 Vala 作为OS开发的主要语言，这一点和苹果对 Cocoa 的使用很相似。项目组可以说是重新发明了很多轮子。例如，下一个版本的系统抛弃了 Nautilus，用 Marlin 作为自己的文件管理器；集成了 Midori 浏览器；开发自己的邮件客户端 Postler ；音乐播放器 BeatBox ，甚至自己的通讯录 Dextex 与字典 Lingo 。这些程序的风格简洁界面清爽。从这些地方可以看出苹果的影子，苹果为了保持统一的系统体验，Mac OS X 与 iOS 上，苹果预装了不少自己开发的软件。但不得不承认，目前这些程序还都是一些半成品。例如，Midori是一个兼容性很差的浏览器，当一些用户留言提出为什么不用 Chromium 来代替它的时候，开发者的态度很坚决，说 elementary OS 决不会用其他框架开发的浏览器，因为 elementary OS 需要自己的浏览器和一致的界面体验；还有，邮件客户端 Postler，虽然清爽，但是经常死掉。

在 UI 设计和用户体验上，elementary OS 在官方博客里经常被讨论，因此可以看出 elementary OS 对这些方面极高的重视。官网有一篇很长的文章讨论过标题栏上面最大化，最小化，关闭按钮的设计。最后讨论的结果是 elemtnary OS 中，去掉了最大化，最小化按钮，仅保留关闭按钮。当点击关闭按钮的后，程序不会退出，而是仅仅关闭了UI界面，从某种程度代替了最小化按钮；在右侧增加了全屏按钮，来代替最大化的功能。这些思路基本上与 Mac OS X 吻合，并且很合理。另外，项目组还对系统设置面板，软件的安装方法等细节都有长篇的讨论。

2012刚开始，elementary 项目组在博客上公布了新一年的任务。作为一个目标远大的项目，elementary OS 的目的绝不是做出一个更换主题，进行简单优化的拼凑的发行版，而是想做成一个用户体验一流，精益求精的产品。但是，要完成他们的目标会非常艰辛。特立独行的风格下，elementary 项目的产品未必会非常稳定，足够日常使用。但至少，它为Linux桌面下的程序设计带来的是另一条思路。
