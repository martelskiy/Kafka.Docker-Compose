# Kafka.Docker-Compose
Docker-compose file to run Kafka stack locally (zookeeper, kafka, schema-registry, UIs

Compose file contains following services:

1. Confluent Zookeeper
2. Confluent Kafka
3. Confluent Schema Registry
4. Confluent Kafka Rest Proxy 
5. landoop schema registry ui 
6. landoop kafka topics ui

In order to spin up entire stack it's enogut just to run 
```bash
docker-compose up
```

Schema registry UI will be accessible on port `:8001` 
Topics UI will be accessible on port `:8000`
