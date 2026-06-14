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

(Add Screenshot Here)

### Druid Datasource

(Add Screenshot Here)

### SQL Transformations

(Add Screenshot Here)

### Superset Connection

(Add Screenshot Here)

### Dashboard Visualizations

(Add Screenshot Here)

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
