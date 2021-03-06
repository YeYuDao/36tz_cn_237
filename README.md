# 36tz_cn_237
一站式学习Redis， 从入门到高可用分布式实践
一站式学习Redis， 从入门到高可用分布式实践
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fd1889e0979ac1105400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 Redis初识 

#### 带领听众进入Redis的世界，了解它的前世今生、众多特性、应用场景、安装配置、简单使用，可以让听众对Redis有一个全面的认识。
1-1 导学 (07:38)

1-2 Redis初识 (04:13)

1-3 谁在使用Redis (01:43)

1-4 redis特性目录 (01:15)

1-5 特性1-速度快 (03:21)

1-6 特性2-持久化 (01:33)

1-7 特性3-数据结构 (02:50)

1-8 特性4-多语言客户端 (00:31)

1-9 特性5-功能丰富 (00:30)

1-10 特性6-简单 (01:33)

1-11 特性7-复制 (00:29)

1-12 特性8-高可用分布式 (00:47)

1-13 redis典型使用场景 (06:14)

1-14 redis三种启动方式介绍 (09:26)

1-15 redis常用配置 (02:35)

1-16 redis安装启动演示 (09:08)


### 第2章 API的理解和使用

#### 全面介绍了Redis提供的5种数据结构字符串（string）、哈希（hash）、列表（list）、集合（set）、有序集合（zset）的数据模型、常用命令、典型应用场景。同时本章还会对Redis的单线程处理机制、键值管理做一个全面介绍，通过对这些原理的理解，听众可以在合适的应用场景选择合适的数据结构。 ...
2-1 -课程目录 (01:22)

2-2 -通用命令 (12:46)

2-3 数据结构和内部编码 (03:21)

2-4 单线程 (04:48)

2-5 字符串 (20:23)

2-6 hash (1) (06:01)

2-7 hash (2) (10:48)

2-8 list(1) (02:45)

2-9 list(2) (10:33)

2-10 set (10:27)

2-11 zset (16:55)


### 第3章 Redis客户端的使用

#### 本章重点关注Redis客户端的开发，介绍了详细讲解了Java客户端Jedis,简单介绍下Python和Go语言的Redis客户端的选择和使用。
3-1 课程目录 (01:01)

3-2 Java客户端：Jedis (11:28)

3-3 Python客户端：redis-py (07:33)

3-4 Go客户端：redigo简介 (02:16)

3-5 Jedis配置优化（上） (06:11)

3-6 Jedis配置优化（下） (10:03)


### 第4章 瑞士军刀Redis其他功能

#### 除了5种数据结构外，Redis还提供了诸如慢查询、Pipeline、Bitmap、HyperLogLog、发布订阅、GEO等附加功能，在这些功能的帮助下，Redis的应用场景更加丰富。
4-1 课程目录 (01:03)

4-2 慢查询 (09:49)

4-3 pipeline (08:58)

4-4 发布订阅 (07:12)

4-5 bitmap (11:25)

4-6 hyperloglog (07:54)

4-7 geo (06:15)


### 第5章 Redis持久化的取舍和选择

#### Redis的持久化功能有效避免因进程退出造成的数据丢失问题，本章将介绍介绍RDB和AOF两种持久化配置和运行流程，以及选择策略
5-1 目录 (01:03)

5-2 持久化的作用 (02:52)

5-3 RDB(1) (08:16)

5-4 RDB(2) (14:18)

5-5 RDB(3) (03:46)

5-6 AOF(1) (08:10)

5-7 AOF(2) (10:37)

5-8 AOF实验 (04:54)

5-9 RDB和AOF抉择 (08:05)


### 第6章 常见的持久化开发运维问题

#### 本章探讨了常见的持久化问题进行定位和优化，最后结合Redis常见的单机多实例部署场景进行优化
6-1 常见问题目录 (00:43)

6-2 fork (03:37)

6-3 子进程开销和优化 (04:57)

6-4 AOF阻塞 (02:44)


### 第7章 Redis复制的原理与优化

