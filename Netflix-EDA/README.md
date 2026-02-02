# 🎬 Netflix Content Strategy: Deep Dive Analysis
**Author:** Mark Mutinda  
**Role:** Data Analyst  
**Date:** January 2026

![Netflix Analysis Banner](https://img.shields.io/badge/Data%20Analysis-EDA-red?style=for-the-badge&logo=netflix)
![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)

---

## 📌 Executive Summary
This project explores the Netflix catalog (9,000+ titles) to decode the platform's global content strategy. By analyzing content growth, maturity ratings, and regional hubs, we identify how Netflix has transitioned from a back-catalog archive to an original-content powerhouse.

### 🚀 Key Discoveries
* **The "Originals" Pivot:** Content added to the platform is increasingly "fresh," with most titles added within 0–2 years of their theatrical release.
* **Adult Audience Focus:** Mature content (TV-MA) dominates the TV Show segment, highlighting a strategy centered on prestige drama.
* **Regional Specialization:** While the US remains the production leader, Bollywood actors are the most prolific individuals on the platform, indicating significant regional investment.

---

## 🛠️ Tech Stack & Requirements
* **Core:** `Python 3.x`
* **Data Handling:** `Pandas`, `NumPy`
* **Visualization:** `Matplotlib`, `Seaborn`
* **Environment:** Jupyter Notebook / VS Code

---

## 📊 Methodology & Analytical Framework

### 1. Data Remediation
To ensure high-fidelity insights, we addressed missing data in the `Director`, `Cast`, and `Country` columns by implementing **Categorical Imputation** (flagging as 'Unknown'). We performed **Type Casting** on date strings to enable time-series analysis.

### 2. Core Research Questions
* **Growth Trends:** Is the gap between Movies and TV Shows narrowing?
* **Audience Targeting:** How does rating distribution vary by content type?
* **Global Hubs:** Which markets are growing the fastest?
* **Star Power:** Who are the most frequent faces in Netflix's portfolio?

---

## 📈 Key Visualizations
*Refer to the [EDA.ipynb](./EDA.ipynb) for the full technical breakdown.*

### 
> **Insight:** Movies still represent the majority of the library, but TV Shows have seen a significantly higher growth rate since 2016.

### 
> **Insight:** The "Lag Time" analysis shows a heavy skew toward 0-year delays, proving Netflix's shift toward "Day-and-Date" digital debuts.

---

## 📂 Repository Structure
```text
├── data/
│   └── netflix_titles.csv    # Raw data source
├── notebooks/
│   └── EDA.ipynb             # Detailed analysis & visualization
├── README.md                 # Project summary
