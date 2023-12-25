---
title: proxy原理
date: 2023-12-02 10:33:17
tags:
categories:
- [network]
- [草稿/创意]
---

最近写代码的时候，github老连不上，但是阿里云的服务器特别快，突发奇想是不是能用阿里云作为tcp代理来连接github。
# 阿里云作为upstream
想到这个思路的时候，方案就基本定下来了，第一步把本地dns指到阿里云服务器，第二步在阿里云服务器上配置tcp-proxy。
## 配置dns
## 配置服务器
## 实验结果：失败
## 问题排查：未果

# 灵光一闪：如果我不行，各种基于系统的proxy是怎么做到的呢？
## 查资料
找到shadowsocks-libev
## 看代码