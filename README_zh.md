# 404 StarLink Project - 404星链计划

![](./logo.png)

“404星链计划”是知道创宇404实验室于2020年8月开始的计划，旨在通过开源或者开放的方式，长期维护并推进涉及安全研究各个领域不同环节的工具化，就像星链一样，将立足于不同安全领域、不同安全环节的研究人员链接起来。

其中不仅限于突破安全壁垒的大型工具，也会包括涉及到优化日常使用体验的各种小工具，除了404本身的工具开放以外，也会不断收集安全研究、渗透测试过程中的痛点，希望能通过“404星链计划”改善安全圈内工具庞杂、水平层次不齐、开源无人维护的多种问题，营造一个更好更开放的安全工具促进与交流的技术氛围。

# Contents

- 信息收集
    * [ksubdomain](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#ksubdomain) 
        * 最快的子域名爆破工具
    * [Zoomeye Tools](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#zoomeye-tools)
        * Zoomeye Tools是配合Zoomeye使用的Chrome插件
    * [Zoomeye-python](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#zoomeye-python) ![](https://img.shields.io/badge/-New-red) 
        * ZoomEye-python 是基于Zoomeye API开发的python库，同时也可以作为SDK集成其他工具。
    
- 漏洞探测
    * [Pocsuite3](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#pocsuite3)
        * 开源的python3漏洞测试框架
	* [LSpider](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#lspider) ![](https://img.shields.io/badge/-New-red) 
        * 一款为被动扫描器而生的前端爬虫~
    
- 攻击与利用
    * [ShellcodeLoader](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#shellcodeloader)
        * Windows平台的shellcode免杀加载器。

- 信息分析
    * [KunLun-M](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#kunlun-m)
        * Kunlun-Mirror. 专注于安全研究人员使用的白盒代码审计工具
    * [KunLun-M - phpunserializechain](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#kunlun-m---phpunserializechain)
        * 基于.QL的概念探索出的一套CodeDB，一个针对寻找PHP反序列化链的demo
    * [KunLun-M - EntranceFinder](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#kunlun-m---EntranceFinder)
        * 一个简单的工具用于寻找php项目的入口文件

- 后渗透、内网工具
    * [Portforward](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#portforward)
        * PortForward 是一个基于golang开发的端口转发工具

- 其他相关
    * [LBot](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#lbot)
        * 一个简单的Xss bot模板
    * [wam](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#wam)
        * wam是一个用于监视Web app、各类行业动态信息的监控平台

- Minitools
  	* [bin_extractor](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#bin_extractor)
       * 一个简单的用于快速挖掘二进制文件中敏感信息的脚本
   * [CookieTest](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#cookietest)
       * 用于快速测试api或某个请求的必选参数、cookie的脚本.
 	* [ipstatistics](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#ipstatistics)
        	* ipstatistics是一个基于ipip库的，用于快速筛选ip列表的脚本
  	* [cidrgen](https://github.com/knownsec/404StarLink-Project/blob/master/TOOLS_README_zh.md#cidrgen)
        	* cidrgen基于cidr的子网IP列表生成器


# Loading

“星链计划”将会是一个长期而持久的计划，本项目下长期收取有关安全研究、渗透测试过程中的idea，如果idea有意义，那么Knownsec 404Team将会持续跟进相应的工具，期待通过“星链计划”让安全真正工具化。