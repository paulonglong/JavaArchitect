- [JavaSE](#javaSE)
  - [基础](#基础)
  - [容器](#容器)
  - [并发](#并发)
  - [JVM](#jvm)
  - [新特性](#新特性)
  - [编码之道](#编码之道)
  - [工具](#工具)
  
- [JavaEE](#javaEE)
  - [基础知识](#基础知识)
  - [Spring/SpringBoot](#Spring/SpringBoot)

- [网络](#网络)

- [操作系统](#操作系统)

- [数据结构与算法](#数据结构与算法)
  - [数据结构](#数据结构)
  - [算法](#算法)

- [系统架构](#系统架构)
  - [MySQL](#mysql)
  - [Redis](#redis)
  - [Netty](#netty)
  - [ZooKeeper](#zookeeper)
  - [安全](#安全)
    - [认证授权](#认证授权)
    - [数据脱敏](#数据脱敏)
  - [分布式架构](#分布式架构)
    - [CAP 理论](#CAP 理论)
    - [BASE 理论](#BASE 理论)
  - [高并发](#高并发)
    - [分布式 id](#分布式 id)
    - [RPC](#RPC)
    - [API 网关](#API 网关)
    - [微服务](#微服务)
    - [消息队列](#消息队列)
    - [负载均衡](#负载均衡)
    - [读写分离](#读写分离)
    - [分库分表](#分库分表)
  - [高可用](#高可用)
    - [限流](#限流)
    - [降级](#降级)
    - [熔断](#熔断)
    - [排队](#排队)
    - [集群](#集群)
    - [超时和重试机制](#超时和重试机制)

## JavaSE
### 基础
 - **知识点/面试题:**
  - **[Java 基础知识](docs/java/basis/Java基础知识.md)**
  - **[Java 基础知识疑难点/易错点](docs/java/basis/Java基础知识疑难点.md)**
 - **重要知识点详解：**
  - [枚举](docs/java/basis/用好Java中的枚举真的没有那么简单.md)
  - [Java 常见关键字总结：final、static、this、super!](docs/java/basis/Java常见关键字总结.md)
  - [什么是反射机制?反射机制的应用场景有哪些?](docs/java/basis/反射机制.md)
  - [BIO,NIO,AIO 总结 ](docs/java/basis/BIO,NIO,AIO总结.md)

### 容器
 - **[Java 容器常见面试题/知识点总结](docs/java/collection/Java集合框架常见面试题.md)** (必看 :+1:)
 - **源码分析** 
  - [ArrayList 源码+扩容机制分析](docs/java/collection/ArrayList源码+扩容机制分析.md) 
  - [LinkedList 源码](docs/java/collection/LinkedList源码分析.md) 
  - [HashMap(JDK1.8)源码+底层数据结构分析](<docs/java/collection/HashMap(JDK1.8)源码+底层数据结构分析.md>) 
  - [ConcurrentHashMap 源码+底层数据结构分析](docs/java/collection/ConcurrentHashMap源码+底层数据结构分析.md)

### 并发
 - **[多线程学习指南](./docs/java/multi-thread/多线程学习指南.md)**
 - **知识点/面试题:**
  - **[Java 并发基础常见面试题总结](docs/java/multi-thread/2020最新Java并发基础常见面试题总结.md)**
  - **[Java 并发进阶常见面试题总结](docs/java/multi-thread/2020最新Java并发进阶常见面试题总结.md)**
 - **重要知识点详解：**
  - **线程池**
   - [Java 线程池学习总结](./docs/java/multi-thread/java线程池学习总结.md)
   - [拿来即用的线程池最佳实践](./docs/java/multi-thread/拿来即用的线程池最佳实践.md)
  - [乐观锁与悲观锁](docs/essential-content-for-interview/面试必备之乐观锁与悲观锁.md)
  - [ ThreadLocal 关键字解析](docs/java/multi-thread/万字详解ThreadLocal关键字.md)
  - [并发容器总结](docs/java/multi-thread/并发容器总结.md)
  - [JUC 中的 Atomic 原子类总结](docs/java/multi-thread/Atomic原子类总结.md)
  - [AQS 原理以及 AQS 同步组件总结](docs/java/multi-thread/AQS原理以及AQS同步组件总结.md)

### JVM
 - **[Java 内存区域](docs/java/jvm/Java内存区域.md)**
 - **[JVM 垃圾回收](docs/java/jvm/JVM垃圾回收.md)**
 - [JDK 监控和故障处理工具](docs/java/jvm/JDK监控和故障处理工具总结.md)
 - [类文件结构](docs/java/jvm/类文件结构.md)
 - **[类加载过程](docs/java/jvm/类加载过程.md)**
 - [类加载器](docs/java/jvm/类加载器.md)
 - **[【待完成】最重要的 JVM 参数指南（翻译完善了一半）](docs/java/jvm/最重要的JVM参数指南.md)**
 - [JVM 配置常用参数和常用 GC 调优策略](docs/java/jvm/GC调优参数.md)
 - **[【加餐】大白话带你认识 JVM](docs/java/jvm/[加餐]大白话带你认识JVM.md)**

### 新特性
 - **Java 8**
  - [Java 8 新特性总结](docs/java/new-features/Java8新特性总结.md)
  - [Java8常用新特性总结](docs/java/new-features/java8-common-new-features.md) 
  - [Java 8 学习资源推荐](docs/java/new-features/Java8教程推荐.md)
  - [Java8 forEach 指南](docs/java/new-features/Java8foreach指南.md)
 - **Java9~Java14**
  - [一文带你看遍 JDK9~14 的重要新特性！](./docs/java/new-features/一文带你看遍JDK9到14的重要新特性.md)

### 编码之道
 - [Java 编程规范以及优雅 Java 代码实践总结](docs/java/Java编程规范.md)
 - [Java 命名之道](docs/system-design/naming.md)
 - [RestFul API 简明教程](docs/system-design/coding-way/RESTfulAPI简明教程.md)

### 工具
 - **Java**
  - [JAD 反编译](docs/java/JAD反编译tricks.md)
  - [手把手教你定位常见 Java 性能问题](./docs/java/手把手教你定位常见Java性能问题.md)
 - **Git**
  - [Git 入门](docs/tools/Git.md)
 - **Github**
  - [我使用Github 5 年总结了这些骚操作](docs/tools/Github技巧.md)
 - **Docker**
  - [Docker 基本概念解读](docs/tools/Docker.md) 
  - [一文搞懂 Docker 镜像的常用操作！](docs/tools/Docker-Image.md)

## JavaEE
### 基础知识
 - [《J2EE 基础知识》](docs/java/J2EE基础知识.md) 对 Java 后台技术发展有更深的认识。

### Spring/SpringBoot
 - **知识点/面试题:** 
  - [代理模式详解：静态代理+JDK/CGLIB 动态代理实战](docs/java/basis/代理模式详解.md)
  - **[Spring 常见问题总结](docs/system-design/framework/spring/Spring常见问题总结.md)**
  - **[SpringBoot 指南/常见面试题总结](https://github.com/Snailclimb/springboot-guide)**
  - **[面试常问：“讲述一下 SpringBoot 自动装配原理？”](https://www.cnblogs.com/javaguide/p/springboot-auto-config.html)**
 - **重要知识点详解：**
  - **[Spring/Spring Boot 常用注解总结！安排！](./docs/system-design/framework/spring/SpringBoot+Spring常用注解总结.md)** 
  - **[Spring 事务总结](docs/system-design/framework/spring/Spring事务总结.md)** 
  - [Spring 中都用到了那些设计模式?](docs/system-design/framework/spring/Spring-Design-Patterns.md)

## 网络
 - [计算机网络常见面试题](docs/network/计算机网络.md)
 - [计算机网络基础知识总结](docs/network/计算机网络知识总结.md)

## 操作系统
 - [操作系统常见问题总结！](docs/operating-system/basis.md)
 - [后端程序员必备的 Linux 基础知识](docs/operating-system/linux.md)
 - [Shell 编程入门](docs/operating-system/Shell.md)

## 数据结构与算法
### 数据结构
- **图解数据结构：**
 - [线性数据结构 :数组、链表、栈、队列](docs/dataStructures-algorithms/data-structure/线性数据结构.md)
 - [图](docs/dataStructures-algorithms/data-structure/图.md)
 - [不了解布隆过滤器？一文给你整的明明白白！](docs/dataStructures-algorithms/data-structure/bloom-filter.md)
### 算法
 - [算法学习书籍+资源推荐](https://www.zhihu.com/question/323359308/answer/1545320858) 。
 - [如何刷Leetcode?](https://www.zhihu.com/question/31092580/answer/1534887374) 
 - **常见算法问题总结：**
  - [几道常见的字符串算法题总结 ](docs/dataStructures-algorithms/几道常见的子符串算法题.md)
  - [几道常见的链表算法题总结 ](docs/dataStructures-algorithms/几道常见的链表算法题.md)
  - [剑指 offer 部分编程题](docs/dataStructures-algorithms/剑指offer部分编程题.md)

## 系统架构
### MySQL
 - **[【推荐】MySQL/数据库 知识点总结](docs/database/MySQL.md)**
 - **[阿里巴巴开发手册数据库部分的一些最佳实践](docs/database/阿里巴巴开发手册数据库部分的一些最佳实践.md)**
 - **[一千行 MySQL 学习笔记](docs/database/一千行MySQL命令.md)**
 - [MySQL 高性能优化规范建议](docs/database/MySQL高性能优化规范建议.md)
 - **重要知识点：**
  - [数据库索引总结 1](docs/database/MySQL%20Index.md)、[数据库索引总结 2](docs/database/数据库索引.md)
  - [事务隔离级别(图文详解)](<docs/database/事务隔离级别(图文详解).md>)
  - [一条 SQL 语句在 MySQL 中如何执行的](docs/database/一条sql语句在mysql中如何执行的.md)
  - **[关于数据库中如何存储时间的一点思考](docs/database/关于数据库存储时间的一点思考.md)**

### Redis
 - [Redis 常见问题总结](docs/database/Redis/redis-all.md)
 - [面试/工作必备！3种常用的缓存读写策略！](docs/database/Redis/3种常用的缓存读写策略.md)

### Netty
 - [剖析面试最常见问题之 Netty（上）](https://xiaozhuanlan.com/topic/4028536971)
 - [剖析面试最常见问题之 Netty（下）](https://xiaozhuanlan.com/topic/3985146207)

### ZooKeeper
1. [【入门】ZooKeeper 相关概念](docs/system-design/distributed-system/zookeeper/zookeeper-intro.md)
2. [【进阶】ZooKeeper 相关总结](docs/system-design/distributed-system/zookeeper/zookeeper-plus.md)
3. [【实战】ZooKeeper 实战](docs/system-design/distributed-system/zookeeper/zookeeper-in-action.md)

### 安全
#### 认证授权
 - **[《认证授权基础》](docs/system-design/authority-certification/basis-of-authority-certification.md)** 
 - **JWT**
  - JSON Web Token是一种身份认证的方式，JWT 本质上就一段签名的 JSON 格式的数据。由于它是带有签名的，因此接收者便可以验证它的真实性
  - [JWT 优缺点分析以及常见问题解决方案](docs/system-design/authority-certification/JWT优缺点分析以及常见问题解决方案.md)
  - [适合初学者入门 Spring Security With JWT 的 Demo](https://github.com/Snailclimb/spring-security-jwt-guide)
 - **SSO(单点登录)**
  - Single Sign On 即单点登录说的是用户登陆多个子系统的其中一个就有权访问与其相关的其他系统。
  - [SSO 单点登录看这篇就够了！](docs/system-design/authority-certification/SSO单点登录看这一篇就够了.md)
#### 数据脱敏
 - [大厂也在用的 6种 数据脱敏方案，严防泄露数据的 “内鬼”](https://www.cnblogs.com/chengxy-nds/p/14107671.html)
 - [【进阶之路】基于ShardingSphere的线上业务数据脱敏解决方案](https://juejin.cn/post/6906074730437836813)

### 分布式架构
 - [8 张图读懂大型网站技术架构](docs/system-design/website-architecture/8%20张图读懂大型网站技术架构.md)
 - [关于大型网站系统架构你不得不懂的 10 个问题](docs/system-design/website-architecture/关于大型网站系统架构你不得不懂的10个问题.md)
#### CAP 理论
 - **Consistency（一致性）**
 - **Availability（可用性）**
 - **Partition Tolerance（分区容错性）**
 - [《CAP理论解读》](docs/system-design/distributed-system/CAP理论.md)
#### BASE 理论
 - **Basically Available（基本可用）** 
 - **Soft-state（软状态）**
 - **Eventually Consistent（最终一致性）**
 - [《BASE理论解读》](docs/system-design/distributed-system/BASE理论.md)

### 高并发
#### 分布式 id
 - 在复杂分布式系统中，往往需要对大量的数据和消息进行唯一标识。
 - [为什么要分布式 id ？分布式 id 生成方案有哪些？](docs/system-design/micro-service/分布式id生成方案总结.md)
#### RPC
 - RPC 让调用远程服务调用像调用本地方法那样简单。
 - [Dubbo 总结：关于 Dubbo 的重要知识点](docs/system-design/distributed-system/rpc/关于Dubbo的重要知识点.md)
 - [服务之间的调用为啥不直接用 HTTP 而用 RPC？](docs/system-design/distributed-system/rpc/服务之间的调用为啥不直接用HTTP而用RPC.md)
 - [一款基于 Netty+Kyro+Zookeeper 实现的自定义 RPC 框架](https://github.com/Snailclimb/guide-rpc-framework)
#### API 网关
 - 网关主要用于请求转发、安全认证、协议转换、容灾。
 - [为什么要网关？你知道有哪些常见的网关系统？](docs/system-design/distributed-system/api-gateway/为什么要网站有哪些常见的网站系统.md)
 - [如何设计一个亿级网关(API Gateway)？](docs/system-design/distributed-system/api-gateway/如何设计一个亿级网关.md)
#### 微服务
 - [ 大白话入门 Spring Cloud](docs/system-design/micro-service/spring-cloud.md)
 - [微服务/分布式大厂真实面试问题解答](https://xiaozhuanlan.com/topic/2895047136)
#### 消息队列
 - 消息队列在分布式系统中主要是为了解耦和削峰。
 - [消息队列总结](docs/system-design/distributed-system/message-queue/message-queue.md)
 - [RabbitMQ 入门](docs/system-design/distributed-system/message-queue/RabbitMQ入门看这一篇就够了.md)
 - [RocketMQ 入门](docs/system-design/distributed-system/message-queue/RocketMQ.md)、
 - [RocketMQ 的几个简单问题与答案](docs/system-design/distributed-system/message-queue/RocketMQ-Questions.md)
 - [Kafka 常见面试题总结](docs/system-design/distributed-system/message-queue/Kafka常见面试题总结.md)
#### 负载均衡
 - 负载均衡系统通常用于将任务比如用户请求处理分配到多个服务器处理以提高网站、应用或者数据库的性能和可靠性。
 - 常见的负载均衡系统包括 3 种：
 - **DNS 负载均衡** ：一般用来实现地理级别的均衡。
 - **硬件负载均衡** ： 通过单独的硬件设备比如 F5 来实现负载均衡功能（硬件的价格一般很贵）。
 - **软件负载均衡** ：通过负载均衡软件比如 Nginx 来实现负载均衡功能。
#### 读写分离
 - 读写分离主要是为了将数据库的读和写操作分不到不同的数据库节点上。
 - 主服务器负责写，从服务器负责读。另外，一主一从或者一主多从都可以。
 - **读写分离可以大幅提高读性能，小幅提高写的性能**
#### 分库分表
 - **分库分表是为了解决由于库、表数据量过大，而导致数据库性能持续下降的问题。** 
 - 常见的分库分表工具有：`sharding-jdbc`（当当）、`TSharding`（蘑菇街）、`MyCAT`（基于 Cobar）、`Cobar`（阿里巴巴）...。
 - **推荐使用 `sharding-jdbc`** 

### 高可用
 - 高可用描述的是一个系统在大部分时间都是可用的，可以为我们提供服务的。
 - 高可用代表系统即使在发生硬件故障或者系统升级的时候，服务仍然是可用的 。
 - **《[如何设计一个高可用系统？要考虑哪些地方？](docs/system-design/high-availability/如何设计一个高可用系统要考虑哪些地方.md)》** 
#### 限流
 - 限流是从用户访问压力的角度来考虑如何应对系统故障。
 - 限流为了对服务端的接口接受请求的频率进行限制，防止服务挂掉。
 - 比如某一接口的请求限制为 100 个每秒, 对超过限制的请求放弃处理或者放到队列中等待处理。限流可以有效应对突发请求过多。
 - 相关阅读：[限流算法有哪些？](docs/system-design/high-availability/limit-request.md)
#### 降级
 - 降级是从系统功能优先级的角度考虑如何应对系统故障。
 - 服务降级指的是当服务器压力剧增的情况下，根据当前业务情况及流量对一些服务和页面有策略的降级，以此释放服务器资源以保证核心任务的正常运行。
#### 熔断
 - 熔断和降级是两个比较容易混淆的概念，两者的含义并不相同。
 - 降级的目的在于应对系统自身的故障，而熔断的目的在于应对当前系统依赖的外部系统或者第三方系统的故障。
#### 排队
 - 另类的一种限流，类比于现实世界的排队。玩过英雄联盟的小伙伴应该有体会，每次一有活动，就要经历一波排队才能进入游戏。
#### 集群
 - 相同的服务部署多份，避免单点故障。
#### 超时和重试机制
 - **一旦用户的请求超过某个时间得不到响应就结束此次请求并抛出异常。** 
 - 如果不进行超时设置可能会导致请求响应速度慢，甚至导致请求堆积进而让系统无法在处理请求。
 - 另外，重试的次数一般设为 3 次，再多次的重试没有好处，反而会加重服务器压力（部分场景使用失败重试机制会不太适合）。
