# A mapreduce process

```mermaid
graph TB
A[Input Data] -->|Split into chunks| B[Mapper 1]
A -->|Split into chunks| C[Mapper 2]
A -->|Split into chunks| D[Mapper 3]
B -->|Key-value pairs| E[Shuffle & Sort]
C -->|Key-value pairs| E[Shuffle & Sort]
D -->|Key-value pairs| E[Shuffle & Sort]
E -->|Grouped key-value pairs| F[Reducer 1]
E -->|Grouped key-value pairs| G[Reducer 2]
F -->|Aggregated/Summarized Data| H[Output Data]
G -->|Aggregated/Summarized Data| H[Output Data]
````

This iagram illustrates a simple MapReduce process. Input data is split into chunks and processed by multiple mapper nodes (Mapper 1, Mapper 2, Mapper 3). The mappers generate key-value pairs, which are then shuffled and sorted before being sent to reducer nodes (Reducer 1, Reducer 2). The reducer nodes aggregate or summarize the grouped key-value pairs, and the final output data is produced as a result.