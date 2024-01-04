Kimsball star schema concept

```mermaid
graph LR
  F([Fact_Sales])
  D1(Dim_Date)
  D2(Dim_Product)
  D3(Dim_Customer)
  D4(Dim_Store)
  
  F --> D1
  F --> D2
  F --> D3
  F --> D4
```

In this example, we have a fact table Fact_Sales and dimension tables Dim_Date, Dim_Product, Dim_Customer, and Dim_Store. The arrows indicate the relationships between the fact table and the dimension tables.
