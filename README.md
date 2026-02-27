### 🏗️ My Data Engineering Ecosystem
```mermaid
graph LR
    subgraph "Data Platform (IaC)"
        A[AWS S3 / Data Lake] --- B[Terraform]
    end
    subgraph "ML Pipeline"
        B --> C[Data Pre-processing]
        C --> D[Model Training / X.align]
        D --> E[Evaluation / K-Fold]
    end
    subgraph "Outcome"
        E --> F[Business Insight]
    end
