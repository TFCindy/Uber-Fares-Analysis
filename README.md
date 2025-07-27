# 🚕 Uber Fares Data Analysis

## 📌 Short Description
An interactive Power BI analysis of Uber Fares data with estimated ride durations, time-based trends, geographic insights, and practical business recommendations.

---

## 📂 Project Overview

This project analyzes an Uber Fares dataset to understand:
- How fares are distributed
- How ride durations can be estimated (using trip distance and assumed average speed)
- Time-based trends in rider demand
- Geographic patterns of ride activity

The final deliverables include:
- A clean, interactive Power BI dashboard
- A detailed analytical report
- A structured GitHub repository with the dataset, screenshots, and documentation

---

## ⚙️ Methodology

**Data Source:**  
- Original dataset: [Uber Fares Dataset from Kaggle](#)

**Key Steps:**  
1. **Data Cleaning:**  
   - Removed duplicates and null values.
   - Verified data types (dates, numbers).
2. **Duration Estimation:**  
   - As `dropoff_datetime` was unavailable, ride duration was estimated:
     ```
     Estimated Duration (Minutes) = (trip_distance / 30) * 60
     ```
     assuming an average urban speed of 30 km/h.
3. **Visualization:**  
   - Created clear, interactive visuals: histograms, box plots, line charts, and maps.
   - Added filters, slicers, and drill-downs for flexible exploration.

---

## 📊 Dashboard Features

- **Fare Distribution:** Histograms and box plots showing fare spread, median, and outliers.
- **Estimated Ride Durations:** Visualized with histograms and time-based line charts by hour/day.
- **Time Series Trends:** Rides by hour, day, and week.
- **Geographic Map:** Spatial patterns of pickup locations.
- **Interactivity:** Slicers for date, time, distance, and map filters.

All visuals follow consistent colors, clean labels, and a professional layout.

---

## ✅ Repository Structure


**Folders:**
- `data/` — Final cleaned dataset.
- `dashboard/` — Power BI `.pbix` file.
- `screenshots/` — Images showing each project step: loading, cleaning, DAX, dashboard build.
- `REPORT.md` — Detailed report with introduction, methodology, analysis, results, conclusions, and recommendations.

---

## 📈 How to Use This Project

1️⃣ **Clone or Download:**

```bash
git clone https://github.com/TFCindy/Uber-Fares-Analysis.git
## 📑 Report

For detailed explanations of objectives, methods, key findings, and business recommendations, see [`REPORT.md`](./REPORT.md).

---

