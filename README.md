## Requeriments

* Apache Kafka
* Java

## Kafka Server

   $ docker-compose -f single-kafka.yml up

## Create a Topic to Store Events

   $ kafka-topics.sh --create --topic quickstart-events --bootstrap-server localhost:9092

## Kafka Producer

   $ kafka-console-producer.sh --broker-list localhost:9092 --topic quickstart-events

## Kafka Consumer

   $ kafka-console-consumer.sh --boostrap-server localhost:9092 quickstart-events