---
title: 我的异地组网实践
date: 2024-01-21 00:32:16
tags:
- network
- 产出
---

## 关于多个局域网连通

首推tailscale，如果跨墙不方便首推wg-easy。但是wg-easy有个缺陷，网页管理端没办法填节点后面局域网网段的ip，需要主动写一个。

## 关于局域网文件互传
发现了一个神器：localsend，能够传文字、图片、文件，目前评价好过其他任何一款