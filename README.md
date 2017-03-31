# k8s-docker-kafka
Kafka docker image for kubernetes.

Example of deploy cluster to kubernetes.

##Features
* Support scaling
* Auto rebalancing on expanding cluster

##Example

* Replication Controller - kafka-rc.yaml
* Service - kafka-service.yaml

Don't forget set ENABLE_AUTO_EXTEND environment variable to true.
