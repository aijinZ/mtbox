# Redis

## # 基础

> [《Redis 设计与实现》](https://book.douban.com/subject/25900156/)
>
> [Redis 设计与实现](http://redisbook.com/)

Redis 数据库里面的每个键值对（key-value pair）都是由对象（object）组成的：

- 其中，数据库的键总是一个字符串对象（string object）；
- 而数据库的键则可以是字符串对象、列表对象（list object）、哈希对象（hash object）、集合对象（set object）、有序集合对象（sorted set object）这五种对象中的其中一种。

## # 渐进式 Hash

> [《Redis 设计与实现》- 第 4 章 字典](https://book.douban.com/subject/25900156/)
>
> [渐进式 rehash](http://redisbook.com/preview/dict/incremental_rehashing.html)

