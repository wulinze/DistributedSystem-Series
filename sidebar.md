  - [一致性与共识](/一致性与共识/README.md)
    - [BFT](/一致性与共识/BFT/README.md)
      
    - [CAP](/一致性与共识/CAP/README.md)
      - [BASE](/一致性与共识/CAP/BASE.md)
      - [DLS](/一致性与共识/CAP/DLS.md)
    - [一致性模型](/一致性与共识/一致性模型/README.md)
      - [其他一致性模型](/一致性与共识/一致性模型/其他一致性模型.md)
      - [因果一致性](/一致性与共识/一致性模型/因果一致性.md)
      - [最终一致性](/一致性与共识/一致性模型/最终一致性.md)
      - [线性一致性](/一致性与共识/一致性模型/线性一致性.md)
      - [顺序一致性](/一致性与共识/一致性模型/顺序一致性.md)
    - [共识算法](/一致性与共识/共识算法/README.md)
      - Paxos
        - [Multiple Paxos](/一致性与共识/共识算法/Paxos/Multiple-Paxos.md)
        - [Paxos](/一致性与共识/共识算法/Paxos/Paxos.md)
      - [Raft](/一致性与共识/共识算法/Raft/README.md)
        - [RPC](/一致性与共识/共识算法/Raft/RPC.md)
        - [与 Multi Paxos 对比](/一致性与共识/共识算法/Raft/与%20Multi-Paxos%20对比.md)
        - [安全性](/一致性与共识/共识算法/Raft/安全性.md)
        - [日志复制](/一致性与共识/共识算法/Raft/日志复制.md)
        - [选举与变更](/一致性与共识/共识算法/Raft/选举与变更.md)
      - [算法模型](/一致性与共识/共识算法/算法模型/README.md)
        - [算法对比](/一致性与共识/共识算法/算法模型/算法对比.md)
    - [分布式 ID](/一致性与共识/分布式%20ID/README.md)
      - [Leaf](/一致性与共识/分布式%20ID/Leaf.md)
      - [Snowflake](/一致性与共识/分布式%20ID/Snowflake.md)
      - [UUID](/一致性与共识/分布式%20ID/UUID.md)
      - [库自增 ID](/一致性与共识/分布式%20ID/库自增%20ID.md)
    - 序列号
      - [全序广播](/一致性与共识/序列号/全序广播.md)
      - [序列号顺序](/一致性与共识/序列号/序列号顺序.md)
  - [分布式事务](/分布式事务/README.md)
    - [JDTX](/分布式事务/JDTX/README.md)
      
    - [Seata](/分布式事务/Seata/README.md)
      
    - [事务消息](/分布式事务/事务消息/README.md)
      - [流处理方案](/分布式事务/事务消息/流处理方案.md)
    - [分布式锁](/分布式事务/分布式锁/README.md)
      - 锁实现
        - [RESTful 分布式锁](/分布式事务/分布式锁/锁实现/RESTful%20分布式锁.md)
        - [Redis 分布式锁](/分布式事务/分布式锁/锁实现/Redis%20分布式锁.md)
        - [Zookeeper 分布式锁](/分布式事务/分布式锁/锁实现/Zookeeper%20分布式锁.md)
    - [多阶段提交](/分布式事务/多阶段提交/README.md)
      - [XA 规范](/分布式事务/多阶段提交/XA%20规范.md)
      - [三阶段提交](/分布式事务/多阶段提交/三阶段提交.md)
      - [二阶段提交](/分布式事务/多阶段提交/二阶段提交.md)
    - [柔性事务](/分布式事务/柔性事务/README.md)
      - Saga
        - [Saga](/分布式事务/柔性事务/Saga/Saga.md)
      - [TCC](/分布式事务/柔性事务/TCC/README.md)
        
  - [分布式存储](/分布式存储/README.md)
    - [分布式文件系统](/分布式存储/分布式文件系统/README.md)
      - [HDFS](/分布式存储/分布式文件系统/HDFS/README.md)
        - [HDFS 源代码分析](/分布式存储/分布式文件系统/HDFS/HDFS%20源代码分析.md)
        - [HDFS 编程](/分布式存储/分布式文件系统/HDFS/HDFS%20编程.md)
        - [HDFS 读取原理](/分布式存储/分布式文件系统/HDFS/HDFS%20读取原理.md)
    - [分片](/分布式存储/分片/README.md)
      - [一致性哈希](/分布式存储/分片/一致性哈希/README.md)
        - [Go](/分布式存储/分片/一致性哈希/Go.md)
        - [Java](/分布式存储/分片/一致性哈希/Java.md)
      - [元数据与调度](/分布式存储/分片/元数据与调度/README.md)
        - [请求路由](/分布式存储/分片/元数据与调度/请求路由.md)
      - [分片策略](/分布式存储/分片/分片策略/README.md)
        - [分片再平衡](/分布式存储/分片/分片策略/分片再平衡.md)
        - [次级索引](/分布式存储/分片/分片策略/次级索引.md)
        - [键的分片](/分布式存储/分片/分片策略/键的分片.md)
    - [复制](/分布式存储/复制/README.md)
      - [主从复制](/分布式存储/复制/主从复制/README.md)
        - [同步与异步](/分布式存储/复制/主从复制/同步与异步.md)
        - [复制延迟](/分布式存储/复制/主从复制/复制延迟.md)
        - [复制日志](/分布式存储/复制/主从复制/复制日志.md)
        - [宕机恢复](/分布式存储/复制/主从复制/宕机恢复.md)
      - [多主复制](/分布式存储/复制/多主复制/README.md)
        - [CRDT](/分布式存储/复制/多主复制/CRDT.md)
        - [冲突解决](/分布式存储/复制/多主复制/冲突解决.md)
        - [多主复制拓扑](/分布式存储/复制/多主复制/多主复制拓扑.md)
      - [无主复制](/分布式存储/复制/无主复制/README.md)
        - [故障与仲裁](/分布式存储/复制/无主复制/故障与仲裁.md)
        - [检测并发写入](/分布式存储/复制/无主复制/检测并发写入.md)
    - 存储基础
      - [存储类型](/分布式存储/存储基础/存储类型.md)
      - [应用场景](/分布式存储/存储基础/应用场景.md)
    - [对象存储](/分布式存储/对象存储/README.md)
      - [Haystack](/分布式存储/对象存储/Haystack.md)
      - [元数据管理](/分布式存储/对象存储/元数据管理.md)
  - [分布式计算](/分布式计算/README.md)
    - [Beam](/分布式计算/Beam/README.md)
      - [Dataflow 模型](/分布式计算/Beam/Dataflow%20模型.md)
      - [快速开始](/分布式计算/Beam/快速开始.md)
      - [部署与配置](/分布式计算/Beam/部署与配置.md)
    - [DAG](/分布式计算/DAG/README.md)
      - [Dryad](/分布式计算/DAG/Dryad.md)
    - [Flink](/分布式计算/Flink/README.md)
      - [Blink](/分布式计算/Flink/Blink/README.md)
        
      - [Table API](/分布式计算/Flink/Table%20API.md)
      - [代码开发](/分布式计算/Flink/代码开发.md)
      - [环境配置](/分布式计算/Flink/环境配置.md)
    - [Hadoop](/分布式计算/Hadoop/README.md)
      - [Hadoop 与数据库对比](/分布式计算/Hadoop/Hadoop%20与数据库对比.md)
      - [MapReduce](/分布式计算/Hadoop/MapReduce/README.md)
        - [CRUD](/分布式计算/Hadoop/MapReduce/CRUD.md)
        - [WordCount](/分布式计算/Hadoop/MapReduce/WordCount.md)
        - [聚合计算](/分布式计算/Hadoop/MapReduce/聚合计算.md)
    - [Spark](/分布式计算/Spark/README.md)
      - [代码开发](/分布式计算/Spark/代码开发.md)
      - [环境配置](/分布式计算/Spark/环境配置.md)
    - [Waltz](/分布式计算/Waltz/README.md)
      
    - [批处理](/分布式计算/批处理/README.md)
      - [MapReduce](/分布式计算/批处理/MapReduce/README.md)
        - [作业执行](/分布式计算/批处理/MapReduce/作业执行.md)
        - [作业输出](/分布式计算/批处理/MapReduce/作业输出.md)
        - [连接与分组](/分布式计算/批处理/MapReduce/连接与分组.md)
      - [使用 Unix 工具的批处理](/分布式计算/批处理/使用%20Unix%20工具的批处理.md)
      - [执行框架](/分布式计算/批处理/执行框架/README.md)
        - [图与迭代处理](/分布式计算/批处理/执行框架/图与迭代处理.md)
        - [物化中间状态](/分布式计算/批处理/执行框架/物化中间状态.md)
        - [高级 API 和语言](/分布式计算/批处理/执行框架/高级%20API%20和语言.md)
      - [编程模型](/分布式计算/批处理/编程模型/README.md)
        - [Data Parallelism](/分布式计算/批处理/编程模型/Data%20Parallelism.md)
        - [图的大规模并行](/分布式计算/批处理/编程模型/图的大规模并行.md)
        - [查询与声明式接口](/分布式计算/批处理/编程模型/查询与声明式接口.md)
    - [数据处理架构](/分布式计算/数据处理架构/README.md)
      - [Lambda 架构](/分布式计算/数据处理架构/Lambda%20架构.md)
      - [事务处理](/分布式计算/数据处理架构/事务处理.md)
      - [分析处理](/分布式计算/数据处理架构/分析处理.md)
      - [批处理与流处理](/分布式计算/数据处理架构/批处理与流处理.md)
    - [流处理](/分布式计算/流处理/README.md)
      - 执行框架
        - [分布式快照](/分布式计算/流处理/执行框架/分布式快照.md)
        - [反压](/分布式计算/流处理/执行框架/反压.md)
        - [容错](/分布式计算/流处理/执行框架/容错.md)
        - [流式连接](/分布式计算/流处理/执行框架/流式连接.md)
      - [流计算框架对比](/分布式计算/流处理/流计算框架对比.md)
      - 编程模型
        - [时间窗口](/分布式计算/流处理/编程模型/时间窗口.md)
    - [边缘计算](/分布式计算/边缘计算/README.md)
      
  - [消息代理](/消息代理/README.md)
    - [Kafka](/消息代理/Kafka/README.md)
      - [Kafka Streams](/消息代理/Kafka/Kafka%20Streams/README.md)
        
      - [消息存储](/消息代理/Kafka/消息存储.md)
      - [消息消费](/消息代理/Kafka/消息消费.md)
      - [消息类型](/消息代理/Kafka/消息类型.md)
      - [部署配置](/消息代理/Kafka/部署配置.md)
      - [集群与高可用](/消息代理/Kafka/集群与高可用.md)
    - [Pulsar](/消息代理/Pulsar/README.md)
      - [消息存储](/消息代理/Pulsar/消息存储.md)
      - [消息消费](/消息代理/Pulsar/消息消费.md)
      - [消息类型](/消息代理/Pulsar/消息类型.md)
      - [部署配置](/消息代理/Pulsar/部署配置.md)
    - [RabbitMQ](/消息代理/RabbitMQ/README.md)
      - [Java](/消息代理/RabbitMQ/Java.md)
      - [Python](/消息代理/RabbitMQ/Python.md)
      - [消息存储](/消息代理/RabbitMQ/消息存储.md)
      - [消息消费](/消息代理/RabbitMQ/消息消费.md)
      - [消息类型](/消息代理/RabbitMQ/消息类型.md)
      - [部署配置](/消息代理/RabbitMQ/部署配置.md)
      - [集群与高可用](/消息代理/RabbitMQ/集群与高可用.md)
    - [RocketMQ](/消息代理/RocketMQ/README.md)
      - [消息操作](/消息代理/RocketMQ/消息操作.md)
      - [消息消费](/消息代理/RocketMQ/消息消费.md)
      - [消息类型](/消息代理/RocketMQ/消息类型.md)
      - [集群与高可用](/消息代理/RocketMQ/集群与高可用.md)
    - [事件流](/消息代理/事件流.md)
    - [系统设计](/消息代理/系统设计/README.md)
      - [中间件模型](/消息代理/系统设计/中间件模型.md)
      - [消息存储](/消息代理/系统设计/消息存储.md)
      - [消息消费](/消息代理/系统设计/消息消费.md)
      - [消息类型](/消息代理/系统设计/消息类型.md)
      - [集群与高可用](/消息代理/系统设计/集群与高可用.md)
  - [网络与时钟](/网络与时钟/README.md)
    - [不可靠网络](/网络与时钟/不可靠网络/README.md)
      - [同步与异步网络](/网络与时钟/不可靠网络/同步与异步网络.md)
      - [超时与延迟](/网络与时钟/不可靠网络/超时与延迟.md)
    - [分布式时钟](/网络与时钟/分布式时钟/README.md)
      - [不可靠的时钟](/网络与时钟/分布式时钟/不可靠的时钟.md)
      - [休眠的进程](/网络与时钟/分布式时钟/休眠的进程.md)
      - [同步时钟](/网络与时钟/分布式时钟/同步时钟.md)
    - [拜占庭问题](/网络与时钟/拜占庭问题/README.md)
      - [拜占庭故障](/网络与时钟/拜占庭问题/拜占庭故障.md)
      - [系统模型与现实](/网络与时钟/拜占庭问题/系统模型与现实.md)