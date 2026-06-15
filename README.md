# ⚡ EV Charging Analytics Pipeline using Apache Druid, Neon PostgreSQL & Superset

## 🚀 Overview

This project demonstrates a complete ELT (Extract, Load, Transform) analytics pipeline for EV Charging Station data using Apache Druid, Neon PostgreSQL, and Apache Superset.

The objective is to ingest charging transaction data, perform analytical transformations, and build interactive dashboards for business insights.

---

## 🏗️ Architecture

### Data Flow

1. EV Charging Dataset stored locally (CSV)
2. Data loaded into Neon PostgreSQL
3. Apache Druid ingests data from PostgreSQL
4. Data transformed using Druid SQL (ELT approach)
5. Analytical queries executed
6. Visualizations created in Apache Superset

```text
EV Charging Dataset
        │
        ▼
Neon PostgreSQL
        │
        ▼
Apache Druid
        │
        ▼
Druid SQL Transformations
        │
        ▼
Apache Superset Dashboard
```

---

## ⚙️ Tech Stack

* Apache Druid
* Neon PostgreSQL
* Apache Superset
* Docker
* SQL
* Python
* CSV Dataset

---

## 🔄 ELT Workflow

### Extract

Raw EV charging station data collected from CSV dataset.

### Load

Data loaded into Neon PostgreSQL and ingested into Apache Druid.

### Transform

Business transformations performed using Druid SQL:

* Revenue calculations
* Daily aggregations
* Station performance metrics
* Payment method analysis

---

## 📊 Analytics Performed

### ⚡ Total Electricity Delivered

Measures the total energy delivered through charging stations.

### 💰 Revenue Analysis

Calculates total revenue generated from charging sessions.

### 📅 Daily Revenue Trends

Tracks daily revenue performance.

### 💳 Payment Method Distribution

Analyzes customer payment preferences.

### 🚗 Station Performance Analysis

Identifies top-performing charging stations.

---

## 📈 Dashboard Visualizations

Interactive dashboards were created using Apache Superset to monitor:

* Revenue KPIs
* Charging Activity
* Station Utilization
* Payment Analytics
* Daily Trends

---

## 🐳 Docker Usage

Docker was used to deploy and manage Apache Superset efficiently.

### Run Superset

```bash
cd superset
docker compose -f docker-compose-non-dev.yml up -d
```

Access Superset:

```text
http://localhost:8088
```

---

## 📸 Project Screenshots

### Apache Druid Ingestion

<img width="893" height="484" alt="Screenshot 2026-06-15 102850" src="https://github.com/user-attachments/assets/cc1cf9fa-afd5-4dda-8261-86ae69842a96" />


### Druid Datasource

<img width="1366" height="768" alt="Screenshot 2026-06-15 103607" src="https://github.com/user-attachments/assets/bc557513-a33c-4c92-b727-aa99e91859ef" />


### SQL Transformations

<img width="987" height="479" alt="Screenshot 2026-06-15 111423" src="https://github.com/user-attachments/assets/d753d2f2-508f-447a-b575-2d7a36e4a27e" />


### Superset Connection

<img width="537" height="629" alt="510b9c42-c857-41f5-beb6-6cc5261caf82" src="https://github.com/user-attachments/assets/6ac11182-f7e7-47f9-a290-4149753e1f3a" />

### Dashboard Visualizations

<img width="1366" height="768" alt="Screenshot 2026-03-16 211219" src="https://github.com/user-attachments/assets/b2b22599-2af9-4999-9c8e-6cdf474b5746" />


---

## 🎯 Key Learnings

* ELT Architecture
* Real-Time Analytics
* Apache Druid Ingestion
* SQL-Based Data Transformation
* Dashboard Development
* Business Intelligence Workflows

---

## 👨‍💻 Author

**Chandra Shekhara Mavulla**
