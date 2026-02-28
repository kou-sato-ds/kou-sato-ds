## 🚀 Current Focus: 2026 Spring Implementation Sprint
現在、これまでの学習で蓄積したデータサイエンスの知見を、実務レベルのコード（MLパイプライン・IaC）へ変換する**「集中実装スプリント」**を実施しています。

- **テーマ**: データの整合性保証、再現性の高いインフラ構築、および「黄金の型」の確立
- **目標**: 2026年11月の転身に向けた、実戦的な開発アセットの完遂

## 🛠 Skills
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)


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
