FROM confluentinc/cp-kafka-connect-base:5.4.1

# Install Postgres connnector
RUN confluent-hub install --no-prompt debezium/debezium-connector-postgresql:1.1.0
# Install SQL Server connector
RUN confluent-hub install --no-prompt debezium/debezium-connector-sqlserver:1.1.0
# Install MySQL  connector
RUN confluent-hub install --no-prompt debezium/debezium-connector-mysql:1.1.0

# Install S3 Sink connector
RUN confluent-hub install --no-prompt confluentinc/kafka-connect-s3:5.4.1
