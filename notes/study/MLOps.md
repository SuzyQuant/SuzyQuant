[The Modern MLOps Blueprint](https://medium.com/slalom-data-ai/the-modern-mlops-blueprint-c8322af69d21)

![image](https://user-images.githubusercontent.com/61100293/218274734-927a6979-71ab-439a-98d4-6737fedf455a.png)

```mermaid
stateDiagram-v2

    DATA --> ML
    ML --> DEV
    DEV --> OPS
    OPS --> DATA
  


    DATA --> Production
    Production --> Identify
    Identify --> Collect
    Collect --> Process
    Process --> Store 
    Store --> Requirements
    Store --> DATA 
       
    ML --> Requirements
    Requirements --> Explore
    Explore --> Extract
    Extract --> Train
    Train --> Optimize
    Optimize --> Optimal_Model 
    Optimize --> ML
    
    DEV --> Optimal_Model
    Optimal_Model --> Plan 
    Plan --> Develop
    Develop --> Package
    Package --> Test
    Test --> Staging
    Test --> DEV
    
    OPS --> Staging
    Staging --> Release 
    Release --> Configure
    Configure --> Monitor
    Monitor --> Validate
    Validate --> OPS
```

Where is the current project at?
What are the requirements from the client?
How much does each state cost?
How long does it take to deliver?
