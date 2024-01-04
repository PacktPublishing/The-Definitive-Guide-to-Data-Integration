# Kafka ecosystem
```mermaid
graph LR
    A[Apache Kafka] --> B[Producers]
    A --> C[Consumers]
    A --> D[Brokers]
    A --> E[Kafka Streams]
    A --> F[Kafka Connect]
    G[Other Open-Source Data Technologies] --> H[Apache Flink]
    G --> I[Apache NiFi]
    G --> J[Apache Cassandra]
    class A main
    class B,C,D,E,F secondary
    class G main
    class H,I,J secondary
```

This diagram provides a visual representation of the Kafka ecosystem, as well as some other influential open-source data technologies. The main components of the Kafka architecture, such as Producers, Consumers, and Brokers, are connected to the central Apache Kafka node. Additional features, like Kafka Streams and Kafka Connect, are also linked to Apache Kafka. Lastly, the diagram highlights other open-source data technologies, such as Apache Flink, Apache NiFi, and Apache Cassandra.