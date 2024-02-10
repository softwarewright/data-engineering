# Kafka


## Common Commands

kafka-topics.sh --create --topic {topic-name} --bootstrap-server localhost:9092
kafka-console-consumer.sh --topic {topic-name} --from-beginning --bootstrap-server localhost:9092
kafka-console-producer.sh --topic {topic-name} --bootstrap-server localhost:9092