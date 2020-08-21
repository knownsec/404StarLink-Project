# Contents

* [Project](#project)
  * [ksubdomain](#ksubdomain) 
  * [Zoomeye Tools](#zoomeye-tools)
  * [Pocsuite3](#pocsuite3)
  * [Zoomeye SDK](#Zoomeye-SDK)
  * [wam](#wam)
* [Minitools](#minitools)
  * [ipstatistics](#ipstatistics)
  * [cidrgen](#cidrgen)



# Project

该分类下主要聚合各类安全工具，偏向于可用性较高的完整项目。


## ksubdomain
Tag:

- Go
- subdomain

#### 项目链接：

[https://github.com/knownsec/ksubdomain](https://github.com/knownsec/ksubdomain)

#### 项目简述：

ksubdomain是一款基于无状态子域名爆破工具，支持在Windows/Linux/Mac上使用，它会很快的进行DNS爆破，在Mac和Windows上理论最大发包速度在30w/s,linux上为160w/s的速度。

## Zoomeye Tools

Tag:

- Chrome crx
- Zoomeye
- Pentest

#### 项目链接：

[https://github.com/knownsec/Zoomeye-Tools](https://github.com/knownsec/Zoomeye-Tools)

#### 项目简述：

Zoomeye Tools包括Zoomeye minitools以及Zoomeye preview两个功能。

minitools目前集成了针对zoomeye.org使用过程中，以多种格式复制所有目标，以方便快捷的方式进入下一步扫描。

preview实现了一个简易的Zoomeye界面，当用户登录并点开preview时，可以方便快捷的看到当前站ip的各种信息以及开放端口信息。

## Pocsuite3

Tag:

- Python3
- Pentest

#### 项目链接：

[https://github.com/knownsec/pocsuite3](https://github.com/knownsec/pocsuite3)

#### 项目简述：

pocsuite3是由Knownsec 404团队开发的开源远程漏洞测试和概念验证开发框架。它带有强大的概念验证引擎，以及针对最终渗透测试人员和安全研究人员的许多强大功能。

## Zoomeye SDK
Tag:

- Zoomeye

#### 项目链接：

[https://github.com/knownsec/ZoomEye](https://github.com/knownsec/ZoomEye)

#### 项目简述：

[ZoomEye](https://www.zoomeye.org/)是用于网络空间的搜索引擎，可让用户查找特定的网络组件（ip，服务等）。

[ZoomEye API](https://www.zoomeye.org/api/doc)是一项Web服务，可通过HTTPS方便地访问ZoomEye功能，数据和信息。 平台API使开发人员能够自动化，扩展和连接ZoomEye。 您可以使用ZoomEye平台API来以编程方式创建应用，提供一些附加组件并执行一些自动化任务。 试想一下，使用ZoomEye可以做得很棒。

## wam
Tag:
- Python
- Monitor

#### 项目链接：

[https://github.com/knownsec/wam](https://github.com/knownsec/wam)

#### 项目简述：

WAM是一个由Python驱动的平台，用于监视“ Web App”，“动态网络信息”。 在某种程度上，它可以极大地帮助安全研究人员节省跟踪脆弱代码更新和投资行业动态的时间。

AM模型：此模块可以监视互联网上所有应用程序的每个更新，分析所做的更改以生成Tag并提供邮件通知；

IDM模型：此模块使用Web搜寻器来获取行业动态信息并将其报告给用户。

VDR Model：此模块管理器在历史记录中的所有应用程序包，并保存其中DIFF详细信息的更新版本；


# Minitools

该分类下主要聚合各类安全研究过程中涉及到的小工具、脚本，旨在优化日常安全自动化的使用体验。

## ipstatistics

Tag:

- Python
- ipip
- ip filter

#### 项目链接：

[https://github.com/knownsec/Minitools-ipstatistics](https://github.com/knownsec/Minitools-ipstatistics)

#### 项目简述：

ipstatistics是一个基于ipip库的，用于快速筛选ip列表的脚本，可以快速筛选出国家、地区以及排除特殊地区的ip目标。



## cidrgen

Tag:

- go
- Scan

#### 项目链接：

[https://github.com/knownsec/Minitools-cidrgen](https://github.com/knownsec/Minitools-cidrgen)

#### 项目简述：

cidrgen基于cidr的子网IP列表生成器，快捷解决扫描时展开子网的痛点。