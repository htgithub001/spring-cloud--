# Spring Cloud Eureka Consul使用和对比

最大的区别是Eureka保证AP, Consul为CP。
所以在同一个时间段内从不同的Eureka获得的两个值的顺序不一致就是因为它放弃了C(一致性).

以上资料来源: https://blog.csdn.net/ZYC88888/article/details/81453647
