# Kafka

## How to run Apache Kafka

### Go to Kafka directory
### Create data/zookeeper & data/kafka
### Go to config/zookeeper.properties. Edit dataDir=/home/{user}/Desktop/kafka_2.12-2.0.0/data/zookeeper
### Run Zookeeper: cd kafka -> bin/zookeeper-server-start.sh config/zookeeper.properties
### Go to config/server.properties. Edit log.dirs=/home/{user}/Desktop/kafka_2.12-2.0.0/data/kafka
### Run Kafka: cd kafaka -> bin/kafka-server-start.sh config/server.properties

We need start Zookeeper before run Kafka
