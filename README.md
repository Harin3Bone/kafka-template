# Docker for Kafka

![Java](https://img.shields.io/badge/Java-E32C2E?logo=Java&style=flat&logoColor=ffffff)&nbsp;
![Kafka](https://img.shields.io/badge/Kafka-231F20?&style=flat&logo=apache-kafka&logoColor=F7F7F7)&nbsp;
![Docker](https://img.shields.io/badge/Docker-2496ED?&style=flat&logo=docker&logoColor=ffffff)&nbsp;

## Description

This repository made for build simple of Kafka with docker.

## Default Value

Create `.env` file to define your own value

| Variable name | Default value | Datatype | Description |
|:--------------|:--------------|:--------:|------------:|
|ZOOKEEPER_VERSION|latest|String|Zookeeper version|
|ZOOKEEPER_PORT|2181|number|Zookeeper port|
|KAFKA_VERSION|2.13-2.8.1|String|Kafka version|
|KAFKA_HTTP|9092|number|Kafka port HTTP|
|KAFKA_HTTPS|9093|number|Kafka port HTTPS|
|KAFKA_ADVERTISED|localhost|String|Kafka advertised name|
|KAFKAUI_PORT|8080|number|Kafka user interface port|
|KAFKAUI_CLUSTER_NAME|kafka|String|Kafka cluster name|
|TIMEZONE|`"Asia/Bangkok"`|String|System timezone|

## Prerequisite

- [Docker](https://docs.docker.com/engine/install/ubuntu/)
- [Docker Compose](https://docs.docker.com/compose/install/)

## Reference

* [Docker hub (Kafka)](https://hub.docker.com/r/wurstmeister/kafka)
* [Docker hub (Zookeeper)](https://hub.docker.com/r/wurstmeister/zookeeper)
* [Kafka-UI](https://github.com/provectus/kafka-ui)

## Contributor

<a href="https://github.com/Harin3Bone">
<img src="https://img.shields.io/badge/Harin3Bone-181717?style=flat&logo=github&logoColor=ffffff">
</a>