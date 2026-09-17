# FIFA World Cup Match Performance Analysis (2006–2026)

## 📌 Project Overview

This project analyzes FIFA World Cup match performance from 2006 to 2026 using data analytics, SQL, cloud technologies, and interactive visualization.

The project focuses on understanding match outcomes, team performance, scoring patterns, and tournament-level trends through an interactive Power BI dashboard.

The data was stored and processed using AWS services, queried using Amazon Athena and SQL, and finally connected to Power BI for visualization and analysis.

---

## 🎯 Objectives

- Analyze FIFA World Cup match results from 2006 to 2026
- Understand team performance and match outcomes
- Analyze goals and scoring patterns
- Identify trends across different World Cup tournaments
- Perform SQL-based data analysis
- Use AWS services as part of a cloud-based data workflow
- Build an interactive Power BI dashboard
- Demonstrate an end-to-end data analytics workflow

---

## 📊 Dataset

The project uses FIFA World Cup match-level data covering tournaments from 2006 to 2026.

The dataset contains match-related information such as:

- World Cup year
- Team 1
- Team 2
- Half-time score
- Full-time score
- Match winner
- Match performance information

**Dataset file:** `football-2006-2026.csv`

---

## 🛠️ Tools & Technologies

- **Amazon S3** – Cloud storage for the dataset
- **AWS Glue** – Data cataloging and crawler
- **Amazon Athena** – SQL querying of the data
- **SQL** – Data querying and analysis
- **Microsoft Power BI** – Interactive dashboard and visualization
- **GitHub** – Project documentation and version control

---

## 🔄 Data Workflow

```text
Football Match Dataset
        ↓
     Amazon S3
        ↓
   AWS Glue Crawler
        ↓
    Data Catalog
        ↓
   Amazon Athena
        ↓
       SQL
        ↓
    Power BI
        ↓
Interactive Dashboard
