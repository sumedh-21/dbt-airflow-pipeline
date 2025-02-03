# 🚀 DBT + Airflow + Snowflake Pipeline  

## 📌 Overview  
An automated **data pipeline** using **Apache Airflow, DBT, and Snowflake** for seamless **data transformation, orchestration, and validation** with **Astronomer Cosmos**.  

---

## 🔥 Features  
- **Automated DBT Transformations** in Snowflake  
- **Airflow Orchestration & Scheduling**  
- **Containerized with Docker & Astronomer**  
- **Data Validation with `dbt test`**  

---

## 🚀 Quick Start  
```sh
git clone https://github.com/yourusername/dbt-airflow-pipeline.git
cd dbt-airflow-pipeline
astro dev start
astro dev trigger dbt_dag
```
➡️ **View results:** [http://localhost:8080](http://localhost:8080)  

Stop pipeline & suspend Snowflake compute:  
```sh
astro dev stop
ALTER WAREHOUSE dbt_wh SUSPEND;
```

---

## 🛠️ Technologies Used  
- **Apache Airflow** (Workflow scheduling)  
- **DBT** (SQL-based transformations)  
- **Snowflake** (Cloud data warehouse)  
- **Docker & Astronomer** (Containerized deployment)  