#### 复制是实现高可用的基石，但复制同样是运维的痛点，本部分详细分析复制的原理，讲解运维过程中可能遇到的问题。
7-1 目录 (01:13)

7-2 什么是主从复制 (05:49)

7-3 主从复制配置-介绍 (05:07)

7-4 主从复制配置-操作 (13:13)

7-5 runid和复制偏移量 (04:06)

7-6 全量复制 (03:22)

7-7 全量复制开销 + 部分复制 (03:48)

7-8 故障处理 (05:49)

7-9 主从复制常见问题 (15:29)


### 第8章 Redis Sentinel

#### 本章将一步步解析Redis Sentinel的相关概念、安装部署、配置、客户端路由、原理解析，最后分析了Redis Sentinel运维中的一些问题。
8-1 sentinel-目录 (01:06)

8-2 主从复制高可用？ (03:57)

8-3 redis sentinel架构 (04:44)

8-4 redis sentinel安装与配置 (06:24)

8-5 redis sentinel安装演示-1 (03:32)

8-6 redis sentinel安装演示-2 (09:44)

8-7 java客户端 (06:42)

8-8 python客户端 (01:19)

8-9 实现原理-1-故障转移演练 (08:19)

8-10 实现原理-2.故障转移演练(客户端) (03:58)

8-11 实现原理-3.故障演练(日志分析) (06:48)

8-12 三个定时任务 (05:34)

8-13 主观下线和客观下线 (04:48)

8-14 领导者选举 (04:06)

8-15 故障转移 (05:52)

8-16 常见开发运维问题-目录 (00:33)

8-17 节点运维 (05:20)

8-18 高可用读写分离 (09:26)

8-19 本章总结 (04:32)


### 第9章 初识Redis Cluster

#### Redis Cluster是Redis 3提供的分布式解决方案，有效解决了Redis分布式方面的需求，同时它也是学习分布式存储的绝佳案例。本章将针对Redis Cluster的数据分布，搭建集群进行分析说明。
9-1 本章目录 (02:54)

9-2 呼唤集群 (05:34)

9-3 数据分布概论 (05:50)

9-4 节点取余分区 (04:50)

9-5 一致性哈希分区 (05:32)

9-6 虚拟槽哈希分布 (04:47)

9-7 基本架构 (07:36)

9-8 原生安装 (07:54)

9-9 原生安装-1.准备节点 (05:45)

9-10 原生安装-2.节点握手 (02:29)

9-11 原生安装-3.分配槽 (09:23)

9-12 原生安装-4.分配主从 (04:40)

9-13 ruby环境准备-说明 (02:05)

9-14 ruby环境准备-操作 (03:48)

9-15 redis-trib构建集群 (08:06)

9-16 原生命令和redis-trib.rb对比 (02:20)


### 第10章 深入Redis Cluster

#### 本章将针对Redis Cluster的集群伸缩，请求路由，故障转移等方面进行分析说明。
10-1 集群伸缩目录 (01:07)

10-2 集群伸缩原理 (01:40)

10-3 扩展集群-1.加入节点 (01:36)

10-4 扩展集群-2.加入集群 (02:57)

10-5 扩展集群-3.迁移槽和数据 (07:12)

10-6 集群扩容演示-1 (03:33)

10-7 集群扩容演示-2 (04:07)

10-8 集群缩容-说明 (02:11)

10-9 集群缩容-操作 (07:29)

10-10 客户端路由-目录 (01:00)

10-11 moved异常说明和操作 (05:13)

10-12 ask重定向 (02:50)

10-13 smart客户端实现原理 (04:49)

10-14 JedisCluster执行源码分析 (04:34)

10-15 smart客户端JedisCluster-目录 (00:56)

10-16 JedisCluster基本使用 (01:57)

10-17 整合spring-1 (05:28)

10-18 整合spring-2 (06:35)

10-19 多节点操作命令 (02:04)

10-20 批量操作优化 (06:16)

10-21 故障转移-目录 (01:07)

