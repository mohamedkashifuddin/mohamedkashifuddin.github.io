---
layout: default
title: Projects
---

## 🛠️ My Projects

Here's a showcase of my key data engineering projects, demonstrating my skills in building scalable and efficient data solutions across various platforms.

---

### **1. GCP E-commerce Data Pipeline (Personal Project)**

* **Repository:** [https://github.com/mohamedkashifuddin/gcp-ecommerce-data-pipeline](https://github.com/mohamedkashifuddin/gcp-ecommerce-data-pipeline)
* **Description:** An end-to-end batch processing data pipeline built on **Google Cloud Platform (GCP)**. This project implements a **medallion architecture (Bronze, Silver, Gold layers)**, ingesting simulated e-commerce data and transforming it for analytical consumption. It highlights best practices in data governance, scalability, and orchestration.
* **Key Features:**
    * **Simulated Raw Data Ingestion:** Uses Google Cloud Functions to generate and land raw CSV data in GCS.
    * **Bronze Layer:** Ingests raw data into GCS (Parquet) using **Dataproc PySpark** for raw data storage.
    * **Silver Layer:** Cleans, transforms, and conforms data from Bronze to Silver layer in GCS (Parquet) using **Dataproc PySpark**.
    * **Gold Layer:** Curates data for analytics in **BigQuery** using **dbt (data build tool)** for dimensional modeling.
    * **Orchestration:** Leverages **Apache Airflow (Google Cloud Composer)** for end-to-end pipeline scheduling and management.
    * **Visualization:** Integration with **Metabase** for business intelligence dashboards.
* **Technologies Used:** GCP (GCS, Dataproc, BigQuery, Cloud Functions, Composer), PySpark, dbt, Apache Airflow, Python, Metabase.



---

### **2. Multi-Cloud Data Workload Transition (From Kloudone)**

* **Description:** Led the transition of large-scale data workloads to a new **cloud platform (Azure/GCP)**, ensuring minimal disruption to downstream processes. This involved comprehensive migration strategies, rigorous data integrity validation, and performance optimization to streamline ETL data workflows in the new environment.
* **Role & Impact:** Played a pivotal role in ensuring continuity and efficiency during a major platform shift. My work contributed to maintaining processing efficiency and enhancing data integrity across diverse datasets.
* **Key Highlights:**
    * Managed the migration of critical data workloads, minimizing downtime.
    * Conducted extensive performance validation and optimization.
    * Enhanced data validation processes, ensuring higher data integrity and consistency.
* **Technologies Used:** Microsoft Azure, Google Cloud Platform (GCP), ETL tools, SQL, Performance Optimization, Data Validation.

---

### **3. Scalable Data Pipeline Optimization with Snowflake & Azure (From DXC Technology)**

* **Description:** Optimized and maintained scalable data pipelines designed to process upstream data from **Azure Blob Storage** and store it efficiently in **Snowflake**. This project significantly improved data accessibility for analytics and reporting, involving the design and enhancement of ETL workflows to meet evolving business requirements. Managed end-to-end data processing across **Snowflake-based pipelines** and **Databricks-powered transformations**.
* **Role & Impact:** Directly contributed to enhancing the reliability and efficiency of critical data flows, ensuring timely and accurate data delivery for business insights.
* **Key Highlights:**
    * Designed and implemented new and enhanced existing ETL workflows.
    * Managed data processing across multi-architecture pipelines (Snowflake, Databricks).
    * Ensured efficient and reliable data processing from diverse sources.
* **Technologies Used:** Snowflake, Microsoft Azure (Azure Blob Storage), Databricks, PySpark, SQL, ETL/ELT.

---

### **4. Automated Operational Task Optimization (From Kloudone)**

* **Description:** Designed and implemented automation solutions for key operational tasks, significantly reducing manual interventions and improving system stability. This initiative led to a **10% reduction in manual effort** and streamlined daily data operations.
* **Role & Impact:** Enhanced the overall efficiency and reliability of data workflows by automating repetitive and error-prone manual tasks.
* **Key Highlights:**
    * Identified and automated recurring operational processes.
    * Improved system stability and reduced manual overhead.
    * Fine-tuned data ingestion and transformation for efficiency.
* **Technologies Used:** Python, Automation Scripts, ETL/ELT Processes.

---