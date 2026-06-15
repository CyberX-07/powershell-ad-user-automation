# Architecture Diagram

```mermaid
flowchart TD

A[HR Input Template] --> B[Input Validation]
B --> C[PowerShell Automation]
C --> D[Excel to CSV Processing]
D --> E[Business Logic]
E --> F[Active Directory]
F --> G[Execution Logging]
```
