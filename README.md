# Distributeed-Database-Simulation
## 使用python模拟分布式数据的实现原理
主要使用pool library 利用多线程的方式模拟分布式数据库

主要模拟了 分布式数据库中的partion，join，select，groupBy等操作。

其实在分布式数据库的设计中最重要的部分就是如何去partion 数据，好的partion的方法可以大大提高分布式数据运行的效率。

其次是在内存地址不够用的情况下，如何利用有限的内存处理器大量的数据。
