# ZooKeeper实战与源代码剖析

极客时间课程首页: [ZooKeeper实战与源码剖析](https://time.geekbang.org/course/intro/100034201)

## 源码列表

### 1.7 ZooKeeper架构
- [在一个机器上配置一个3节点ZooKeeper集群的配置文件](src/main/resources/quorum)

### 2.1 ZooKeeper API介绍
- [WatcherTests](src/test/java/org/yao/WatcherTests.java)

### 2.2 ZooKeeper API-Watch示例
- [Java Watch Client](src/main/java/org/yao/watchclient)
- [seq.sh](scripts/seq.sh)
- [executor.sh](scripts/executor.sh)

### 2.6 使用 Apache Curator 简化 ZooKeeper 开发
- [CuratorTests](src/test/java/org/yao/CuratorTests.java)

### 3.4 通过动态配置实现不中断服务的集群成员变更
- [DigestGenerator](src/main/java/org/yao/DigestGenerator.java)

### 3.5 ZooKeeper节点是如何存储数据的
- [snapshotFormatter.sh](scripts/snapshotFormatter.sh)

### 4.3 使用ZooKeeper实现服务发现(3)
- [A port of curator-x-discovery-server in Spring Boot](https://github.com/yaojingguo/curator-x-discovery-server)

## PPT
1. [第一章：基础篇](slides/第一章：基础篇.pdf)
1. [第二章：开发篇](slides/第二章：开发篇.pdf)
1. [第三章：运维篇](slides/第三章：运维篇.pdf)
