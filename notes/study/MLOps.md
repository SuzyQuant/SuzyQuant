[The Modern MLOps Blueprint](https://medium.com/slalom-data-ai/the-modern-mlops-blueprint-c8322af69d21)

![image](https://user-images.githubusercontent.com/61100293/218274734-927a6979-71ab-439a-98d4-6737fedf455a.png)

```mermaid
stateDiagram-v2
    [*] --> DATA
    DATA --> ML
    ML --> [*]

    DATA --> Production
    Production --> Identify
    Identify --> Collect
    Collect --> Process
    Process --> Store
    Store --> DATA 
    Store --> ML 

```
