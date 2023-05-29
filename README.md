## Kafka Cluster Config

- The Provided Kafka Cluster has 3 brokers which act as a controller and a broker as well
- Docker opens up the ports at 9092, 9093, 9094 for external connections to the brokers
- One can connect to the cluster using any of --bootstrap-server localhost:9092, --bootstrap-server localhost:9093, --bootstrap-server localhost:9092 in their commands
- All the data related to the cluster will be stored at docker volumes called kafka1, kafka2, kafka3

## Jenkins Config

- The Jenkins accepts external connections at port 9092
- All the jenkins related data will be stored at docker volume jenkinsdata
