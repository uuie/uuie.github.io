---
layout:     post
title:      "spring cloud 整理"
subtitle:   ""
date:       2018-07-01
author:     "chris"
 # header-img: "img/post-bg-js-version.jpg"
tags:
  -spring cloud
---

# spring cloud微服务框架整理

## component list

| name                    | Subcomponent | Desc.                    |
| ----------------------- | ------------ | ------------------------ |
| spring-cloud-config     |              | 分布式配置服务           |
| spring-cloud-netflix    | Eureka       | 服务发现和注册           |
|                         | Hystrix      | 服务降级，熔断           |
|                         | Zuul         | api网关                  |
|                         | Ribbon       | client side load balance |
|                         | Feign        | Http API Helper          |
|                        | Archaius     | Cloud Configuration      |
| spring-cloud-consul     |              | 服务发现和注册           |
| spring-cloud-security   |              | 认证和授权               |
| spring-cloud-sleuth     |              | 服务跟踪                 |
| spring-cloud-dataflow   |              | 大数据处理               |
| spring-cloud-stream     |              | MQ Integration           |
| spring-cloud-task       |              | Short time task execute  |
| Spring-cloud-zookeeper  |              | 服务发现和注册(ZK,CP)    |
| spring-cloud-connectors |              | cloud platform connector |
| spring-cloud-contract   |              |                          |
| spring-cloud-gateway    |              | API Gateway              |
| spring-cloud-openfeign  |              | Http API Helper          |
| spring-cloud-bus        |              | Event Bus                |
| spring-cloud-vault      |              | Authentication           |
|                         |              |                          |



## 组件关系



![spring-cloud](/img/spring-cloud.jpg)