# Akka 中文指南

![author](https://img.shields.io/badge/author-chariesgavin-blueviolet.svg)![last commit](https://img.shields.io/github/last-commit/guobinhit/akka-guide.svg)![issues](https://img.shields.io/github/issues/guobinhit/akka-guide.svg)![stars](https://img.shields.io/github/stars/guobinhit/akka-guide.svg)![forks](	https://img.shields.io/github/forks/guobinhit/akka-guide.svg)![license](https://img.shields.io/github/license/guobinhit/akka-guide.svg)

> **更轻松地构建强大的反应式、并发和分布式应用程序**

Akka 是一个用 Scala 编写的库，用于在 JVM 平台上简化编写具有可容错的、高可伸缩性的 Java 和 Scala 的 Actor 模型应用，其同时提供了Java 和 Scala 的开发接口。Akka 允许我们专注于满足业务需求，而不是编写初级代码。在 Akka 中，Actor 之间通信的唯一机制就是消息传递。Akka 对 Actor 模型的使用提供了一个抽象级别，使得编写正确的并发、并行和分布式系统更加容易。Actor 模型贯穿了整个 Akka 库，为我们提供了一致的理解和使用它们的方法。


- [Gitter Chat](https://gitter.im/akka/akka?source=orgpage)，Akka 在线交流平台；
- [Akka Forums](https://discuss.lightbend.com/c/akka/)，Akka 论坛；
- [Akka in GitHub](https://github.com/akka/akka)，Akka 开源项目仓库；
- [Akka Official Website](https://akka.io/)，Akka 官网；
- [Akka Java API](https://doc.akka.io/japi/akka/2.6/overview-summary.html)，Akka 应用程序编程接口。


## 快速入门指南 

- [快速入门 Akka Java 指南](https://github.com/guobinhit/akka-guide/blob/master/articles/qucikstart-akka-java.md)
- [快速入门 Akka Scala 指南](https://developer.lightbend.com/guides/akka-quickstart-scala/)

## 目录

- [安全公告](https://github.com/guobinhit/akka-guide/blob/master/articles/security-announcements.md)
- [入门指南](https://doc.akka.io/docs/akka/current/guide/index.html)
  - [Akka 简介](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/introduction-to-akka.md) 
  - [为什么现代系统需要新的编程模型](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/actors-motivation.md) 
  - [Actor 模型如何满足现代分布式系统的需求](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/actor-intro.md)
  - [Akka 库和模块概述](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/modules.md) 
  - [Akka 应用程序示例简介](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial.md)
  - [第 1 部分: Actor 的体系结构](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial_1.md)
  - [第 2 部分: 创建第一个 Actor](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial_2.md)
  - [第 3 部分: 使用设备 Actors](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial_3.md)
  - [第 4 部分: 使用设备组](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial_4.md)
  - [第 5 部分: 查询设备组](https://github.com/guobinhit/akka-guide/blob/master/articles/getting-started-guide/tutorial_5.md)
- [一般概念](https://doc.akka.io/docs/akka/current/general/index.html)
  - [术语及概念](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/terminology.md)
  - [Actor 系统](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/actor-systems.md)
  - [什么是 Actor？](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/actors.md)
  - [监督和监控](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/supervision.md)
  - [Actor 引用、路径和地址](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/addressing.md)
  - [位置透明](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/remoting.md)
  - [Akka 和 Java 内存模型](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/jmm.md)
  - [消息传递可靠性](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/message-delivery-reliability.md)
  - [配置](https://github.com/guobinhit/akka-guide/blob/master/articles/general-concepts/configuration.md)
- [Actors](https://doc.akka.io/docs/akka/current/index-actors.html)
  - [Actors](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/actors.md)（详述了 Akka 中常见的 API 操作，**强烈推荐阅读**）
  - [容错](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/fault-tolerance.md)
  - [调度器](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/dispatchers.md)
  - [邮箱](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/mailboxes.md)
  - [路由](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/routing.md)
  - [FSM](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/fsm.md)
  - [持久化](https://github.com/guobinhit/akka-guide/blob/master/articles/actors/persistence.md)
  - [持久化 - 模式演化](https://doc.akka.io/docs/akka/current/persistence-schema-evolution.html)
  - [持久化查询](https://doc.akka.io/docs/akka/current/persistence-query.html)
  - [LevelDB 的持久化查询](https://doc.akka.io/docs/akka/current/persistence-query-leveldb.html)
  - [持久化 FSM](https://doc.akka.io/docs/akka/current/persistence-fsm.html)
  - [持久化 - 构建存储后端](https://doc.akka.io/docs/akka/current/persistence-journals.html)
  - [测试 Actor 系统](https://doc.akka.io/docs/akka/current/testing.html)
- [Akka 类型](https://doc.akka.io/docs/akka/current/typed/index.html)
  - [入门指南](https://doc.akka.io/docs/akka/current/typed/guide/index.html)
  - [Actors](https://doc.akka.io/docs/akka/current/typed/actors.html)
  - [调度器](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/dispatchers.md)
  - [共存](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/coexisting.md)
  - [Actor 生命周期](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/actor-lifecycle.md)
  - [交互模式](https://doc.akka.io/docs/akka/current/typed/interaction-patterns.html)
  - [容错](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/fault-tolerance.md)
  - [Actor 发现](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/actor-discovery.md)
  - [路由](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/routers.md)
  - [Stash](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/stash.md)
  - [流](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/stream.md)
  - [分布式数据](https://doc.akka.io/docs/akka/current/typed/distributed-data.html)
  - [集群单例](https://doc.akka.io/docs/akka/current/typed/cluster-singleton.html)
  - [集群分片](https://doc.akka.io/docs/akka/current/typed/cluster-sharding.html)
  - [持久性](https://doc.akka.io/docs/akka/current/typed/persistence.html)
  - [作为 FSM 的行为](https://github.com/guobinhit/akka-guide/blob/master/articles/typed/fsm.md)
  - [测试](https://doc.akka.io/docs/akka/current/typed/testing.html)
- [集群](https://doc.akka.io/docs/akka/current/index-cluster.html)
  - [集群规范](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-specification.md) 
  - [集群的使用方法](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-usage.md) 
  - [集群感知路由器](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-routing.md) 
  - [集群单例](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-singleton.md) 
  - [集群中的分布式发布订阅](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/distributed-pub-sub.md) 
  - [集群客户端](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-client.md) 
  - [集群分片](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-sharding.md)
  - [集群度量扩展](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-metrics.md) 
  - [分布式数据](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/distributed-data.md) 
  - [跨多个数据中心集群](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/cluster-dc.md) 
  - [多虚拟机测试](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/multi-jvm-testing.md) 
  - [多节点测试](https://github.com/guobinhit/akka-guide/blob/master/articles/clustering/multi-node-testing.md) 
- [流](https://doc.akka.io/docs/akka/current/stream/index.html)
- [网络](https://doc.akka.io/docs/akka/current/index-network.html)
  - [远程处理](https://doc.akka.io/docs/akka/current/remoting.html) 
  - [远程处理（代号动脉）](https://doc.akka.io/docs/akka/current/remoting-artery.html)
  - [序列化](https://doc.akka.io/docs/akka/current/serialization.html) 
  - [I/O](https://doc.akka.io/docs/akka/current/io.html) 
  - [使用 TCP](https://doc.akka.io/docs/akka/current/io-tcp.html) 
  - [使用 UDP](https://doc.akka.io/docs/akka/current/io-udp.html) 
  - [DNS 扩展](https://doc.akka.io/docs/akka/current/io-dns.html) 
  - [Camel](https://doc.akka.io/docs/akka/current/camel.html)  
- [发现](https://github.com/guobinhit/akka-guide/blob/master/articles/discovery-index.md)
- [协作](https://github.com/guobinhit/akka-guide/blob/master/articles/coordination.md)
- [Futures 和 Agents](https://doc.akka.io/docs/akka/current/index-futures.html)
  - [Futures](https://doc.akka.io/docs/akka/current/futures.html) 
  - [Agents](https://github.com/guobinhit/akka-guide/blob/master/articles/index-futures/agents.md) 
- [工具](https://doc.akka.io/docs/akka/current/index-utilities.html)
  - [事件总线](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/event-bus.md) 
  - [日志记录](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/logging.md) 
  - [调度程序](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/scheduler.md) 
  - [持续时间](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/duration.md) 
  - [断路器](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/circuitbreaker.md) 
  - [Java 8 兼容性](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/java8-compat.md)
  - [Akka 扩展](https://github.com/guobinhit/akka-guide/blob/master/articles/index-utilities/extending-akka.md) 
- [其他 Akka 模块](https://doc.akka.io/docs/akka/current/common/other-modules.html)
  - [Akka HTTP](https://doc.akka.io/docs/akka-http/current/?language=java) 
  - [Alpakka](https://doc.akka.io/docs/alpakka/current/) 
  - [Alpakka Kafka Connector](http://doc.akka.io/docs/akka-stream-kafka/current/home.html) 
  - [Akka 持久化的 Cassandra 插件](https://github.com/akka/akka-persistence-cassandra) 
  - [Akka 持久化的 Couchbase 插件](https://doc.akka.io/docs/akka-persistence-couchbase/current/) 
  - [Akka 管理](http://developer.lightbend.com/docs/akka-management/current/) 
  - [Akka gRPC](https://doc.akka.io/docs/akka-grpc/current/) 
  - [社区项目](https://doc.akka.io/docs/akka/current/common/other-modules.html) 
  - [Lightbend 赞助的相关项目](https://doc.akka.io/docs/akka/current/common/other-modules.html) 
    - [Play 框架](https://www.playframework.com) 
    - [Lagom](https://www.lagomframework.com) 
- [如何：常见模式](https://github.com/guobinhit/akka-guide/blob/master/articles/howto.md)
- [项目信息](https://doc.akka.io/docs/akka/current/project/index.html)
  - [迁移指南](https://github.com/guobinhit/akka-guide/blob/master/articles/project/migration-guides.md) 
  - [滚动更新](https://github.com/guobinhit/akka-guide/blob/master/articles/project/rolling-update.md)
  - [问题追踪](https://github.com/guobinhit/akka-guide/blob/master/articles/project/issue-tracking.md)
  - [许可证](https://github.com/guobinhit/akka-guide/blob/master/articles/project/licenses.md)
  - [项目](https://github.com/guobinhit/akka-guide/blob/master/articles/project/links.md)
- [附加信息](https://doc.akka.io/docs/akka/current/additional/index.html)
  - [二进制兼容规则](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/binary-compatibility-rules.md)
  - [模块标记为“可能改变”](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/may-change.md)
  - [如何部署 Akka?](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/deploy.md)
  - [常见问题](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/faq.md)
  - [IDE 提示](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/ide.md)
  - [书籍和视频](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/books.md)
  - [OSGi 中的 Akka](https://github.com/guobinhit/akka-guide/blob/master/articles/additional/osgi.md)



----------

**English Original Editon**: [Akka Documentation](https://doc.akka.io/docs/akka/current/index.html)

