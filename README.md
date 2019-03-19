## Apache RocketMQ [![Build Status](https://travis-ci.org/apache/rocketmq.svg?branch=master)](https://travis-ci.org/apache/rocketmq) [![Coverage Status](https://coveralls.io/repos/github/apache/rocketmq/badge.svg?branch=master)](https://coveralls.io/github/apache/rocketmq?branch=master)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.rocketmq/rocketmq-all/badge.svg)](http://search.maven.org/#search%7Cga%7C1%7Corg.apache.rocketmq)
[![GitHub release](https://img.shields.io/badge/release-download-orange.svg)](https://rocketmq.apache.org/dowloading/releases)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)

**[Apache RocketMQ](https://rocketmq.apache.org) is a distributed messaging and streaming platform with low latency, high performance and reliability, trillion-level capacity and flexible scalability.**

It offers a variety of features:

* Pub/Sub messaging model
* Scheduled message delivery
* Message retroactivity by time or offset
* Log hub for streaming
* Big data integration
* Reliable FIFO and strict ordered messaging in the same queue
* Efficient pull&push consumption model
* Million-level message accumulation capacity in a single queue
* Multiple messaging protocols like JMS and OpenMessaging
* Flexible distributed scale-out deployment architecture
* Lightning-fast batch message exchange system
* Various message filter mechanics such as SQL and Tag
* Docker images for isolated testing and cloud isolated clusters
* Feature-rich administrative dashboard for configuration, metrics and monitoring


----------
## 调试启动
+ 先下载一个4.4.0的二进制包到本地解压
+ 启动NameSrvStartup，同时设置idea的environment variables：ROCKETMQ_HOME = /Users/wangzx/Downloads/rocketmq-all-4.4.0-bin-release
+ 启动BrokerStartup，同时设置Program argument：-n localhost:9876 和environment variables：ROCKETMQ_HOME = /Users/wangzx/Downloads/rocketmq-all-4.4.0-bin-release