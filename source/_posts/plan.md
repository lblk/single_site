---
title: 滚动计划
date: 2024-01-22 02:32:51
tags:
- 计划
top: 9999
---


### 1.22进展
#### 未完成
- [ ] 没有安排单位述职述廉报告
- [ ] 没有安排公司述职报告
#### 已完成
- [x] nas配置wake on lan
- [x] nas安装docker
- [x] 了解公司负载均衡的使用方法
- [x] 收藏了两篇文章用于后续学习前端速度优化
	- [ ] 学习这两篇文章（在掘金）
	- [ ] 学习有关网站植入广告的知识（在掘金）
- [x] 设计了负载均衡的营销重点
	- [ ] 还要关注如何实现HA功能
	- [ ] 关注SSLO和其它负载均衡产品的关键难点功能
#### 有进展
- 完善wg-easy
	阅读了代码，修改代码的关键在于能否找到合适的vue原生组件用于添加cidr，其它后端代码非常易读
- 完善cosmos
	搭建了运行环境，运行了demo，还需要进一步加深研究。
- 完善nas
	搭建好了docker，剩下的事都没做，没事就先放着吧，反正不急用
- 完善实验环境
	没做，没多大意义


### 完善nas

- 远程访问功能
  - 完善wg-easy
    - 完善ip-cidr配置界面
    - 完善PersistKeepalive配置生成
    - 调查研究登录机制，研究如何实现多容器/docker-compose/k8s/下的多租户模式
<<<<<<< HEAD
- gitlab
- mysql
- postgresql
- wow server
- docker
- pypi镜像站
- docker镜像站(flask*)
- npm镜像站
- next-cloud
=======
- gitlab(docker)
- mysql(docker)
- postgresql(docker)
- wow server(raw)
- [x] docker
- pypi镜像站(flask-pypi-proxy)
- docker镜像站(harbor)
- npm镜像站(verdaccio)
>>>>>>> 2088adc6542c636a2b3af1a9d07feb11e36d7202
### 完善实验环境
- 给机械硬盘测速，形成一个对速度的基本认识
- spdk + iscsi测试nas的裸盘访问速度