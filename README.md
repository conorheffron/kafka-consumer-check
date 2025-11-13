# kafka-consumer-check

## Tech
- JDK 17, Apache Kafka 3, Kafka Broker

## Build Project
```shell
./mvnw clean package
```

## Run Kafka Consumer
```shell
java -jar target/kafka-tester-1.0-SNAPSHOT.jar localhost:9092 ironoc-test-topic ironoc-net
```

## See Consumer App Running below:
![pt-kafka-consumer-running](./src/test/resources/pt-kafka-consumer-running.png)
