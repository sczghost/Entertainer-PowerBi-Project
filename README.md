# Entertainer-PowerBi-Project 
# 🎬 Entertainer Analytics Project

## 📖 Overview

This project analyzes the career journeys of entertainers (actors, singers, performers) using **Power BI**.
It provides insights into **career milestones, longevity, gender representation, and breakthrough eras** through an interactive dashboard.

---

## 🎯 Objectives

* Analyze entertainer demographics (gender, alive/deceased).
* Measure career milestones (breakthrough age, first award, active span).
* Identify trends (breakthroughs by year/decade, cumulative growth).
* Explore detailed entertainer profiles with timelines.
* Provide interactive slicers and filters for deeper insights.

---

## 📂 Data Sources

The solution uses three Excel datasets:

1. **Basic Info** – Name, Gender, Birth Year, Death Year
2. **Breakthrough Info** – Breakthrough Year, Breakthrough Work, First Award Year
3. **Last Work Info** – Last Major Work Year

---

## ⚙️ Workflow

**ETL (Power Query)** → Clean & transform Excel data
**Data Model (DAX)** → Relationships, Calculated Columns, Measures
**Visualization (Power BI)** → Interactive dashboards

---

## 🏗 Architecture

```
Excel Files → Power Query (ETL) → Data Model (Entertainers, Events, YearTable) 
            → DAX (Columns & Measures) → Power BI Dashboard
```

---

## 📊 Dashboard Pages

**Page 1 – Overview**

* KPIs: Total Entertainers, Alive Entertainers, % Female, Median Age at Breakthrough, Avg Active Span
* Charts: Breakthroughs by Year, Cumulative Breakthroughs, Breakthroughs by Decade
* Detail Table & Slicers

**Page 2 – Entertainer Details**

* Entertainer profile cards
* Career timeline of events (Birth, Breakthrough, Awards, Last Work, Death)

---

## 📄 Documentation

This repo includes:

* **HLD.docx** – High Level Design
* **LLD.docx** – Low Level Design
* **Architecture.docx** – System architecture
* **Wireframe.docx** – Dashboard wireframes
* **Project Code.docx** – DAX measures & Power Query M scripts
* **DPR.docx** – Detailed Project Report

---

## 🚀 How to Use

1. Clone this repo.
2. Open `Entertainer_Analytics.pbix` in Power BI Desktop.
3. Place the Excel datasets in the same directory.
4. Refresh the data to load updated visuals.

---

## 📌 Insights

* Golden era of breakthroughs: **1950s–1970s**
* Female representation: **\~28.6%**, rising in modern decades
* Many entertainers had **50+ year careers**
* Strong link between **breakthrough age and career longevity**

---

## 🔮 Future Enhancements

* Add external datasets (box office, streaming, social metrics).
* Enable automated refresh with Power BI Service.
* Extend to predictive modeling for career longevity.

---

✨ Developed with **Power BI**, **Excel**, and **DAX**.
