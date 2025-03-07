# kafka-docker-playground-connect ![CI](https://github.com/vdesabou/kafka-docker-playground-connect/workflows/CI/badge.svg?branch=master)

Create Kafka Connect image with Confluent Hub connectors required for [vdesabou/kafka-docker-playground](https://github.com/vdesabou/kafka-docker-playground) repository

| connector  | version |
|---|---|
| confluentinc-connect-transforms  | 1.4.0 |
| confluentinc-kafka-connect-activemq  | 11.0.1 |
| confluentinc-kafka-connect-activemq-sink  | 1.3.2 |
| confluentinc-kafka-connect-amps  | 1.0.0-preview |
| confluentinc-kafka-connect-appdynamics-metrics  | 1.1.3 |
| confluentinc-kafka-connect-aws-cloudwatch-logs  | 1.1.0 |
| confluentinc-kafka-connect-aws-cloudwatch-metrics  | 1.1.3 |
| confluentinc-kafka-connect-aws-dynamodb  | 1.1.4 |
| confluentinc-kafka-connect-aws-lambda  | 1.1.1 |
| confluentinc-kafka-connect-aws-redshift  | 1.0.5 |
| confluentinc-kafka-connect-azure-blob-storage  | 1.6.1 |
| confluentinc-kafka-connect-azure-blob-storage-source  | 1.4.3 |
| confluentinc-kafka-connect-azure-data-lake-gen1-storage  | 1.6.1 |
| confluentinc-kafka-connect-azure-data-lake-gen2-storage  | 1.6.1 |
| confluentinc-kafka-connect-azure-event-hubs  | 1.2.0 |
| confluentinc-kafka-connect-azure-functions  | 1.0.9 |
| confluentinc-kafka-connect-azure-search  | 1.0.4 |
| confluentinc-kafka-connect-azure-service-bus  | 1.1.3 |
| confluentinc-kafka-connect-azure-sql-dw  | 1.0.4 |
| confluentinc-kafka-connect-cassandra  | 2.0.0 |
| confluentinc-kafka-connect-data-diode  | 1.1.1 |
| confluentinc-kafka-connect-datadog-metrics  | 1.1.3 |
| confluentinc-kafka-connect-datagen  | 0.4.0 |
| confluentinc-kafka-connect-elasticsearch  | 11.0.2 |
| confluentinc-kafka-connect-firebase  | 1.2.0 |
| confluentinc-kafka-connect-ftps  | 1.0.3-preview |
| confluentinc-kafka-connect-gcp-bigtable  | 1.0.7 |
| confluentinc-kafka-connect-gcp-dataproc-sink  | 1.1.1 |
| confluentinc-kafka-connect-gcp-functions  | 1.1.3 |
| confluentinc-kafka-connect-gcp-pubsub  | 1.0.6 |
| confluentinc-kafka-connect-gcp-spanner  | 1.0.4 |
| confluentinc-kafka-connect-gcs  | 5.5.5 |
| confluentinc-kafka-connect-gcs-source  | 1.4.3 |
| confluentinc-kafka-connect-github  | 1.0.4 |
| confluentinc-kafka-connect-hbase  | 1.0.7 |
| confluentinc-kafka-connect-hdfs  | 10.0.1 |
| confluentinc-kafka-connect-hdfs2-source  | 1.4.3 |
| confluentinc-kafka-connect-hdfs3  | 1.1.1 |
| confluentinc-kafka-connect-hdfs3-source  | 1.4.3 |
| confluentinc-kafka-connect-http  | 1.2.2 |
| confluentinc-kafka-connect-ibmmq  | 11.0.1 |
| confluentinc-kafka-connect-ibmmq-sink  | 1.3.2 |
| confluentinc-kafka-connect-influxdb  | 1.2.1 |
| confluentinc-kafka-connect-jdbc  | 10.0.2 |
| confluentinc-kafka-connect-jira  | 1.0.3-preview |
| confluentinc-kafka-connect-jms  | 11.0.1 |
| confluentinc-kafka-connect-jms-sink  | 1.3.2 |
| confluentinc-kafka-connect-kinesis  | 1.3.3 |
| confluentinc-kafka-connect-kudu  | 1.0.1 |
| confluentinc-kafka-connect-maprdb  | 1.1.2 |
| confluentinc-kafka-connect-marketo  | 1.0.0-preview |
| confluentinc-kafka-connect-mqtt  | 1.4.0 |
| confluentinc-kafka-connect-omnisci  | 1.0.2 |
| confluentinc-kafka-connect-oracle-cdc  | 1.0.5 |
| confluentinc-kafka-connect-pagerduty  | 1.0.2 |
| confluentinc-kafka-connect-pivotal-gemfire  | 1.0.6 |
| confluentinc-kafka-connect-prometheus-metrics  | 1.1.3-preview |
| confluentinc-kafka-connect-rabbitmq  | 1.5.0 |
| confluentinc-kafka-connect-rabbitmq-sink  | 1.5.0 |
| confluentinc-kafka-connect-replicator  | 6.1.0 |
| confluentinc-kafka-connect-s3  | 10.0.0 |
| confluentinc-kafka-connect-s3-source  | 1.4.3 |
| confluentinc-kafka-connect-salesforce  | 1.7.15 |
| confluentinc-kafka-connect-salesforce-bulk-api  | 1.7.15 |
| confluentinc-kafka-connect-servicenow  | 2.0.3 |
| confluentinc-kafka-connect-sftp  | 2.2.4 |
| confluentinc-kafka-connect-snmp  | 1.1.2 |
| confluentinc-kafka-connect-solace-sink  | 1.3.2 |
| confluentinc-kafka-connect-solace-source  | 1.2.0 |
| confluentinc-kafka-connect-splunk-source  | 1.0.3 |
| confluentinc-kafka-connect-sqs  | 1.1.1 |
| confluentinc-kafka-connect-syslog  | 1.3.2 |
| confluentinc-kafka-connect-tibco-sink  | 1.3.2 |
| confluentinc-kafka-connect-tibco-source  | 1.2.0 |
| confluentinc-kafka-connect-vertica  | 1.2.5 |
| confluentinc-kafka-connect-zendesk  | 1.0.6 |
| debezium-debezium-connector-mongodb  | 1.4.0 |
| debezium-debezium-connector-mysql  | 1.4.0 |
| debezium-debezium-connector-postgresql  | 1.4.0 |
| debezium-debezium-connector-sqlserver  | 1.4.0 |
| jcustenborder-kafka-connect-redis  | 0.0.2.11 |
| jcustenborder-kafka-connect-spooldir  | 2.0.60 |
| kafka-connect-couchbase  | 3.4.8 |
| mongodb-kafka-connect-mongodb  | 1.2.0 |
| neo4j-kafka-connect-neo4j  | 1.0.9 |
| snowflakeinc-snowflake-kafka-connector  | 1.5.2 |
| splunk-kafka-connect-splunk  | 2.0.2 |
| wepay-kafka-connect-bigquery  | 2.1.0 |
