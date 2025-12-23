Below is a **professional, clean, GitHub-ready README.md** written **exactly according to your dataset and Week-3 task**.
You can **copy–paste directly** into your GitHub repository.

---

# 🦠 COVID-19 Data Analysis (Time Series)

## 📌 Project Overview

This project performs **country-wise COVID-19 time-series analysis** using Python.
The analysis includes **daily and weekly case computation**, **country comparisons**, **rolling averages for noise reduction**, **peak detection**, and **basic reproduction trend insights**.
The goal is to understand how COVID-19 spread evolved over time across different countries.

---

## 🎯 Objectives

* Load and analyze country-wise COVID-19 time-series data
* Compute **daily and weekly new cases**
* Compare COVID-19 trends between selected countries
* Apply **rolling averages** to smooth daily fluctuations
* Detect **peak infection periods**
* Derive **basic reproduction insights** based on trends
* Export visualizations and summarize findings

---

## 📁 Dataset Description

* **Rows:** 35,000+
* **Columns:** 10
* **Type:** Daily time-series COVID-19 data

### Dataset Columns

| Column Name    | Description               |
| -------------- | ------------------------- |
| Date           | Reporting date            |
| Country/Region | Country name              |
| Confirmed      | Total confirmed cases     |
| Deaths         | Total deaths              |
| Recovered      | Total recovered cases     |
| Active         | Active cases              |
| New cases      | Daily new confirmed cases |
| New deaths     | Daily new deaths          |
| New recovered  | Daily recoveries          |
| WHO Region     | WHO geographical region   |

📌 Each row represents **one country on one specific date**.

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib

---

## ⚙️ Methodology

### 1️⃣ Data Loading & Preprocessing

* Loaded CSV dataset using Pandas
* Converted `Date` column into datetime format
* Filtered selected countries for comparison

### 2️⃣ Daily & Weekly Analysis

* Used **New cases** as daily case data
* Aggregated data weekly using resampling

### 3️⃣ Rolling Average

* Applied **7-day rolling average** to smooth noise
* Helped identify real trends in case growth/decline

### 4️⃣ Country Comparison

* Compared COVID-19 trends for multiple countries
* Visualized daily and smoothed trends using line plots

### 5️⃣ Peak Detection

* Identified peak infection dates and values per country

### 6️⃣ Basic Reproduction Insight

* Increasing trend → Higher spread (R > 1)
* Decreasing trend → Controlled spread (R < 1)

---

## 📊 Visualizations

* Daily new cases comparison
* 7-day rolling average trend comparison
* Exported charts for reporting and analysis

---

📸 Output Screenshots
📊 Daily COVID-19 Cases Comparison

This plot shows the daily new COVID-19 cases for selected countries, enabling direct comparison of infection trends over time.

Example: India, US, and Brazil daily case trends

![Daily Cases Comparison](<img width="1000" height="500" alt="Daily COVID-19 Cases Comparison" src="https://github.com/user-attachments/assets/1e13aba8-604e-49e1-889d-25496715869d" />
)

📈 7-Day Rolling Average Trend

This visualization applies a 7-day rolling average to smooth daily fluctuations and highlight the actual trend of COVID-19 spread.

![Rolling Average Trend](<img width="1000" height="500" alt="7-Day Rolling Average of COVID-19 Cases" src="https://github.com/user-attachments/assets/820987d1-f6b2-44ad-8d27-2ee7e7a73815" />
)

🔝 Peak Detection Visualization

This output highlights the peak infection period for each country based on the highest number of daily new cases.

![Peak Detection](<img width="270" height="222" alt="image" src="https://github.com/user-attachments/assets/20459007-d510-439c-b70c-7aee9e848416" />
)

🧠 Trend-Based Reproduction Insight

This output helps interpret whether COVID-19 spread was increasing or decreasing based on case trends.

![Reproduction Insight](<img width="640" height="480" alt="rolling_average_trend" src="https://github.com/user-attachments/assets/33386612-827a-4fd2-b599-d4a066e380e1" />
)

## 📈 Key Insights

* Different countries experienced peaks at different times
* Rolling averages reduced reporting noise effectively
* Countries with declining trends showed better control
* Time-series analysis helps understand pandemic behavior

---

## 📁 Project Structure

```
COVID-19-Analysis/
│
├── covid_data.csv
├── covid_analysis.ipynb
├── covid_trend_comparison.png
├── README.md
```

---

## ✅ Conclusion

This project demonstrates how time-series analysis can be used to study pandemic trends.
Rolling averages, peak detection, and country-wise comparison provide valuable insights into the spread and control of COVID-19.

---

## 📌 Author

**Aftab Tamboli**

---


Just tell me 👍
