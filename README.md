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

