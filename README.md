
以下是面试知识图谱，我会逐步完善下面文章，可能目前不是很完善，每周我会定期更新文章，大家可以去【公众号】搜索"Java面试公开课"，或者添加我【微信】，免费获取面试通关资料，写文章不易(大家别忘记**Star**哟)。


<p align="left" >
        <img src="https://p3-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/64301d17b1ca42d084e0d2c38b5701be~tplv-k3u1fbpfcp-watermark.image" width="600px"/>
</p>

- 手写算法
    - [letcode](https://leetcode-cn.com/problemset/all/)
- Java核心基础
    - [Exception和Error有什么区别](https://mp.weixin.qq.com/s/H7hx9e5Fj_Lc-_fSDOpeGw)
    - [final、finally、 finalize有什么不同](https://mp.weixin.qq.com/s/W2VxecoIxBWhqXzGFOfcTw)
    - [Java提供了哪些IO方式？什么是 NIO？](https://mp.weixin.qq.com/s/e-aWIxevMz7wpG8oCURqVg)
    - HashMap灵魂拷问
    - 设计模式详解
    - JDK1.8新特性
- 计算机网络和操作系统
    - 你输入 URL 后到响应，都经历了哪些过程
    - TCP/IP 常见面试知识总结
    - 被问千百遍的 TCP 三次握手和四次挥手
    - HTTPS常见面试题
    - Linux面试-常用命令总结
    - TLS 1.3 VS TLS 1.2
- JVM深入浅出
    - JVM内存模型
    - JVM类加载机制
    - JVM垃圾回收器，垃圾回收算法
    - 一次内存溢出&CPU飙高排查历程
    - JVM面试，看这一篇就够了
- Java面试之必问-多线程
    - [Java面试必问：ThreadLocal](https://mp.weixin.qq.com/s/Pj9ggVIbdzPEilLiCt9qDw)
    - 单列模式（以为是送分题，结果是送命题）引发了我对锁粒度的思考
    - ReentrantLock底层原理
    - Synchronized 底层如何实现的？什么是锁的升级，锁的降级
    - Synchronized 和 ReentrantLock 区别
    - 实现线程安全有哪些方法？
    - Volatile关键字，面试官服了
    - 谈谈你对线程安全的理解？究竟该怎么谈！
    - Java提供了哪些并发工具类？
        - CountDownLatch?
        - CyclicBarrier
        - Semaphore
        - ConcurrentHashMap
        - ConcurrentSkipListMap
        - CopyOnWriteArrayList? 
        - CopyOnWriteArraySet
        - ArrayBlockingQueue
        - PriorityBlockingQueue
    - Java并发工具类的基石-AQS
    - 多线程常问-HashMap和ConcurrentHashMap，HashTable的区别
    - 线程之间如何通信？
    - AtomicInteger底层实现原理
    - Java读写锁如何通信？如何使用Redis实现读写锁？
    - 一次线程两次调用start()方法会出现什么样的情况
    - 线程池的使用
    - 线程池的原理篇
    - Java内存模型中的happen-before是什么？
- redis
    - [Redis面经-基础篇](https://mp.weixin.qq.com/s/yPB6VOeg01uaNg6jYp2U9w)
        - Redis的内存淘汰策略有哪些？
        - 自己如何实现一个LRU算法?
        - Redis是怎么进行持久化的
        - Redis过期删除策略
        - 说说Redis和Memcache的区别？
    - Redis为何这么快？Redis是单线程吗？
    - Redis 5种数据结构
    - Redis之集群模式，哨兵模式，主从模式
    - Redis 分布式锁
    - Redis之雪崩、击穿、穿透
    - Redis 之缓存一致性问题
    - Redis常见面试题-Redis使用过程中都有哪些问题？
    - Redis高阶用法-Lua 脚本的使用
    - Redis之布隆过滤器实战
    - Redis HyperLogLog
    - Redis 之GEO的使用
    - 如何用Redis实现消息队列？
    - Redis脑裂问题
    - 秒杀系统的设计
- 消息队列
    - 你们公司用的什么MQ，你是如何选型的？
        - 性能对比
        - 如何保证消息不丢失
        - 重复消费问题
        - 消息堆积能力
        - 顺序消费问题
    - 使用MQ实现分布式事务
    - 面试题：如何保证消息不丢失？处理重复消息？消息有序性？消息堆积处理？
    - RocketMQ面试总结
    - Kafka面试总结
- Mysql
    - Mysql之性能调优正取姿势（不管是否调过优，这牛我吹定了）
    - Mysql引擎选择&Mysql索引篇
    - Mysql之模糊查询like %% 优化方案
    - Mysql之MVCC和事务隔离级别的关系
    - Mysql是如何保证ACID的？（binlog,redo log,undo log MVCC）
    - 事务传播属性，原来可以这样问
    - Mysql逻辑结构和字段选择的优化
    - Mysql如何做分表分库
    - Mysql如何读写分离
- Dubbo
    - Dubbo面试题整理
    - Dubbo服务调用过程
    - Dubbo集群容错负载均衡
    - Dubbo和spring cloud区别
- 常用框架
    - 谈谈SpringMvc整个流程
    - Spring Bean的生命周期和作用域
    - springboot自动配置原理
    - spring aop原理
    - spring声明式事务原理
    - spring@import原理
    - 高性能NIO框架-Netty
    - 没有看过框架源码，一次有目的的源码阅读计划
- 分布式相关
    - 分布式事务
    - 阿里巴巴开源限流系统 Sentinel 全解析
    - zookeeper和eureka的区别
    - 限流原理
    - 如何用Redis实现限流
- 大数据
    - Spark
    - Hadoop
    - Hbase
    - Hive
- 架构篇
    - 很多公司三面都问架构相关问题，我该怎么理解架构？怎么设计我的回答
- 简历篇
    - [简历小技巧](https://mp.weixin.qq.com/s/hv5kQhL_vLo4cbpfECEtQQ)
    - 面试流程
    - 哪些是面试中的加分项
- 面试真题&面经分享
    - 一线大厂都爱问哪些面试题，都爱怎么问？
    - 阿里巴巴面试题汇总
    - 腾讯面试题汇总
    - 字节面试题汇总
    - 美团面试题汇总
    - 拼多多面试题汇总
    - 滴滴面试题汇总
    - 京东面试题汇总
    - 网易面试题汇总
<p align="center" >
        <img src="https://p6-juejin.byteimg.com/tos-cn-i-k3u1fbpfcp/76be48d8fbb841c985956b01a9da85b6~tplv-k3u1fbpfcp-watermark.image" width="600px" height="600px" />
</p>
	
	
