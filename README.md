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









## Method:2

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



## Method:3

```mermaid
graph TD;
    A[Start] --> B[Step 1]
    B --> C[Step 2]
    C --> D[Step 3]
    D --> E[Step 4]
    E --> F{Is it complete?}
    F -- Yes --> G[Finish]
    F -- No --> B
```




## Method:4
```mermaid
graph TD;
    A1[Input 1] --> B[Step 1]
    A2[Input 2] --> B
    B --> C[Step 2]
    C --> D[Step 3]
    D --> E[Step 4]
    E --> F{Is it complete?}
    F -- Yes --> G[Finish]
    F -- No --> B

```


