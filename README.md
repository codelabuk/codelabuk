# Afzal Ahmed

Distributed systems engineer who builds data infrastructure — Apache Arrow Flight, Kafka, Spark, Iceberg, Delta Lake, and the low-latency serving layers that sit on top of them.

13+ years in software, the last 7+ focused on large-scale data platforms in financial services. Currently a Technical Lead at BNP Paribas, building a lakehouse  architecture based data platform &  Arrow Flight-based columnar Data-as-a-Service layer for a financial data platform.

📝 I write about the internals — spark-submit's JVM/classloader chain, Arrow Flight serialisation, distributed systems tradeoffs — at [codelabuk.hashnode.dev](https://codelabuk.hashnode.dev)

---

## What I work on

**Columnar transport & serving layers** — Arrow Flight servers, record batch pipelines, FieldVector population, low-latency OLAP/API serving on top of Iceberg and Delta Lake.

**Event-driven data pipelines** — Kafka-orchestrated multi-stage pipelines (notification → orchestration → versioning → serving), Spark Structured Streaming, exactly-once semantics.

**Platform migration & re-architecture** — TB-scale on-prem Hadoop → cloud-native (Azure/AWS), zero data loss, resilience patterns for stateful in-memory OLAP (auto-reload on pod restart).

---

## Featured projects

### 🔹 [labuk-query-engine](https://github.com/codelabuk/labuk-query-engine)
Arrow Flight serving layer over Apache Iceberg — HadoopCatalog on MinIO, Scala/SBT, four-module structure. K8s manifests, seed scripts, and a demo client included.

### 🔹 [notification-platform](https://github.com/codelabuk/notification-platform)
A reactive, event-driven data platform rebuilt as a portfolio artifact: Spark Structured Streaming, Kafka, Akka Persistence, Pekko HTTP, and Spark Operator CRDs across a five-module pipeline (Akka processor → Spark analytics → Airflow DAG → Arrow Flight server).

### 🔹 [labuk-data-platform](https://github.com/codelabuk/labuk-data-platform)
Full lakehouse stack — Kafka, Spark, Iceberg, Delta Lake, Arrow Flight DaaS, ClickHouse, ZIO — deployed on OCI Kubernetes.


---

## Stack

`Apache Spark` `Apache Kafka` `Apache Arrow Flight` `Apache Iceberg` `Delta Lake` `Apache Airflow` 'Modern Lakehouse` `Kubernetes` `Apache Flink` `ClickHouse` `Java` `Scala` `Python`  
`Azure` `AWS` `Microservices` `Spring Boot` `Akka/Pekko` `PySpark` 

---

📍 Bangalore, India · [LinkedIn](#) · afzal232@gmail.com
