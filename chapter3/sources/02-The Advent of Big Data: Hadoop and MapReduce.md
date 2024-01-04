# The Advent of Big Data: Hadoop and MapReduce

```mermaid
graph TB
A[Big Data]
B[Hadoop]
C[MapReduce]
D[Hadoop Distributed File System HDFS]
E[Hadoop MapReduce Engine]
F[Google File System GFS]
G[Google's MapReduce]
H[Map Function]
I[Reduce Function]
J[Apache Spark]
K[Modern Data Stack]

A --> B
A --> C
B --> D
B --> E
B -.-> F
B -.-> G
C --> H
C --> I
C -.-> G
D -.-> F
E -.-> G
H --> J
I --> J
J --> K
```

This schema illustrates the chapter using the Mermaid syntax. It shows the relationships between the advent of big data, Hadoop, MapReduce, Hadoop Distributed File System (HDFS), Hadoop MapReduce Engine, Google File System (GFS), Google's MapReduce, Map function, Reduce function, Apache Spark, and the modern data stack. The dashed lines represent inspiration or foundation relationships, while the solid lines depict direct connections or development paths.	