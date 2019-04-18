## 发送消息存储
+ CommitLog：所有topic消息都存储在CommitLog中
+ ConsumeQueue：CommitLog异步消息转移到此，一个topic对应多个ConsumeQueue
+ IndexFile：加速消息检索

## 消息存储基类：DefaultMessageStore


