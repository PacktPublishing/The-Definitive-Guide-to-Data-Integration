```mermaid
graph LR

subgraph Manufacturing Application
    Event_Stream_Collection --> Event_Stream_Ingestion
    Event_Stream_Ingestion --> Event_Stream_Processing
    Event_Stream_Processing --> Exposition_Stream
end

subgraph Event Processing
    Event_Stream_Collection((Event Stream Collection))
    Event_Stream_Ingestion((Event Stream Ingestion))
    Event_Stream_Processing((Event Stream Processing))
end

subgraph Data Visualization
    Exposition_Stream((Exposition Stream))
end

Event_Stream_Processing --> Exposition_Stream

subgraph Visualization Tools
    Data_Visualization((Visualization Tools))
end

Exposition_Stream --> Data_Visualization
```
