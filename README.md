# seckill_jiuzhang

## 介绍

商品秒杀系统
1. 从互联网业务来看
	秒杀玩法在电商，直播带货业务中运用的非常广泛，越来越多的 秒杀玩法不断出现，秒杀系统几乎是所有互联网公司的 “标配”
2. 从技术难度和深度来看
	秒杀系统需要面对瞬间高并发大流量（High Concurrency And Large Flow） 的场景，要求具备大并发、高性能系统的架构设计方法和关键技术


## 技术栈
1. 数据库：Mysql
2. 持久层框架：Mybatis
3. Springboot+SpringMVC
4. 缓存中间件：Redis
5. 消息中间件：RocketMQ
6. 分布式唯一ID生成：雪花算法
7. 流量控制框架：Sentinel
8. 压力测试工具：JMeter
## 核心技术点

- **数 据 库 D a t a b a s e**
    1. Redis 实现分布式锁 Distributed Lock 
    2. 缓存预热 Cache Preheating 
    3. 数据库乐观锁 DB Optimistic Lock 
    4. 数据库索引优化 DB Index Optimization
- **中 间 件 M i d d l e w a r e**
    1. 消息队列 Message Queue
    2. 延迟队列 Delay Queue
    3. 接口限流 Rate Limiting
    4. 服务熔断 Circuit Breaker
- **优 化 O p t i m i z a t i o n**
    1. 商品限购 Purchase Limit
    2. 雪花算法 ID 生成器 SnowFlake
    3. 分布式事务处理 Distributed Transaction
    4. 页面静态化 Static Page Technology
    5. JMeter 压力测试 Stress Test
    6. 防爬虫和黄牛请求 Anti-reptile


## 秒杀流程

![SharedScreenshot.jpg](https://s2.loli.net/2021/12/28/npqy9StOgIb3RrQ.jpg)

## QuickStart

- clone 源码
- 导入 maven 项目
- 运行 SQL 脚本生成数据库
- 修改 application.properties 配置文件，修改数据库连接配置
- 通过 springboot 启动项目

## 联系作者
添加个人微信号发送关键词【seckill】获取更多源码
![image.png](https://s2.loli.net/2021/12/28/1AMsFGugKapqdZ2.png)
