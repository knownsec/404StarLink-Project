# Contents

* [Contents](#contents)
  * [Reconnaissance](#reconnaissance)
     * [ksubdomain](#ksubdomain)
     * [Zoomeye Tools](#zoomeye-tools)
     * [Zoomeye SDK](#zoomeye-sdk)
  * [Vulnerability Assessment](#vulnerability-assessment)
     * [Pocsuite3](#pocsuite3)
  * [Penetration Test](#penetration-test)
     * [shellcodeloader](#shellcodeloader)
  * [Information analysis](#information-analysis)
     * [KunLun-M](#kunlun-m)
     * [KunLun-M - phpunserializechain](#kunlun-m---phpunserializechain)
     * [KunLun-M - EntranceFinder](#kunlun-m---entrancefinder)
  * [Back-penetration, intranet tools](#back-penetration-intranet-tools)
     * [Portforward](#portforward)
  * [Others](#others)
     * [LBot](#lbot)
     * [wam](#wam)
  * [Minitools](#minitools)
     * [bin_extractor](#bin_extractor)
     * [CookieTest](#cookietest)
     * [ipstatistics](#ipstatistics)
     * [cidrgen](#cidrgen)


# Reconnaissance

Information collection of the target before penetration testing



## ksubdomain

#### Project link：

[https://github.com/knownsec/ksubdomain](https://github.com/knownsec/ksubdomain)

#### Project Overview：

ksubdomain is the fastest subdomain enumeration tool, and it runs on Windows/Linux/Mac.



## Zoomeye Tools

#### Project link：

[https://github.com/knownsec/Zoomeye-Tools](https://github.com/knownsec/Zoomeye-Tools)

#### Project Overview：

Zoomeye Tools includes Zoomeye minitools and Zoomeye preview.

Minitools is currently integrated for use in zoomeye.org, copy all targets in multiple formats, and enter the next scan in a convenient and quick way.

Preview implements a simple Zoomeye interface. When a user login and clicks on preview, he can quickly and easily see various information of the current station ip and open port information.



## Zoomeye SDK

#### Project link：

[https://github.com/knownsec/ZoomEye](https://github.com/knownsec/ZoomEye)

#### Project Overview：

[ZoomEye](https://www.zoomeye.org/) is a search engine for cyberspace that lets the user find specific network components(ip, services, etc.).

[ZoomEye API](https://www.zoomeye.org/api/doc) is a web service that provides convenient access to ZoomEye features, data, information over HTTPS. The platform API empowers developers to automate, extend and connected with ZoomEye. You can use the ZoomEye platform API to programmatically create apps, provision some add-ons and perform some automate tasks. Just imagine that what you could do amazing stuff with ZoomEye.



# Vulnerability Assessment

Vulnerability scanning and detection of targets



## Pocsuite3

#### Project link：

[https://github.com/knownsec/pocsuite3](https://github.com/knownsec/pocsuite3)

#### Project Overview：

pocsuite3 is an open-sourced remote vulnerability testing and proof-of-concept development framework developed by the [**Knownsec 404 Team**](http://www.knownsec.com/). It comes with a powerful proof-of-concept engine, many powerful features for the ultimate penetration testers and security researchers.



# Penetration Test

Penetration test on target



## shellcodeloader

#### Project link：

[https://github.com/knownsec/shellcodeloader](https://github.com/knownsec/shellcodeloader)

#### Project Overview：

Because shellcode can be changed and restored at will, it is difficult to check and kill. Therefore, it is one of the most popular ways to bypass AV by making shellcode Trojan. However, for the conventional production method of shellcode payload of cobalt strike, the shellcode text needs to be encrypted, and put into the source code to find a way to bypass AV, then compile. 

The process is too cumbersome. Many of the steps are time-consuming and labor-consuming. After changing shellcode, many processes need to be repeated. 

This tool aims to solve most of the repetitive work in shellcodeloader generation process, reduce the working time of bypass AV, and put more energy on penetration or discovery of new ways to bypass AV.



# Information analysis

Analysis and processing of information in the penetration process, including code audits, etc.



## KunLun-M

#### Project link：

[https://github.com/LoRexxar/Kunlun-M](https://github.com/LoRexxar/Kunlun-M)

#### Project Overview：

Kunlun-Mirror is developed from Cobra-W2.0. After long-term maintenance and improvement, Kunlun-Mirror will focus on the development of tools on the use of security researchers, and will continuously improve the user experience around the use of tools.

At present, the tool mainly supports semantic analysis of php and javascript, as well as basic scanning of chrome ext and solidity.

KunLun-M may be the only open source and long-term maintained automated code audit tool on the market. It is hoped that open source tools can promote the development of white box auditing:>.



## KunLun-M - phpunserializechain

#### Project link：

[https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain](https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/phpunserializechain)

#### Project Overview：

Based on the concept of .QL, a set of CodeDB was explored, and a tool demo for finding the PHP deserialization chain was exploratoryly completed. It is still demo in nature, and there are still many problems to be solved.



## KunLun-M - EntranceFinder

#### Project link：

[https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/entrancefinder](https://github.com/LoRexxar/Kunlun-M/tree/master/core/plugins/entrancefinder)

#### Project Overview：

An interesting small tool for quickly discovering possible entry pages (or missing by developers) when auditing a large amount of php code.



# Back-penetration, intranet tools

Including maintenance of permissions after penetration and intranet tools, etc.



## Portforward

#### Project link：

[https://github.com/knownsec/Portforward](https://github.com/knownsec/Portforward)

#### Project Overview：

PortForward is a port forwarding tool developed using Golang, which solves the problem that the internal and external networks cannot communicate in certain scenarios.



# Others

the others

## LBot

#### Project link：

[https://github.com/knownsec/LBot](https://github.com/knownsec/LBot)

#### Project Overview：

XSS Bot is a threshold for XSS in the CTF. Insufficient back-end performance and imperfect environmental processing will affect every aspect of the bot.

LBot is a simple template born out of a crawler. With the corresponding functions, a mature Bot can be completed quickly and easily.



## wam

#### Project link：

[https://github.com/knownsec/wam](https://github.com/knownsec/wam)

#### Project Overview：

WAM is a platform powered by Python to monitor "Web App", "The dynamic network information". To a certain extent, it greatly help the security researchers save time on tracking the vulnerable code updates and industry dynamics of investment.

AM Model: This module can monitor every updates on all of apps on internet, analysising the changes to make Tag and provide mail notification;

IDM Model: This module uses Web crawler to fetch the industry dynamic information and report that to users;

VDR Model: This module manager all of application package in the history, and save the updated version of which DIFF details;



# Minitools

This category mainly aggregates gadgets and scripts involved in various security research processes, aiming to optimize the daily security automation experience.



## bin_extractor

#### Project link：

[https://github.com/knownsec/Minitools-bin_extractor](https://github.com/knownsec/Minitools-bin_extractor)

#### Project Overview：

A simple script for quickly mining sensitive information in binary files. It can be used to quickly dig and verify inscription information such as URL links in binary files.



## CookieTest

#### Project link：

[https://github.com/knownsec/Minitools-CookieTest](https://github.com/knownsec/Minitools-CookieTest)

#### Project Overview：

A script used to quickly test APIs or required parameters and cookies for a certain request. It can be used to quickly confirm the required parameters of an api for further testing of penetration, etc.



## ipstatistics
#### Project link：

[https://github.com/knownsec/Minitools-ipstatistics](https://github.com/knownsec/Minitools-ipstatistics)

#### Project Overview：

ipstatistics is a script based on the ipip library that is used to quickly filter the ip list. It can quickly filter out countries, regions, and exclude ip targets in special regions.



## cidrgen
#### Project link：

[https://github.com/knownsec/Minitools-cidrgen](https://github.com/knownsec/Minitools-cidrgen)

#### Project Overview：

cidrgen is based on cidr's subnet IP list generator, which quickly solves the pain points of expanding subnets during scanning.