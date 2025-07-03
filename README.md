# Simple-Kafka-Java-Spring-Example
A simple example of two Java Spring apps using Apache Kafka. One is a producer and the other a consumer. To run these two projects you will need Apache Kafka running locally.

Download Apache Kafka: https://kafka.apache.org/downloads

This project assumes Kafka is running on localhost:9092.

Run both projects, then test by passing path parameters to the /send endpoint:

```curl -X POST http://localhost:8080/send/testing ```