### Java基础与并发编程

#### 线程

1. Java中线程的实现方式？[test](base/aa.md)
2. Java中线程的状态？
3. Java中如何停止线程？
4. Java中sleep和wait方法的区别？
5. 并发编程的三大特性？
6. 什么是CAS？有什么优缺点？
7. @Contended注解有什么用？
8. Java中的四种引用类型
9. ThreadLocal的内存泄漏问题？
10. Java中锁的分类？
11. synchronized在JDK1.6中的优化？
12. synchronized的实现原理？
13. 什么是AQS？
14. AQS唤醒节点时，为何从后往前找？
15. ReentrantLock和synchronized的区别？
16. ReentrantReadWriteLock的实现原理？

#### 并发容器

1. ConcurrentHashMap在1.8做了什么优化？
2. ConcurrentHashMap的散列算法？
3. ConcurrentHashMap初始化数组的流程？
4. ConcurrentHashMap扩容的流程？
5. ConcurrentHashMap读取数据的流程？
6. ConcurrentHashMap中计数器的实现

### Spring框架

#### 核心概念

1. 谈谈你对Spring的理解
2. Spring中应用到的设计模式有哪些
3. 谈谈Autowired和Resource两个注解的区别
4. 谈谈Spring中常用的注解
5. 谈谈你对循环依赖的理解
6. Spring中是如何解决循环依赖问题的
7. Spring中是如何解决构造注入的循环依赖问题的
8. Spring中循环依赖为什么需要三级缓存
9. Spring中Bean对象的生命周期
10. Spring中支持的作用域有几种
11. Spring中事务的隔离级别介绍
12. Spring中事务的实现方式
13. Spring中事务的本质
14. 谈谈你对BeanFactory和ApplicationContext的理解
15. 谈谈你对BeanFactoryPostProcessor的理解
16. 谈谈你对BeanPostProcessor的理解

#### SpringMVC

1. 谈谈你对SpringMVC框架的理解
2. 谈谈Spring和SpringMVC的关系
3. 谈谈你对DelegatingFilterProxy的理解
4. 谈谈你对SpringBoot自动装配原理的理解
5. 谈谈你对Import注解的理解
6. 谈谈你对DeferredImportSelector的理解
7. 谈谈SpringBoot中的bootstrap.yml文件的作用
8. 如果要对属性文件中的账号密码加密如何实现？
9. 谈谈Indexed注解的作用
10. @Component, @Controller, @Repository,@Service 有何区别？
11. 有哪些通知类型(Advice)
12. 介绍下Spring中的依赖注入
13. Spring中的Bean单例对象是否是线程安全的
14. @ComponentScan注解是干什么的？
15. @EnableAutoConfiguration注解是干什么的？
16. bootstrap.yml的意义
17. Import注解的三种用法
18. RequestMapping 和 GetMapping 的不同之处在哪里？

#### SpringBoot

1. Spring Boot 的核心注解是哪个？它主要由哪几个注解组成的？
2. Spring Boot 可以兼容老 Spring 项目吗，如何做？
3. Spring Boot 如何定义多套不同环境配置？
4. Spring Boot 需要独立的容器运行吗？
5. Spring Boot 有哪几种读取配置的方式
6. Spring Boot 支持哪些日志框架？推荐和默认的日志框架是哪个？
7. Spring Boot、Spring MVC 和 Spring 有什么区别？
8. SpringBoot 中的监视器是什么呢
9. SpringBoot打成的jar和普通jar有什么区别
10. SpringBoot的run方法做了什么事情
11. SpringBoot的优点
12. SpringBoot如何解决跨域问题
13. SpringBoot中如何配置log4j
14. SpringBoot中如何实现定时任务
15. SpringBoot自动装配的核心配置文件有哪些？
16. SpringBoot自动装配的流程是怎样的？
17. 介绍几个常用的starter
18. 你如何理解 Spring Boot 配置加载顺序？
19. 如何实现SpringBoot 应用程序的安全性
20. 如何在 Spring Boot 启动的时候运行一些特定的代码？
21. 如何重新加载Spring Boot上的更改，而无需重新启动服务器？
22. 什么是 Spring Boot Starter ？
23. 什么是SpringBoot
24. 我们如何连接一个像 MySQL 或者Orcale 一样的外部数据库？
25. 运行SpringBoot项目的方式

