# strangematter_ifc_4x
```mermaid
---
title: Breaking Down IFC into the Strange Matter Protocol
---
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```
