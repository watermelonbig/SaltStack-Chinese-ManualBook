# SaltStack-Chinese-Manual
本文是根据SaltStack官方英文文档翻译所得，欲了解原文内容请参见以下链接.
https://docs.saltstack.com/en/latest/contents.html

![SaltStack Logo](./images/saltstack-logo.png)

# 文档内容目录结构
+ [Introduction to Salt 产品介绍](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/01.Introduction-to-Salt-SaltStack-简介.md)
+ [SaltStack Get Started Tutorial 快速入门教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/02.SaltStack-Get-Started-快速入门教程.md)
    - [Understanding SaltStack 理解运行原理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-1.Understanding-SaltStack-理解运行原理.md)
    - [SaltStack Fundamentals 基础知识](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-2.SaltStack-Fundamentals-基础知识.md)
    - [SaltStack Configuration Management 配置管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-3.Configuration-Management-配置管理.md)
    - [Event Driven Infrastructure 事件驱动的基础设施](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-4.Event-Driven-Infrastructure-基于事件驱动的基础设施.md)
    - [Agentless SaltStack SaltStack的免代理方式](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-5.Agentless-SaltStack-SaltStack的免代理方式.md)
    - [SaltStack Components, Flexibility and Speed 组件、灵活性及速度](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter02/02-6.SaltStack-Compoents-and-Flexibity-and-Speed-SaltStack组件与灵活性以及速度.md)
