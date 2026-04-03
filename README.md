# Customer360-Pipeline-
End-to-end data engineering project: Kafka ingestion, Spark ETL, Airflow orchestration, PostgreSQL storage, Power BI dashboards.

---

## 🚀 Project Overview
This project simulates an **E-commerce Customer360 pipeline**. It ingests customer events in real time, processes them with Spark, orchestrates workflows with Airflow, stores data in PostgreSQL, and visualizes insights in Power BI.

The goal: **learn by building** and showcase a complete data engineering workflow.

---

## 🏗️ Architecture
1. **Data Ingestion** – FastAPI produces mock customer events → Kafka streams them.
2. **ETL Processing** – Spark consumes Kafka, cleans & transforms data.
3. **Storage** – PostgreSQL stores structured data.
4. **Orchestration** – Airflow automates ingestion + ETL jobs.
5. **Visualization** – Power BI dashboards show customer insights.

---

## 🔧 Tech Stack
- **Languages**: Python, SQL
- **Frameworks**: FastAPI, PySpark
- **Data Tools**: Kafka, Airflow, PostgreSQL
- **Visualization**: Power BI
- **Cloud**: AWS S3 (optional for storage)

---

## 📂 Repository Structure
