```mermaid
graph LR
    A[Hadoop] --> B[HDFS]
    A --> C[MapReduce]
    A --> D[YARN]
    A --> E[HBase]
    A --> F[Hive]
    A --> G[Pig]
    A --> H[Sqoop]
    A --> I[Flume]
    
    B --> J((Data Storage))
    C --> K((Data Processing))
    D --> L((Resource Management))
    E --> M((NoSQL Database))
    F --> N((SQL-like Interface))
    G --> O((Data Transformation))
    H --> P((Data Ingestion))
    I --> Q((Log Data Aggregation))
```
The Hadoop ecosystem and its key components. Hadoop is at the center, with arrows connecting it to each of the ecosystem components: HDFS, MapReduce, YARN, HBase, Hive, Pig, Sqoop, and Flume. Each component is then linked to its primary function.