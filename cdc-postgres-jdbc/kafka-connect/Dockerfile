FROM confluentinc/cp-kafka-connect-base:7.2.1

RUN confluent-hub install --no-prompt debezium/debezium-connector-postgresql:2.1.4
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-jdbc:10.7.1
