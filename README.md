### Kafka Cluster with 3 Brokers which acts as a controller and a broker as well
### Docker opens ports 9092, 9093, 9094 for external connections to broker
### One can connect to the cluster using any of --bootstrap-server localhost:9092, --bootstrap-server localhost:9093, --bootstrap-server localhost:9092 in their commands
### Directories ./data/kafka1, ./data/kafka2, ./data/kafka3 must exist because the cluster data and metadata is stored in these directories
