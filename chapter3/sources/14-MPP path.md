```mermaid
flowchart TB
    A(2013 - Created by Facebook) --> B(2014 - Qubole)
    B --> C{2017}
    C -->|Fork| D(2019 - Starburst Adopt PrestSQL)
    C --> E(2018 - AWS Athena)
    E -->|Fork| D
    E --> F(2020)
    F -->|Fork| G(Ahana)
    G -->|Integrated| H(2023 - IBM)
    D --> |Open Source Track|I(Trino)
    D --> J(Starburst)
    F --> |Open Source Track|K(Presto)
```