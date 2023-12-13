# kafka-demo-app

Небольшое демо-приложение для изучения работы kafka

## Запуск Kafka
```
cd kafka_2.13-3.6.1
```
Запуск Zookeeper:
```
bin/zookeeper-server-start.sh config/zookeeper.properties
```
Запуск Kafka:
```
bin/kafka-server-start.sh config/server.properties
```

## Параллельно можно отслеживать сообщения в консоли

topicName - название топика

```
bin/kafka-console-consumer.sh --topic topicName --from-beginning --bootstrap-server localhost:9092
```
