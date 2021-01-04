# yumbo
云博是一款开源的、利于使用的、个性化的、优秀的创新博客。整体架构基于微服务springcloud。立志要做成为最受欢迎的开源博客。
前端基于Vue+elementUI，后端基于springboot_2.x+springcloud+cloudAlibaba。数据库采用非关系型数据库Mongodb+传统的关系型数据库MySQL，缓存采用Redis、消息队列ActiveMQ、阿里云OSS对象存储、检索引擎ElasticSearch。整体项目基于maven构建。

用到CloudAlibaba主要的组件有Nocos注册和配置中心、Sentinel服务熔断降级流控、Seata分布式事务
springcloud组件GateWay网关、
springsecurity


### 预期功能的思维导图的png
![avatar](https://github.com/1015770492/yumbo/blob/master/xmind%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE%E6%96%87%E4%BB%B6/%E5%8D%9A%E5%AE%A2%E6%A8%A1%E5%9D%97%E5%8A%9F%E8%83%BD%E6%80%9D%E7%BB%B4%E5%AF%BC%E5%9B%BE.png)

微服务模块命名规则
yumbo-xxx-服务名-服务端口

