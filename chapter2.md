# 第二章 云计算技术

###云计算技术：
####首先让大家明白什么是云端，所谓云端需要两层理解
* 服务不在本地，这一层可以理解为服务器
* 它和普通的服务器是不一样的，这些云端的服务器的资源是共享的，一旦一个服务器不能承受，将会把任务分配给其他机器。

###云技术与其他技术的区别：
&#160; &#160; &#160; &#160;云技术可以使用的语言有java,c++等。云技术的开发，并没有发展什么新语言，而是在其他语言的基础上。比如Java语言。与其他技术，最显著的区别，不是在开发上，而是在于架构上，最显著的特点是分布式。
###成熟的云计算技术：
* Hadoop
>&#160; &#160; &#160; &#160;Hadoop是一个框架，它是由Java语言来实现的。Hadoop是处理大数据技术.Hadoop可以处理云计算产生大数据，需要区分hadoop并不是云计算。它和云计算密不可分。  
&#160; &#160; &#160; &#160;Hadoop产生是互联网的产物，也是必然。大家都知道，我们上网时需要服务器的。假如世界上只有一台电脑，根本不需要服务器。如果有10台服务器，100台，1000台，上万台，那么我们该如何让大家相互通信，共享知识，所以我们产生了互联网。  
&#160; &#160; &#160; &#160;互联网产生，全世界都可以通信，知识如此居多，我们像获取更多的知识，想获取新技术，获取新知识，通过什么，国内通过百度，国外也有许多，比如Google。可是百度和谷歌的用户有多少，多了不说，最起码有上亿的用户。并且这些用户每天上百度，上谷歌，又会产生多少数据，查询多少数据。那么他们怎么承受如此多用户。  
&#160; &#160; &#160; &#160;这不是一台电脑、一台服务器能完成的事情。Hadoop就是一个解决方案。Hadoop是一个分布式方案，能够把压力分摊到其他服务器。至于如何做到的，可以深入了解Hadoop的maprecude等知识。

* openstack
>&#160; &#160; &#160; &#160;openstack是搭建云平台技术，可以搭建公有云，私有云，和混合云。OpenStack是开源的云管理平台，用来统一管理多个虚拟化集群的框架。
openstack目前分为两种:openstack的运维与openstack的二次开发
* Cloud Foundry
>&#160; &#160; &#160; &#160;Cloud Foundry是一个开源的平台即服务产品，它提供给开发者自由度去选择云平台，开发框架和应用服务。Cloud Foundry最初由 VMware 发起，得到了业界广泛的支持，它使得开发者能够更快更容易的开发，测试，部署和扩展应用。Cloud Foundry是一个开源项目，用户可以使用多种私有云发行版，也可以使用公共云服务。
* nosql
>&#160; &#160; &#160; &#160;nosql即not only sql。nosql数据库是一种比较低级的数据库，关系型数据库是由nosql数据库发展而来。
什么是关系型数据库，这里不从概念上区别，常用的SqlServer，mysql,oracle都是关系型数据库。关系型数据库顾名思义，数据库关系明确严谨。
而nosql则是一种数据关系不严谨的数据库。一个key和value。
