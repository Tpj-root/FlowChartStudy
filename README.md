# FlowChartStudy

This is a sample of a GitHub flow chart inside the README.md.


# Help 

https://docs.github.com/en/get-started/writing-on-github/working-with-advanced-formatting/creating-diagrams


## Method:1

```mermaid
graph TD;
    A[Start] --> B{Decision};
    B -- Yes --> C[Process 1];
    B -- No --> D[Process 2];
    C --> E[End];
    D --> E;
```


## notes

A, B, C, and D represent nodes









## Method:1

```mermaid
graph TD;
    A[Start] --> B{Is data available?}
    B -- Yes --> C[Preprocess Data]
    B -- No --> D[Gather Data]
    D --> E[Data Collection Complete]
    E --> C
    
    C --> F{Is preprocessing successful?}
    F -- Yes --> G[Run Analysis]
    F -- No --> H[Check Errors]
    H --> I[Fix Errors]
    I --> C
    
    G --> J{Is analysis complete?}
    J -- Yes --> K[Generate Report]
    J -- No --> L[Review Analysis]
    L --> G
    
    K --> M[End]
```



