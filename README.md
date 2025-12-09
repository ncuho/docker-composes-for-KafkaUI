# docker-composes-for-KafkaUI
Конфигурационные файлы для запуска тестового стенда с различными UI для Apache Kafka

Готовые docker-compose файлы для быстрого развертывания тестовых стендов каждого UI: 

Kafbat UI:
```
curl -o docker-compose.yml https://raw.githubusercontent.com/ncuho/docker-composes-for-KafkaUI/main/Kafbat/docker-compose.yml
docker-compose up -d
# Открыть: http://localhost:8080
```
Что развернется:
Apache Kafka + Zookeeper
Schema Registry
Kafka Connect
KSQL DB
Kafbat UI


AKHQ:
```
curl -o docker-compose.yml https://raw.githubusercontent.com/ncuho/docker-composes-for-KafkaUI/main/AKHQ/docker-compose.yml
docker-compose up -d
# Открыть: http://localhost:8080
```
Что развернется:
Apache Kafka + Zookeeper
Schema Registry
Kafka Connect
AKHQ с полной RBAC-конфигурацией


Kafdrop:
```
curl -o docker-compose.yml https://raw.githubusercontent.com/ncuho/docker-composes-for-KafkaUI/main/Kafdrop/docker-compose.yml
docker-compose up -d
# Открыть: http://localhost:9000
```
Что развернется:
Apache Kafka + Zookeeper
Kafdrop


Redpanda Console:
```
curl -o docker-compose.yml "https://raw.githubusercontent.com/ncuho/docker-composes-for-KafkaUI/main/Redpanda%20Console/docker-compose.yml"
docker-compose up -d
# Открыть: http://localhost:8080
```
Что развернется:
Apache Kafka + Zookeeper
Redpanda Console
