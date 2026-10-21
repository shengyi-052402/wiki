#kafka

## kafka的事务功能

只能保证kafka事物的原子性,可以保证消息一起发送成功或者一起失败.

而 #RocketMQ 存在半事务机制,可以保证消息和数据库之间操作的原子性
如下图
![Kafka 图片](assets/Kafka/file-20260926182453944.png)
