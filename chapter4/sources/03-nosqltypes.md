

```mermaid
graph TD
   G[Time Series DB]
  A[NoSQL Databases]
  B[Document-Based]
  C[Column-Based]
  D[Key-Value]
  E[Graph]
  F[Hybrid SQL/NoSQL]

  A-->B
  A-->C
  A-->D
  A-->E
  A-->F
  A-->G

  B---|Examples| H[CouchDB]

  C---|Examples| I[Cassandra]
  C---|Examples| J[HBase]

  D---|Examples| K[Redis]
  D---|Examples| L[Riak]
  D---|Examples| Q[DynamoDB]

  E---|Examples| M[Neo4j]
  E---|Examples| N[OrientDB]

  F---|Examples| O[CockroachDB]
  F---|Examples| P[ArangoDB]
<<<<<<< HEAD
```
=======

  G---|Examples| S[InfluxDB]

  ```
>>>>>>> a78c7e31022020dc122c814604250d1fe7bf8adb
