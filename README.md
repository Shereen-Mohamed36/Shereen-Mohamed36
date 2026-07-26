# Hi there, I'm Shereen Mohamed Yasen! 👋 

### 🚀 Aspiring Data Engineer & Big Data Enthusiast 
Driven by a passion for building scalable data architectures, optimizing complex pipelines, and turning raw data into actionable enterprise-level insights. I thrive on project-based learning and solving real-world data challenges.

---

### 🎓 Education & Background
*   **B.Sc. in Computers and Artificial Intelligence** – Capital University (formerly Helwan University)
*   **Big Data Training Track** – Samsung Innovation Campus
*   **NextStep Mentorship Program** – UNICEF Mentees (Supported by Deloitte)

---

### 🛠️ Technical Toolbox

#### 🌌 Data Engineering & Big Data Ecosystem
![](https://img.shields.io/badge/Apache_Airflow-017CE2?style=for-the-badge&logo=Apache%20Airflow&logoColor=white)
![](https://img.shields.io/badge/Apache_NiFi-009688?style=for-the-badge&logo=Apache%20NiFi&logoColor=white)
![](https://img.shields.io/badge/Apache_Spark-E25A1C?style=for-the-badge&logo=Apache%20Spark&logoColor=white)
![](https://img.shields.io/badge/Apache_Kafka-231F20?style=for-the-badge&logo=Apache%20Kafka&logoColor=white)
![](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=Power%20BI&logoColor=black)

##### ⚡ Dynamic Data Pipeline Workflow
```mermaid
graph LR
    %% Tool Nodes
    A[📥 Data Sources] 
    B[🔄 Apache NiFi] 
    C[⚡ Apache Kafka] 
    D[⚙️ Apache Spark] 
    E[🗄️ Storage / DBs] 
    F[📊 Power BI]
    Airflow[💨 Apache Airflow]

    %% Flow Connections
    A ==>|Raw Data| B
    B ==>|Ingest & Stream| C
    C ==>|High-Velocity| D
    D ==>|Transform & Load| E
    E ==>|Analyze| F

    %% Airflow Orchestration
    Airflow -.->|Orchestrate| B
    Airflow -.->|Trigger Jobs| D

    %% Custom Tech-Stack Styling (Colors)
    style Airflow fill:#017CE2,stroke:#fff,stroke-width:2px,color:#fff
    style B fill:#009688,stroke:#fff,stroke-width:2px,color:#fff
    style C fill:#231F20,stroke:#fff,stroke-width:2px,color:#fff
    style D fill:#E25A1C,stroke:#fff,stroke-width:2px,color:#fff
    style F fill:#F2C811,stroke:#333,stroke-width:2px,color:#333
    style A fill:#7f8c8d,stroke:#fff,stroke-width:1px,color:#fff
    style E fill:#2980b9,stroke:#fff,stroke-width:1px,color:#fff
