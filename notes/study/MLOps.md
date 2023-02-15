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

### Gantt Chart
```mermaid
gantt
    title A Gantt Diagram
    dateFormat  YYYY-MM-DD
    
    section DATA
    Production   :a1, 2014-01-01, 5d
    Identify     :a2, after a1  , 3d
    Collect      :a3, 2014-02-09, 10d
    Process      :a4, after a3, 7d
    Store        :a5, after a4, 2d
    
    section ML
    Requirements :a6, after a5, 10d
    Explore      :after a6, 20d
    Extract      :a7, 2014-01-01, 30d
    Train        :after a7, 20d
    Optimize     :a8, 20d
    
    section DEV
    Optimal_Model :a1, 2014-01-01, 30d
    Plan         :after a1  , 20d
    Develop      :a1, 2014-01-01, 30d
    Package      :after a1  , 20d
    Test         :after a1  , 20d

```
Where is the current project at?

What are the requirements from the client?

How much does each state cost?

How long does it take to deliver?

On a manager's perspective, how do you connect different industries?
