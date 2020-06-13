# kafka-alerting-system
Containerized streaming application with Apache Kafka with scripts for generating data stream and processing via the broker to detect an anomaly and alert the user of the anomalous data.

#### docker-compose.kafka.yml
- Contains the Docker configuration to run Kafka itself in an insolated container.

#### docker-compose.yml
- Contains Docker configuration to define the 2 services, generator and detector, which will generate and process data through interaction with Kafka.