10-22 故障发现 (05:06)

10-23 故障恢复 (04:06)

10-24 故障模拟 (09:44)

10-25 Redis Cluster常见开发运维问题-目录 (02:07)

10-26 集群完整性 (06:30)

10-27 带宽消耗 (05:56)

10-28 PubSub广播 (01:49)

10-29 集群倾斜-目录 (00:54)

10-30 数据倾斜 (08:00)

10-31 请求倾斜 (01:41)

10-32 读写分离 (03:54)

10-33 数据迁移 (05:29)

10-34 集群vs单机 (03:43)

10-35 本章总结 (04:30)


### 第11章 缓存设计与优化 

#### 讲解将缓存加入应用架构后带来的一些问题，这些问题常常会成为应用的致命点。
11-1 目录 (01:25)

11-2 缓存的受益和成本 (06:36)

11-3 缓存的更新策略 (07:09)

11-4 缓存粒度问题 (05:14)

11-5 缓存穿透问题 (12:30)

11-6 缓存雪崩优化 (09:53)

11-7 无底洞问题 (07:32)

11-8 热点key的重建优化 (11:45)

11-9 本章总结 (02:41)


### 第12章 Redis云平台CacheCloud

#### 本章结合前面的知识介绍redis规模化后使用云平台如何进行机器部署、应用接入、用户相关功能维护等问题
12-1 _目录 (01:45)

12-2 _Redis规模化困扰 (05:27)

12-3 _快速构建 (05:25)

12-4 机器部署 (08:22)

12-5 应用接入 (13:34)

12-6 用户功能 (02:58)

12-7 运维功能 (03:20)


### 第13章 课程总结

#### 课程总结
13-1 _课程总结 (06:42)


### 第14章 增补：Redis布隆过滤器

#### 现有50亿电话号码，如何快速判断10w个电话号码是否在其中？利用之前学习的bitmap和redis cluster构建分布式布隆过滤器
14-1 _目录_ (01:43)

14-2 引出布隆过滤器 (05:15)

14-3 布隆过滤器基本原理 (05:25)

14-4 布隆过滤器误差率 (04:40)

14-5 本地布隆过滤器 (04:18)

14-6 Redis布隆过器 (16:17)

14-7 Redis分布式布隆过滤器 (05:53)


### 第15章 Redis开发规范

#### 本章介绍键值的设计、命令的优化、连接池优化、客户端使用规范及客户端常见问题，带领用户全面梳理Redis开发规范。
15-1 key设计 (10:57)

15-2 value设计 (13:39)

15-3 发现bigkey的方法 (07:29)

15-4 bigkey的删除 (05:48)

15-5 选择合理的数据结构 (08:23)

15-6 键值生命周期的管理 (02:38)

15-7 命令优化技巧 (08:27)

15-8 java客户端优化 (07:46)

15-9 连接池参数优化1 (08:56)

15-10 连接池参数优化2 (04:14)

15-11 连接池参数优化3 (06:29)


### 第16章 内存管理 

#### 本章主要讲解Redis内存消耗、组成分析、Redis内存管理设置及内存优化技巧。
16-1 Redis内存优化介绍 (02:20)

16-2 Redis内存消耗 (08:54)

16-3 客户端缓冲区 (12:03)

16-4 缓冲内存 (02:56)

16-5 对象内存 (05:42)

16-6 内存设置上限 (04:47)

16-7 内存回收策略 (05:07)

16-8 内存优化 (12:30)

16-9 客户端缓冲区优化 (09:15)


### 第17章 开发运维常见坑

#### 本章介绍Linux针对Redis的内核参数优化、Redis安全七个方法以及Redis热点key的发现方法。
17-1 redis开发运维那些坑 (04:36)

17-2 overcommit_memory参数讲解和演示 (09:06)

17-3 其它参数的讲解 (15:32)

17-4 安全的redis (08:24)

17-5 安全七法则 (08:44)

17-6 热点key (06:05)


[下载地址](http://www.36tz.cn "下载地址")
