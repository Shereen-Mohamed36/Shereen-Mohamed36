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
%%{init: {'theme': 'dark', 'themeVariables': { 'lineColor': '#ff79c6' }}}%%
graph LR
    %% Tool Nodes with HTML Icons
    A[<img src='[https://img.shields.io/badge/Data_Sources-Ingest-lightgrey?style=flat-square'/](https://img.shields.io/badge/Data_Sources-Ingest-lightgrey?style=flat-square'/)>] 
    B[<img src='[https://img.shields.io/badge/Apache_NiFi-009688?style=flat-square&logo=Apache%20NiFi&logoColor=white'/](https://img.shields.io/badge/Apache_NiFi-009688?style=flat-square&logo=Apache%20NiFi&logoColor=white'/)>] 
    C[<img src='[https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=Apache%20Kafka&logoColor=white'/](https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=Apache%20Kafka&logoColor=white'/)>] 
    D[<img src='[https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=Apache%20Spark&logoColor=white'/](https://img.shields.io/badge/Apache_Spark-E25A1C?style=flat-square&logo=Apache%20Spark&logoColor=white'/)>] 
    E[<img src='[https://img.shields.io/badge/Databases-Storage-blue?style=flat-square'/](https://img.shields.io/badge/Databases-Storage-blue?style=flat-square'/)>] 
    F[<img src='[https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=Power%20BI&logoColor=black'/](https://img.shields.io/badge/Power_BI-F2C811?style=flat-square&logo=Power%20BI&logoColor=black'/)>]
    
    %% Orchestration Overlay
    Airflow[<img src='[https://img.shields.io/badge/Apache_Airflow-017CE2?style=flat-square&logo=Apache%20Airflow&logoColor=white'/](https://img.shields.io/badge/Apache_Airflow-017CE2?style=flat-square&logo=Apache%20Airflow&logoColor=white'/)>]

    %% Flow Connections with Moving/Interactive-style Links
    A ==>|Raw Data| B
    B ==>|Stream| C
    C ==>|High Velocity| D
    D ==>|Transform & Load| E
    E ==>|Analytics| F

    %% Airflow Orchestrating the Core
    Airflow -.->|Orchestrate| B
    Airflow -.->|Trigger Jobs| D

    %% Dynamic Linking/Stuffs
    style B fill:#111,stroke:#009688,stroke-width:2px
    style C fill:#111,stroke:#231F20,stroke-width:2px
    style D fill:#111,stroke:#E25A1C,stroke-width:2px
    style Airflow fill:#111,stroke:#017CE2,stroke-width:2px
