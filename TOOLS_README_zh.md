# Contents

* [Contents](#contents)
  * [信息收集](#信息收集)
    * [ksubdomain](#ksubdomain)
    * [Zoomeye Tools](#zoomeye-tools)
    * [Zoomeye-python](#zoomeye-python)
  * [漏洞探测](#漏洞探测)
    * [Pocsuite3](#pocsuite3)
    * [LSpider](#lspider)
  * [攻击与利用](#攻击与利用)
    * [shellcodeloader](#shellcodeloader)
  * [信息分析](#信息分析)
    * [KunLun-M](#kunlun-m)
    * [KunLun-M - phpunserializechain](#kunlun-m---phpunserializechain)
    * [KunLun-M - EntranceFinder](#kunlun-m---entrancefinder)
  * [后渗透，内网工具](#后渗透内网工具)
    * [Portforward](#portforward)
  * [其他](#其他)
    * [LBot](#lbot)
    * [wam](#wam)
  * [Minitools](#minitools)
    * [bin_extractor](#bin_extractor)
    * [CookieTest](#cookietest)
    * [ipstatistics](#ipstatistics)
    * [cidrgen](#cidrgen)



# 信息收集

在渗透测试前置准备工作过程种涉及到的各类信息收集。



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



## [Zoomeye-python](https://github.com/knownsec/ZoomEye-python)

##### 项目链接：

https://github.com/knownsec/ZoomEye-python

##### 项目简述：
ZoomEye 是一款网络空间搜索引擎，用户可以使用浏览器方式 https://www.zoomeye.org 搜索网络设备。

ZoomEye-python 是一款基于 ZoomEye API 开发的 Python 库，提供了 ZoomEye 命令行模式，同时也可以作为 SDK 集成到其他工具中。该库可以让技术人员更便捷地搜索、筛选、导出 ZoomEye 的数据。



# 漏洞探测

对目标的各类漏洞探测扫描。



## Pocsuite3

#### 项目链接：

[https://github.com/knownsec/pocsuite3](https://github.com/knownsec/pocsuite3)

#### 项目简述：

pocsuite3是由Knownsec 404团队开发的开源远程漏洞测试和概念验证开发框架。它带有强大的概念验证引擎，以及针对最终渗透测试人员和安全研究人员的许多强大功能。



## [LSpider](https://github.com/knownsec/LSpider)

##### 项目链接：

https://github.com/knownsec/LSpider

##### 项目简述：
一款为被动扫描器而生的前端爬虫~

由Chrome Headless、LSpider主控、Mysql数据库、RabbitMQ、被动扫描器5部分组合而成。

(1) 建立在Chrome Headless基础上，将模拟点击和触发事件作为核心原理，通过设置代理将流量导出到被动扫描器。

(2) 通过内置任务+子域名api来进行发散式的爬取，目的经可能的触发对应目标域的流量。

(3) 通过RabbitMQ来进行任务管理，支持大量线程同时任务。

(4) 智能填充表单，提交表单等。

(5) 通过一些方式智能判断登录框，并反馈给使用者，使用者可以通过添加cookie的方式来完成登录。

(6) 定制了相应的Webhook接口，以供Webhook统计发送到微信。

(7) 内置了Hackerone、bugcrowd爬虫，提供账号的情况下可以一键获取某个目标的所有范围。



# 攻击与利用

在实际渗透测试过程中涉及到的工具。



## shellcodeloader

#### 项目链接：

https://github.com/knownsec/shellcodeloader

#### 项目简述：

shellcode由于可以随意地进行变化和还原，杀软的查杀难度较大。因此将木马shellcode化，再进行shellcode免杀是目前最流行的免杀方式之一。

但是就以Cobalt Strike的shellcode免杀载荷常规的制作方式来说，需要将shellcode文本加密编码，放入源码想办法免杀，编译等过程太过繁琐，其中不少步骤耗时耗力，更换shellcode之后不少过程又需要重复进行。

本工具旨在解决shellcode载荷生成过程中多数重复性工作，降低免杀的工作时间，将更多的精力放在渗透或者发现新的免杀利用方式上。



# 信息分析

对在渗透测试中获取到的各种信息做分析。



## KunLun-M

#### 项目链接：

[https://github.com/LoRexxar/Kunlun-M](https://github.com/LoRexxar/Kunlun-M)

#### 项目简述：

Kunlun-Mirror是从Cobra-W2.0发展而来，在经历了痛苦的维护改进原工具之后，昆仑镜将工具的发展重心放在安全研究员的使用上，将会围绕工具化使用不断改进使用体验。

目前工具主要支持php、javascript的语义分析，以及chrome ext, solidity的基础扫描.

KunLun-M可能是市面上唯一的开源并长期维护的自动化代码审计工具，希望开源工具可以推动白盒审计的发展:>.



## KunLun-M - phpunserializechain

#### 项目链接：

[https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain](https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain)

#### 项目简述：

基于.QL的概念探索出的一套CodeDB，探索性的完成了一个针对寻找PHP反序列化链的工具demo，目前还是demo性质的，还有很多问题需要解决。



## KunLun-M - EntranceFinder

#### 项目链接：

[https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/entrancefinder](https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/entrancefinder)

#### 项目简述：

一个有趣的小工具，用于解决在审计大量的php代码时，快速发现存在可能的入口页面（或是开发者都遗漏的）。



# 后渗透、内网工具

在渗透测试后涉及到的权限维持，或者内网渗透涉及到的工具。



## Portforward

#### 项目链接：

[https://github.com/knownsec/Portforward](https://github.com/knownsec/Portforward)

#### 项目简述：

PortForward 是使用 Golang 进行开发的端口转发工具，解决在某些场景下 内外网无法互通的问题。



# 其他相关

其他安全链路下的安全类工具。



## LBot

#### 项目链接：

[https://github.com/knownsec/LBot](https://github.com/knownsec/LBot)

#### 项目简述：

XSS Bot是CTF比赛中出XSS的一大门槛，后端性能不够，环境处理不完善各种都会影响到Bot的每一环。

LBot是脱胎于爬虫的简单模板，配合相应的功能，可以方便快捷的完成一个成熟的Bot。



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