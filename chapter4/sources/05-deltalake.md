```mermaid
flowchart LR
    mytable/-->_delta_log
    mytable/-->_date=2024-01-01
    subgraph delta_log/
    _delta_log-->00000.json
    _delta_log-->00001.json
    _delta_log-->....json
    end
    subgraph date=2024-01-01/
    _date=2024-01-01-->file-1.parquet
    _date=2024-01-01-->file-2.parquet
    _date=2024-01-01-->file...
    end
```
This flowchart shows the main components of the Delta Lake folder organization, including the root folder, the Parquet data files and JSON transaction log files within those folders.