+ [Installation 安装指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md)
    - [Quick Install 快速安装](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#快速安装)
    - [Platform-specific Installation Instructions 特定系统平台的安装](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#特定系统平台的安装)
    - [Initial Configuration 初始化配置说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#初始化配置说明)
    - [Additional Installation Guides 补充安装说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#补充安装说明)
    - [Dependencies 依赖性的说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#依赖性的说明)
    - [Optional Dependencies 可选的依赖性](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#可选的依赖性)
    - [Upgrading Salt Salt升级](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#salt升级)
    - [Building Packages using Salt Pack 使用Salt Pack构建软件包](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/03.Installation-安装指南.md#使用salt-pack构建软件包)
+ [Configuring Salt Salt配置指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/04.Configuring-Salt-Salt配置指南.md)
    - [Configuring the Salt Master - Salt Master配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-1-0.Configuring-the-Salt-Master-Salt-Master配置.md)
    - [Configuring the Salt Minion - Salt Minion配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-2-0.Configuring-the-Salt-Minion-Salt-Minion配置.md)
    - [Configuring the Salt Proxy Minion - Salt Proxy Minion配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-3-0.Configuring-the-Salt-Proxy-Minion.md)
    - [Configuration file examples - 配置文件示例](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-4-0.Configuration-File-Examples.md)
    - [Minion Blackout Configuration - Minion Blackout(管制模式)配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-5-0.Minion-Blackout-Configuration.md)
    - [Access Control System - 访问控制系统](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-6-0.Access-Control-System.md)
    - [Job Management - Job作业管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-7-0.Job-JobCache-JobResult-Management.md)
    - [Managing the Job Cache - Job Cache作业缓存管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-7-0.Job-JobCache-JobResult-Management.md#MANAGING-THE-JOB-CACHE)
    - [Storing Job Results in an External System - 将Job作业结果存储在外部系统中](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-7-0.Job-JobCache-JobResult-Management.md#STORING-JOB-RESULTS-IN-AN-EXTERNAL-SYSTEM)
    - [Logging - 日志系统配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-8-0.Logging-External-Logging-Handlers.md)
    - [External Logging Handlers - 外部日志记录处理程序](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-8-0.Logging-External-Logging-Handlers.md#external-logging-handlers)
    - [Salt File Server - Salt文件服务器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-9-0.Salt-File-Server-and-Git-MinionFS-Backend.md)
    - [Git Fileserver Backend Walkthrough - 配置GitFS作为后端文件服务器的教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-9-0.Salt-File-Server-and-Git-MinionFS-Backend.md#git-fileserver-backend-walkthrough)
    - [MinionFS Backend Walkthrough - 配置MinionFS作为后端文件服务器的教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-9-0.Salt-File-Server-and-Git-MinionFS-Backend.md#minionfs-backend-walkthrough)
    - [Salt Package Manager - Salt包管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-10-0.Salt-Package-Manager.md)
    - [Storing Data in Other Databases - 将数据存储在其他数据库系统中](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-11-0.Salt-sdb-nonroot-and-cron.md)
    - [Running the Salt Master/Minion as an Unprivileged User - 使用非特权用户运行Salt Master/Minion](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-11-0.Salt-sdb-nonroot-and-cron.md#RUNNING-THE-SALT-MASTER-OR-MINION-AS-AN-UNPRIVILEGED-USER)
    - [Using cron with Salt - 通过cron定时执行Salt配置任务](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-11-0.Salt-sdb-nonroot-and-cron.md#USING-CRON-WITH-SALT)
    - [Hardening Salt - Salt安全加固](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-12-0.Hardening-Salt-and-Security-Disclosure-Policy.md)
    - [Security disclosure policy - 安全披露政策](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-12-0.Hardening-Salt-and-Security-Disclosure-Policy.md#SECURITY-DISCLOSURE-POLICY-安全披露政策)
    - [Salt Transport - Salt通信与传输](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-13-0.Salt-Transport.md)
    - [Master Tops System - Master Tops系统](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-14.Master-Tops-System.md)
    - [Returners - Salt 作业结果数据返回器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-15.Returners.md)
    - [Renderers - Salt 渲染器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter04/04-16.Renderers.md)
+ [Using Salt 使用指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/05.Using-Salt-使用指南.md)
    - [Grains](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-1.Grains.md)
    - [Storing Static Data in the Pillar - 使用Pillar存放静态数据](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-2.Storing-Static-Data-in-the-Pillar.md)
    - [Pillar Walkthrough - Pillar实战演练](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-2-1.Pillar-Walkthrough-Pillar-实战演练.md)
    - [Targeting Minions - Minions目标定位](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-3.Targeting-Minions.md)
    - [The Salt Mine - 管理grains的数据变化](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-4.The-Salt-Mine.md)
    - [Runners - Salt 运行器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-5.Runners-and-Salt-Engines.md#RUNNERS)
    - [Salt Engines - Salt 引擎](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-5.Runners-and-Salt-Engines.md#SALT-ENGINES)
    - [Understanding YAML - 理解YAML](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-6.Understanding-YAML.md)
    - [Understanding Jinja - 理解Jinja](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-7.Understanding-Jinja.md)
    - [Tutorials Index - 各种Salt使用教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-8-0.Tutorials-Index-使用教程索引目录.md)
    - [Troubleshooting - 故障排查指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-9.Troubleshooting.md)
    - [Frequently Asked Questions - Salt在使用中经常被问到的一些问题](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-10.Frequently-Asked-Questions.md)
    - [Salt Best Practices - SaltStack最佳实践](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-11.Salt-Best-Practices.md)
+ [Remote Execution 远程执行模块](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/06.Remote-Execution-远程执行系统.md)
    - [Remote execution tutorial - 远程执行模块使用教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter06/06-1.Remote-exection-tutorial.md)
    - [Running Commands on Salt Minions - 在Salt Minions上运行管理命令](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter06/06-2.Running-Commands-on-Salt-Minions.md)
    - [Writing Execution Modules - 怎样开发一个执行模块](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter06/06-3.Writing-Execution-Modules.md)
    - [Executors - 程序执行器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter06/06-4.Executors.md)
+ [Configuration Management - 配置管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/07.Configuration-Management-配置管理.md)
    - [States tutorial, part 1 - Basic Usage 基本用法](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-8-16.States-tutorial.md#PART-1---BASIC-USAGE)
    - [States tutorial, part 2 - More Complex States, Requisites 更复杂的STATES、REQUISITES](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-8-16.States-tutorial.md#PART-2---MORE-COMPLEX-STATES-AND-REQUISITES)
    - [States tutorial, part 3 - Templating, Includes, Extends 模板、包含和扩展](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-8-16.States-tutorial.md#PART-3---TEMPLATING-AND-INCLUDES-AND-EXTENDS)
    - [States tutorial, part 4 - Set Up a Workflow by Salt states 使用Salt states建立一个上线发布的工作流](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter05/05-8-16.States-tutorial.md#PART-4---Set-Up-a-Workflow-by-Salt-states)
    - [State System Reference - State状态系统参考资料](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter07/07-1.State-System-Reference.md)
+ [Return Codes - 返回码](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/08.Return-Code.md)
+ [Utility Modules - Code Reuse in Custom Modules](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/09.Utility-Modules-Code-Reuse-in-Custom-Modules.md)
+ [Events & Reactor - 事件与反应器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/10.Events-and-Reactor.md)
    - [Event System - 事件系统](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter10/10-1.Event-System.md)
    - [Beacons - 信标](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter10/10-3.Salt-Beacons.md)
    - [Reactor System - 反应器系统](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter10/10-4.Salt-Reactor-System.md)
+ [Orchestration 服务编排](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/11.Orchestration-服务编排.md)
+ [Solaris 配置说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/12.Solaris.md)
+ [Salt SSH 使用说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/13.Salt-SSH.md)
+ [Thorium Complex Reactor](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/14.Thorium-Complex-Reactor.md)
+ [Salt Cloud - Salt云管理模块完全指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md)
    - [Configuration - 配置文件](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md)
    - [Configuration Inheritance - 配置的继承](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#Configuration-Inheritance---配置的继承)
    - [QuickStart - 快速入门](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#QuickStart---快速入门)
    - [Using Salt cloud - Salt cloud模块使用指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#Using-Salt-cloud---Salt-cloud模块使用指南)
    - [Core Configuration - 核心配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#Core-Configuration---核心配置)
    - [Windows Configuration - 怎样使用Salt Cloud管理Windows实例](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#Windows-Configuration---怎样使用Salt-Cloud管理Windows实例)
    - [Cloud Provider Specifics - 针对特定云平台的Salt Cloud配置方法](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/15.Salt-Cloud.md#Cloud-Provider-Specifics---针对特定云平台的Salt-Cloud配置方法)
    - [Miscellaneous Options - 一些零散的配置项](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-33.Salt-Cloud-Miscellaneous-Options.md)
    - [Troubleshooting Steps - Salt Cloud故障排查步骤](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-34.TroubleShooting-Salt-Cloud.md)
    - [Extending Salt Cloud and Adding Cloud Providers - 开发一个云平台驱动程序](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-35.Extending-Salt-Cloud-Adding-Cloud-Providers.md)
    - [Extending Salt Cloud and Adding OS Support - bootstrap-salt部署脚本的扩展使用](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-36.Extending-Salt-Cloud-Adding-OS-Support.md)
    - [Using Salt Cloud from Salt - 在Salt的主要功能模块中使用Salt Cloud的方法](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-37.Using-Salt-Cloud-from-Salt.md)
    - [Feature Comparison - Salt Cloud对各云平台的功能支持比较](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-38.Salt-Cloud-Feature-Comparison.md)
    - [Using Salt Cloud with the Event Reactor - 在Reactor事件反应器中使用Salt Cloud](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter15/15-39.Using-Salt-Cloud-with-the-Event-Reactor.md)
+ [Salt Proxy Minion - Salt代理客户端](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/16.Salt-Proxy-Minion.md)
    - [Getting Started](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/16.Salt-Proxy-Minion.md#Getting-Started)
    - [关于`__proxyenabled__`指令](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/16.Salt-Proxy-Minion.md#proxyenabled-directive)
    - [SSH Proxymodules](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/16.Salt-Proxy-Minion.md#SSH-Proxymodules)
+ [Network Automation - 网络自动化配置](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/21.Network-Automation.md)
    - [New in Carbon](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/21.Network-Automation.md#New-in-Carbon)
    - [NAPALM](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/21.Network-Automation.md#NAPALM)
    - [JUNOS](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/21.Network-Automation.md#JUNOS)
+ [Pillars](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/22.Pillars.md)
+ [Command Line Reference - 命令行命令使用参考](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/17.Command-Line-Reference.md)
    - [salt-call](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-1.salt-call.md)
    - [salt](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-2.salt.md)
    - [salt-cloud](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-3.salt-cloud.md)
    - [salt-cp](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-4.salt-cp.md)
    - [salt-extend](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-5.salt-extend.md)
    - [salt-key](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-6.salt-key.md)
    - [salt-master](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-7.salt-master.md)
    - [salt-minion](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-8.salt-minion.md)
    - [salt-proxy](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-9.salt-proxy.md)
    - [salt-run](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-10.salt-run.md)
    - [salt-ssh](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-11.salt-ssh.md)
    - [salt-syndic](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-12.salt-syndic.md)
    - [salt-unity](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-13.salt-unity.md)
    - [salt-api](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-14.salt-api.md)
    - [spm](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter17/17-15.spm.md)
+ [Salt Virt 虚拟化模块](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/18.Salt-Virt.md)
    - [Salt Virt Tutorial - 虚拟化配置教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/18.Salt-Virt.md#Salt-Virt-Tutorial)
    - [The Salt Virt Runner - Salt Virt Runner运行器](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/18.Salt-Virt.md#Salt-Virt-Tutorial)
    - [Based on Live State Data - 使用在线状态数据](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/18.Salt-Virt.md#Based-on-Live-State-Data)
    - [Deploy for Network or Disk - 部署虚拟机的网络或磁盘](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/18.Salt-Virt.md#Deploy-for-Network-or-Disk)
+ [SaltStack APIs](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/19.APIs.md)
    - [Python client API - SaltStack Python客户端程序API开发指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter19/19-01.Python-client-API-Python客户端程序API接口.md)
    - [netapi modules - SaltStack netapi模块开发指南](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter19/19-02.netapi-modules.md)
    - [netapi模块——rest_cherrypy](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter19/19-05.netapi-modules-rest-cherrypy.md)
    - [netapi模块——rest_tornado](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter19/19-06.netapi-modules-rest-tornado.md)
    - [netapi模块——rest_wsgi](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter19/19-07.netapi-modules-rest-wsgi.md)
+ [Architecture SaltStack 高可用架构](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/20.Architecture-SaltStack高可用架构.md)
    - [High Availability Features in Salt - Salt中的高可用性功能](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter20/20-1.High-Availability-Features-in-Salt-Salt中的高可用性功能.md)
    - [Salt Syndic - Salt分区管理](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter20/20-4.SALT-SYNDIC-Salt分区管理.md)
    - [Using Salt at scale - 在更大规模范围内使用Salt时会遇到的一些问题](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter20/20-5.Using-Salt-at-scale-在更大规模范围内使用Salt时会遇到的一些问题.md)
    - [Multi Master Tutorial - Multimaster架构的配置教程](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter20/20-2.MULTI-MASTER-TUTORIAL-Multimaster架构的配置教程.md)
    - [Multi-Master-PKI Tutorial With Failover - 给合使用PKI和failover的Multimaster架构](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/chapter20/20-3.Multi-Master-PKI-Tutorial-With-Failover-给合使用PKI和failover的Multimaster架构.md)
+ [Windows](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/23.Windows.md)
+ [Master Tops](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/26.Master-Tops.md)
+ [Minion Data Cache - Minion数据缓存](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/28.Minion-Data-Cache.md)
+ [Slots](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/29.Slots.md)
+ [Salt2019.2.0 Release Notes (Codename Fluorine) 新版本功能特性说明](https://github.com/watermelonbig/SaltStack-Chinese-ManualBook/blob/master/25.Salt2019.2.0-Release-Notes-Codename-Fluorine-Salt2019.2.0版本功能特性说明.md)