### 数据库

#### MySQL

1. 什么是BufferPool
2. InnoDB引擎如何管理Page页
3. 为什么写缓冲区 仅适用于非唯一普通索引页
4. MySQL为什么要改进LRU算法
5. 使用索引一定可以提升效率吗
6. 介绍一下Page页的结构
7. 说一下聚簇索引与非聚簇索引
8. 索引有哪几种类型？
9. 介绍一下最佳左前缀法则
10. 什么是索引下推
11. 什么是自适应哈希索引
12. 为什么LIKE以%开头索引会失效
13. 自增还是UUID 数据库主键的类型该如何选择
14. InnoDB与MyISAM的区别
15. B树和B+树的区别是什么
16. 一个B+树中大概能存放多少条索引记录
17. explain 用过吗，有哪些主要字段
18. type字段中有哪些常见的值
19. Extra有哪些主要指标，各自的含义是什么
20. 如何进行分页查询优化
21. 如何做慢查询优化
22. Hash索引有哪些优缺点
23. 说一下InnoDB内存相关的参数优化
24. InnoDB日志相关的参数优化了解过吗
25. InnoDB IO线程相关参数优化了解过吗
26. 什么是写失效
27. 什么是行溢出
28. 如何进行JOIN优化
29. 索引哪些情况下会失效
30. 什么是覆盖索引
31. 介绍一下MySQL中事务的特性
32. MySQL 的可重复读怎么实现的
33. Repeatable Read 解决了幻读问题吗
34. 请说一下数据库锁的种类
35. 请说一下共享锁和排他锁
36. InnoDB 的行锁是怎么实现的
37. 并发事务会产生哪些问题
38. 说一下MVCC内部细节
39. 说一下MySQL死锁的原因和处理方法
40. 介绍一下MySQL的体系架构
41. undo log、redo log、 bin log的作用是什么
42. redo log与undo log的持久化策略
43. bin log与undo log的区别
44. MySQL的binlog有几种日志格式 分别有什么区别
45. MySQL线上修改大表结构有哪些风险
46. count(列名)、count(1)和 count(星号)有什么区别
47. 什么是分库分表 什么时候进行分库分表
48. 说说 MySQL 的主从复制
49. 说一下 MySQL 执行一条查询语句的内部执行过程
50. MySQL内部支持缓存查询吗

#### Redis

1. Redis为什么快？
2. Redis合适的应用场景？
3. Redis6.0之前为什么一直不使用多线程？
4. Redis6.0为什么要引入多线程？
5. Redis有哪些高级功能？
6. 为什么要用Redis？
7. Redis与memcached相对有哪些优势？
8. 怎么理解Redis中事务？
9. Redis的过期策略以及内存淘汰机制？
10. 什么是缓存穿透？如何避免？
11. 什么是缓存雪崩？如何避免？
12. 使用Redis如何设计分布式锁？
13. 怎么使用Redis实现消息队列？
14. 什么是bigkey？会有什么影响？
15. Redis如何解决key冲突？
16. 怎么提高缓存命中率？
17. Redis持久化方式有哪些？有什么区别？
18. 为什么Redis需要把所有数据放到内存中？
19. 如何保证缓存与数据库双写时的数据一致性
20. Redis集群方案应该怎么做？
21. Redis集群方案什么情况下会导致整个集群不可用？
22. 说一说Redis哈希槽的概念？
23. Redis集群会有写操作丢失吗？为什么？
24. Redis常见性能问题和解决方案有哪些？
25. 热点数据和冷数据是什么
26. 什么情况下可能会导致Redis阻塞？
27. 什么时候选择Redis，什么时候选择Memcached？
28. Redis过期策略都有哪些？LRU算法知道吗？

### 分布式系统

#### 分布式基础

1. 分布式幂等性如何
