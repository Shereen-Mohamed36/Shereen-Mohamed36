# Hi there, I'm Shereen Mohamed Yasen! 👋 

### 🚀 Aspiring Data Engineer & Big Data Enthusiast 
Driven by a passion for building scalable data architectures, optimizing complex pipelines, and turning raw data into actionable enterprise-level insights. I thrive on project-based learning and solving real-world data challenges.

---

### 🌐 Comprehensive Data Lifecycle Architecture

Here is how I view, connect, and orchestrate the entire data engineering ecosystem using my tech stack:

```mermaid
graph LR
    %% Data Sources
    subgraph Sources [1. Data Generation]
        A[APIs / Web Scraping]
        B[Relational DBs]
        C[NoSQL & Graph DBs]
    end

    %% Ingestion & Streaming
    subgraph Ingestion [2. Ingestion & Streaming]
        D[Apache NiFi]
        E[Apache Kafka]
    end

    %% Processing & Storage
    subgraph Processing [3. Processing & Storage]
        F[Apache Spark]
        G[Dockerized Environment]
        H[(PostgreSQL / MySQL)]
        I[(MongoDB / Cassandra)]
        J[(Neo4j Graph)]
    end

    %% Orchestration
    subgraph Orchestration [4. Workflow Management]
        K{Apache Airflow}
    end

    %% Serving & BI
    subgraph Consumption [5. Serving & BI]
        L[Power BI Dashboards]
    end

    %% Connections
    A -->|Batch / Stream| D
    B -->|CDC / Extract| D
    C -->|NoSQL Fetch| E
    
    D --> E
    E -->|High-Velocity Streams| F
    
    K -.->|Orchestrates & Monitors| D
    K -.->|Schedules Jobs| F
    G -.->|Containers Strategy| F
    
    F -->|Transform & Load| H
    F -->|Store Unstructured| I
    F -->|Map Relationships| J
    
    H -->|Analytical Querying| L
