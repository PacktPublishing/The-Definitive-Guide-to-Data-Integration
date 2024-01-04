```mermaid
graph TB
A[Raw Data] -->|Staging| B[Staging Layer]
B -->|Preparation| C[Bronze Layer]
C -->|Transformation and Cleansing| D[Silver Layer]
D -->|Creation of Aggregates, KPIs| E[Gold Layer]
E -->|Consumption| F[Insight Layer]
```