# 云计算 #
## 01云计算的概念 ##

### 云计算产生背景 ###
> 云计算驱动力：技术、需求、商业模式

### 云计算概念 ###
> #### 商业视角：云计算=信息电厂 ####
>> 1.计算和存储从局域网向互联网迁移  
 2.软件从终端向云端迁移  
 3.软件和硬件解耦，实现硬件共享  
 
> #### 技术角度：云计算=计算/存储的网络 ####
>> 分为狭义和广义云计算  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/01.png)

### 云计算的部署模式 ###
> 私有云、公有云、混合云

### 云计算的应用模式 ###
> IaaS：基础设施即服务：消费者-虚拟机租用、云盘等
>> 第一层叫做IaaS，有时候也叫做Hardware-as-a-Service，几年前如果你想在办公室或者公司的网站上运行一些企业应用，你需要去买服务器，或者别的高昂的硬件来控制本地应用，让你的业务运行起来。  
但是现在有IaaS，你可以将硬件外包到别的地方去。IaaS公司会提供场外服务器，存储和网络硬件，你可以租用。节省了维护成本和办公场地，公司可以在任何时候利用这些硬件来运行其应用。  
一些大的IaaS公司包括Amazon, Microsoft, VMWare, Rackspace和Red Hat.不过这些公司又都有自己的专长，比如Amazon和微软给你提供的不只是IaaS，他们还会将其计算能力出租给你来host你的网站。

> PaaS：平台即服务：面向专业开发者，可以加快SaaS应用的开发速度
>> 第二层就是所谓的PaaS，某些时候也叫做中间件。你公司所有的开发都可以在这一层进行，节省了时间和资源。  
PaaS公司在网上提供各种开发和分发应用的解决方案，比如虚拟服务器和操作系统。这节省了你在硬件上的费用，也让分散的工作室之间的合作变得更加容易。网页应用管理，应用设计，应用虚拟主机，存储，安全以及应用开发协作工具等。  
一些大的PaaS提供者有Google App Engine,Microsoft Azure，Force.com,Heroku，Engine Yard。最近兴起的公司有AppFog, Mendix 和 Standing Cloud

> SaaS：软件即服务：面向终端用户，例如网络邮箱
>> 第三层也就是所谓SaaS。这一层是和你的生活每天接触的一层，大多是通过网页浏览器来接入。任何一个远程服务器上的应用都可以通过网络来运行，就是SaaS了。
你消费的服务完全是从网页如Netflix, MOG, Google Apps, Box.NET, Dropbox或者苹果的iCloud那里进入这些分类。尽管这些网页服务是用作商务和娱乐或者两者都有，但这也算是云技术的一部分。  
一些用作商务的SaaS应用包括Citrix的GoToMeeting，Cisco的WebEx，Salesforce的CRM，ADP，Workday和SuccessFactors。

## 02云计算的价值 ##
### 行业客户反应的困难和挑战 ###
> * 复杂性与平滑过渡  
* 可靠性或SLA  
* 工作负载可迁移性  
* 数据安全性  
* 厂商锁定  
* 看不到投资回报  
### 云计算的价值体现--智能资源调度 ###
> 快速实现业务的负载均衡  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/02.png)
> 节能减排  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/03.png)

### 云计算的价值--提高资源利用率 ###
> 资源共享  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/04.png)
> 分时共享  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/05.png)

### 云计算的价值--分布式计算存储 ###
> ![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/06.png)

### 云计算的价值--统一管理 ###
> ![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/07.png)

### 云计算的价值--业务快速部署 ###
> ![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/08.png)


## 03虚拟化技术简介 ##
### 虚拟化的起源 ###
> ![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/09.png)

### 虚拟化的概念 ###
> 虚拟化是指通过虚拟化技术，将一台计算机虚拟为多台逻辑计算机，在一台计算机上同时运行多个逻辑计算机，每个逻辑计算机可运行不同的操作系统，并且，应用程序都可以在相互独立的空间内运行而互不影响，从而显著地提高计算机的工作效率。  
![alt](https://github.com/frankwtq/Huawei-Network/blob/master/01%E4%BA%91%E8%AE%A1%E7%AE%97/img/10.png)

### 虚拟化的主要内容 ###
> 计算虚拟化：CPU虚拟化、内存虚拟化、I/O虚拟化  
存储虚拟化：裸设备+逻辑卷、存储设备虚拟化、主机存储虚拟化+文件系统  
网络虚拟化：虚拟专用网VPN、虚拟网络VLAN  

### 虚拟化的本质 ###
> 分区：在单一物理服务器上可同时运行多个虚拟机，按需使用硬件资源池中的资源  
隔离：每个虚拟机之间嗾使隔离的，业务互不影响  
封装：整个虚拟机的执行环境封装在独立的文件中，可以通过移动复制这些文件来移动和复制该虚拟机  
独立：相对于硬件独立，虚拟机无需任何修改，可在任何物理服务器上运行，实现虚拟机的热迁移  
