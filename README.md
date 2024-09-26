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




## Method:4 (TWO input)


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



## Method:5 (URL)
```mermaid
graph TD;
    A1[Input 1<br><a href="https://example.com/input1">Link</a>] --> B[Step 1<br><a href="https://example.com/step1">Details</a>]
    A2[Input 2<br><a href="https://example.com/input2">Link</a>] --> B
    B --> C[Step 2<br><a href="https://example.com/step2">Details</a>]
    C --> D[Step 3<br><a href="https://example.com/step3">Details</a>]
    D --> E[Step 4<br><a href="https://example.com/step4">Details</a>]
    E --> F{Is it complete?}
    F -- Yes --> G[Finish<br><a href="https://example.com/finish">Link</a>]
    F -- No --> B
```



## Method:6 (Image)
```mermaid
graph TD;
    A1[Input 1<br><img src="https://i.pinimg.com/736x/5e/9f/22/5e9f22fe0856cebcfa5409dd0f7b00ca.jpg" width="50" height="50"/>] --> B[Step 1]
    A2[Input 2<br><img src="https://cdn-icons-png.freepik.com/512/15686/15686999.png" width="50" height="50"/>] --> B
    B --> C[Step 2]
    C --> D[Step 3]
    D --> E[Step 4]
    E --> F{Is it complete?}
    F -- Yes --> G[Finish]
    F -- No --> B



