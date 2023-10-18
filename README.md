# 方案设计
本系统主要演示如何用多语言实现一套图书贩卖系统，整个功能包括跨云的使用，多个不同语言微服务间的调用，网关的中的资源管理以及多种数据库、中间件的集成。

## 微服务包括
1. 图书系统，用 golang 编写，对应一张表: gin+gorm；
1. 用户系统，用 java 编写，对应一张表；
1. 订单系统，用 c# 编写。这里将涉及跨云调用的挑战；
