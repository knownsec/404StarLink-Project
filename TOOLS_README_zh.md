# Contents

* [Project](#project)
  * [Portforward](#portforward)
  * [KunLun-M](#kunlun-m)
  * [LBot](#lbot)
  * [ksubdomain](#ksubdomain) 
  * [Zoomeye Tools](#zoomeye-tools)
  * [Pocsuite3](#pocsuite3)
  * [Zoomeye SDK](#Zoomeye-SDK)
  * [wam](#wam)
* [Minitools](#minitools)
* [KunLun-M - phpunserializechain](#kunlun-m---phpunserializechain)
  - [bin_extractor](#bin_extractor)
  	  	- [CookieTest](#cookietest)
  	  
  	  * [ipstatistics](#ipstatistics)
  	  * [cidrgen](#cidrgen)



# Project

该分类下主要聚合各类安全工具，偏向于可用性较高的完整项目。



## Portforward

#### 项目链接：

[https://github.com/knownsec/Portforward](https://github.com/knownsec/Portforward)

#### 项目简述：

PortForward 是使用 Golang 进行开发的端口转发工具，解决在某些场景下 内外网无法互通的问题。



## KunLun-M

#### 项目链接：

[https://github.com/LoRexxar/Kunlun-M](https://github.com/LoRexxar/Kunlun-M)

#### 项目简述：

Kunlun-Mirror是从Cobra-W2.0发展而来，在经历了痛苦的维护改进原工具之后，昆仑镜将工具的发展重心放在安全研究员的使用上，将会围绕工具化使用不断改进使用体验。

目前工具主要支持php、javascript的语义分析，以及chrome ext, solidity的基础扫描.

KunLun-M可能是市面上唯一的开源并长期维护的自动化代码审计工具，希望开源工具可以推动白盒审计的发展:>.



## LBot

#### 项目链接：

[https://github.com/knownsec/LBot](https://github.com/knownsec/LBot)

#### 项目简述：

XSS Bot是CTF比赛中出XSS的一大门槛，后端性能不够，环境处理不完善各种都会影响到Bot的每一环。

LBot是脱胎于爬虫的简单模板，配合相应的功能，可以方便快捷的完成一个成熟的Bot。




## ksubdomain
#### 项目链接：

[https://github.com/knownsec/ksubdomain](https://github.com/knownsec/ksubdomain)

#### 项目简述：

ksubdomain是最快的子域名爆破工具,并且能运行在Windows/Linux/Mac，它可以很快的进行DNS爆破，在Mac和Windows上理论最大发包速度在30w/s,linux上为160w/s的速度。



## Zoomeye Tools

#### 项目链接：

[https://github.com/knownsec/Zoomeye-Tools](https://github.com/knownsec/Zoomeye-Tools)

#### 项目简述：

Zoomeye Tools包括Zoomeye minitools以及Zoomeye preview两个功能。

minitools目前集成了针对zoomeye.org使用过程中，以多种格式复制所有目标，以方便快捷的方式进入下一步扫描。

preview实现了一个简易的Zoomeye界面，当用户登录并点开preview时，可以方便快捷的看到当前站ip的各种信息以及开放端口信息。



## Pocsuite3

#### 项目链接：

[https://github.com/knownsec/pocsuite3](https://github.com/knownsec/pocsuite3)

#### 项目简述：

pocsuite3是由Knownsec 404团队开发的开源远程漏洞测试和概念验证开发框架。它带有强大的概念验证引擎，以及针对最终渗透测试人员和安全研究人员的许多强大功能。



## Zoomeye SDK
#### 项目链接：

[https://github.com/knownsec/ZoomEye](https://github.com/knownsec/ZoomEye)

#### 项目简述：

[ZoomEye](https://www.zoomeye.org/)是用于网络空间的搜索引擎，可让用户查找特定的网络组件（ip，服务等）。

[ZoomEye API](https://www.zoomeye.org/api/doc)是一项Web服务，可通过HTTPS方便地访问ZoomEye功能，数据和信息。 平台API使开发人员能够自动化，扩展和连接ZoomEye。 您可以使用ZoomEye平台API来以编程方式创建应用，提供一些附加组件并执行一些自动化任务。 试想一下，使用ZoomEye可以做得很棒。



## wam
#### 项目链接：

[https://github.com/knownsec/wam](https://github.com/knownsec/wam)

#### 项目简述：

WAM是一个由Python驱动的平台，用于监视“ Web App”，“动态网络信息”。 在某种程度上，它可以极大地帮助安全研究人员节省跟踪脆弱代码更新和投资行业动态的时间。

AM模型：此模块可以监视互联网上所有应用程序的每个更新，分析所做的更改以生成Tag并提供邮件通知；

IDM模型：此模块使用Web搜寻器来获取行业动态信息并将其报告给用户。

VDR Model：此模块管理器在历史记录中的所有应用程序包，并保存其中DIFF详细信息的更新版本；




# Minitools

该分类下主要聚合各类安全研究过程中涉及到的小工具、脚本，旨在优化日常安全自动化的使用体验。



## KunLun-M - phpunserializechain

#### 项目链接：

[https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain](https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain)

#### 项目简述：

基于.QL的概念探索出的一套CodeDB，探索性的完成了一个针对寻找PHP反序列化链的工具demo，目前还是demo性质的，还有很多问题需要解决。



## bin_extractor

#### 项目链接：

[https://github.com/knownsec/Minitools-bin_extractor](https://github.com/knownsec/Minitools-bin_extractor)

#### 项目简述：

一个简单的用于快速挖掘二进制文件中敏感信息的脚本。可以用来快速挖掘并验证二进制文件中的url链接等铭感信息。



## CookieTest

#### 项目链接：

[https://github.com/knownsec/Minitools-CookieTest](https://github.com/knownsec/Minitools-CookieTest)

#### 项目简述：

用于快速测试api或某个请求的必选参数、cookie的脚本。可以用来快速确认某个api的必选参数以便进一步测试渗透等.



## ipstatistics

#### 项目链接：

[https://github.com/knownsec/Minitools-ipstatistics](https://github.com/knownsec/Minitools-ipstatistics)

#### 项目简述：

ipstatistics是一个基于ipip库的，用于快速筛选ip列表的脚本，可以快速筛选出国家、地区以及排除特殊地区的ip目标。



## cidrgen

#### 项目链接：

[https://github.com/knownsec/Minitools-cidrgen](https://github.com/knownsec/Minitools-cidrgen)

#### 项目简述：

cidrgen基于cidr的子网IP列表生成器，快捷解决扫描时展开子网的痛点。