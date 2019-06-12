
## 2019年最新总结，阿里，腾讯，百度，美团，头条等技术面试题目，以及答案，专家出题人分析汇总。持续更新中。

## 阿里篇

##### 1.1.1 如何实现一个高效的单向链表逆序输出？

##### 1.1.2 已知sqrt(2)约等于1.414，要求不用数学库，求sqrt(2)精确到小数点后10位

##### 1.1.3 给定一个二叉搜索树(BST)，找到树中第 K 小的节点

##### 1.1.4 LRU缓存机制

##### 1.1.5 关于epoll和select的区别，以下哪些说法是正确的

##### 1.1.6 从innodb的索引结构分析，为什么索引的 key 长度不能太长

##### 1.1.7 MySQL的数据如何恢复到任意时间点？

##### 1.1.8 NFS 和 SMB 是最常见的两种 NAS（Network Attached Storage）协议，当把一个文件系统同时通过 NFS 和 SMB 协议共享给多个主机访问时，以下哪些说法是错误的

##### 1.1.9 输入 ping IP 后敲回车，发包前会发生什么？

##### 1.2.0 请解释下为什么鹿晗发布恋情的时候，微博系统会崩溃，如何解决？

##### 1.2.1 现有一批邮件需要发送给订阅顾客，且有一个集群（集群的节点数不定，会动态扩容缩容）来负责具体的邮件发送任务，如何让系统尽快地完成发送？

##### 1.2.2 有一批气象观测站，现需要获取这些站点的观测数据，并存储到 Hive 中。但是气象局只提供了 api 查询，每次只能查询单个观测点。那么如果能够方便快速地获取到所有的观测点的数据？

##### 1.2.3 如何实现两金额数据相加（最多小数点两位）

##### 1.2.4 关于并行计算的一些基础开放问题

##### 1.2.5 请计算XILINX公司VU9P芯片的算力相当于多少TOPS，给出计算过程与公式

##### 1.2.6 一颗现代处理器，每秒大概可以执行多少条简单的MOV指令，有哪些主要的影响因素

##### 1.2.7 请分析 MaxCompute 产品与分布式技术的关系、当前大数据计算平台类产品的市场现状和发展趋势

##### 1.2.8 对大数据平台中的元数据管理是怎么理解的，元数据收集管理体系是怎么样的，会对大数据应用有什么样的影响

##### 1.2.9 你理解常见如阿里，和友商大数据平台的技术体系差异以及发展趋势和技术瓶颈，在存储和计算两个方面进行概述

##### 1.3.0 在云计算大数据处理场景中，每天运行着成千上万的任务，每个任务都要进行 IO 读写。存储系统为了更好的服务，经常会保证高优先级的任务优先执行。当多个作业或用户访问存储系统时,如何保证优先级和公平性

##### 1.3.1 最大频率栈

##### 1.3.2 给定一个链表，删除链表的倒数第N个节点，并且返回链表的头结点

##### 1.3.3 如果让你设计一个通用的、支持各种数据库秒级备份和恢复的系统，你会如何设计

##### 1.3.4 如果让你来设计一个支持数据库、NOSQL 和大数据之间数据实时流动的数据流及处理的系统，你会考虑哪些问题？如何设计？

##### 1.3.5 给定一个整数数组和一个整数，返回两个数组的索引，这两个索引指向的数字的加和等于指定的整数。需要最优的算法，分析算法的空间和时间复杂度

##### 1.3.6 假如给你一个新产品，你将从哪些方面来保障它的质量？

##### 1.3.7 请评估一下程序的执行结果？

<br>

## mysql

##### 2.1.0 主键 超键 候选键 外键

##### 2.1.1 数据库事务的四个特性及含义

##### 2.1.2 视图的作用，视图可以更改么？

##### 2.1.3 drop,delete与truncate的区别

##### 2.1.4 索引的工作原理及其种类

##### 2.1.5 连接的种类

##### 2.1.6 数据库范式

##### 2.1.7 数据库优化的思路

##### 2.1.8 存储过程与触发器的区别


<br>

## redis
---

<br>

## MongDB
---

<br>

## Zookeeper

---


<br>

## nginx篇
---
#### 4.0 请解释一下什么是Nginx?

#### 4.1 请列举Nginx的一些特性?

#### 4.2 请列举Nginx和Apache 之间的不同点?

#### 4.3 请解释Nginx如何处理HTTP请求。

#### 4.4 在Nginx中，如何使用未定义的服务器名称来阻止处理请求?

#### 4.5 使用“反向代理服务器”的优点是什么?

#### 4.6 请列举Nginx服务器的最佳用途。

#### 4.7 请解释Nginx服务器上的Master和Worker进程分别是什么?

#### 4.8 请解释你如何通过不同于80的端口开启Nginx?

#### 4.9  请解释是否有可能将Nginx的错误替换为502错误、503?

#### 5.0 在Nginx中，解释如何在URL中保留双斜线?

#### 5.1 请解释ngx_http_upstream_module的作用是什么?

#### 5.2 请解释什么是C10K问题，后来是怎么解决的？

#### 5.3 请陈述stub_status和sub_filter指令的作用是什么?

#### 5.4 解释Nginx是否支持将请求压缩到上游?

#### 5.5 解释如何在Nginx中获得当前的时间?

#### 5.6 用Nginx服务器解释-s的目的是什么?

#### 5.7 解释如何在Nginx服务器上添加模块?

#### 5.8 nginx中多个work进程是如何监听同一个端口的？如何处理客户连接的惊群问题？

#### 5.9 nginx程序的热更新是如何做的？


<br/>
<br/>


#### 专家架构交流3群：783153655
#### 若群已满，添加QQ：469254771 , 备注github

