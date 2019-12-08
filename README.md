# Kafka.Docker-Compose
Docker-compose file to run Kafka stack locally (zookeeper, kafka, schema-registry, UIs

Compose file contains following services:

1. Confluent Zookeeper 5.3.1
2. Confluent Kafka 5.3.1
3. Confluent Schema Registry 5.3.1
4. Confluent Kafka Rest Proxy 5.3.1
5. landoop schema registry ui 0.9.4
6. landoop kafka topics ui:0.9.4

In order to spin up entire stack it's enogut just to run 
```bash
docker-compose up
```

Schema registry UI will be accessible on port `:8001` 
Topics UI will be accessible on port `:8000`
