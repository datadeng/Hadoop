# 初识Hadoop

## 数据存储与分析
并行读写需要解决的问题：
+ 硬件故障：使用多个硬件时发生概率非常高，系统保存冗余复本是避免数据丢失的常见做法
+ 多数分析任务需要结合大部分数据完成任务：保证其准确性是关键，Mapreduce从中抽象出编程模型，计算数据集（键/对组成）

总之，Hadoop提供可靠的共享存储和分析系统，HDFS实现存储，MapReduce实现分析处理

## 与其他系统相比
优势之处：

## 关系型数据库管理系统
+ 结构化数据：
+ 半结构化数据：
+ 非结构化数据：

## 网格计算
+ 网格计算：
+ 高性能计算：
+ 数据本地化：
+ 志愿计算：
+ 云计算：

## Hadoop发展史
+ 创始人：
+ 起源：
+ 过程：
+ 现状：

## Apache Hadoop和Hadoop生态圈
+ Common
+ Avro
+ MapReduce
+ HDFS
+ Pig
+ [Hive](https://github.com/datadeng/Hive)：分布式、按列存储的数据仓库路？管理HDFS中数据，提供基于HQL的查询语言查询数据（运行时转化为MapReduce任务）
+ HBase
+ Zookeeper
+ Sqoop:在数据库和HDFS之间高效传输的工具

# 关于Mapreduce
