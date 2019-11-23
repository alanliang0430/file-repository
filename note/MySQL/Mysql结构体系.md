#一、MySQL 结构体系介绍
>本系列的文章是想把我理解的MySQL知识系统化的整理出来，这样做一是希望本人会对MySQL有更体系化和更深的理解，若同学们看到我文章有错误和理解偏差的地方，希望大家指正。二是希望能为刚刚学习数据库的同学提供思路。   
>   
>MySQL相关知识总结的第一篇，我先说明下我将从哪几方面介绍MySQL:
>>1.MySQL架构  
>>2.MySQL索引  
>>3.MySQL锁  
>>4.MySQL事务   
>>5.MySQL性能分析和性能优化  
>>6.MySQL集群   
>>7.MySQL分库分表   

##1.MySQL的逻辑架构   
想要MySQL展现出高效的性能，就必须了解MySQL的结构设计，和工作流程，MySQL逻辑架构图如下：   
![e](https://raw.githubusercontent.com/alanliang0430/file-repository/master/img-folder/MySQL/MySQL1.jpg)   

+ 连接器（Connectors）   
负责与其程序之间的交互，实现了开发者可以用不同开发语言进行数据库应用程序构建。
+ 系统管理和控制工具（Management Serveices & Utilities）
+ 连接池（Connection Pool）
+ SQL接口（SQL Interface）
+ 解析器（Parser）
+ 查询优化器（Optimizer）
+ 查询缓存（Cache和Buffer）
+ 存储引擎（Pluggable Storage Engines）
##2.

##3.MySQL的物理结构    
