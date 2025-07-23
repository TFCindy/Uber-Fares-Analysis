# 📑 Uber Fares Data Analysis — Comprehensive Report

---

## ✅ Introduction

This report presents a comprehensive analysis of an Uber Fares dataset. The main goal is to uncover trends in fare distribution, estimate ride durations (using trip distance and assumed average speed), identify time-based patterns in rider demand, and highlight geographic ride hotspots. The insights help stakeholders make data-driven decisions to improve operational efficiency and rider satisfaction.

---

## ⚙️ Methodology

**Data Source:**  
The dataset was sourced from [Kaggle](#) *(add your actual link if public)*.  
Key variables include:
- `pickup_datetime`
- `trip_distance`
- `fare_amount`
- Pickup and drop-off coordinates

**Data Preparation:**  
- Loaded raw data into Power BI using Power Query.
- Checked for missing values and duplicates — these were removed.
- Verified and corrected data types (date/time columns, numeric values).
- Added calculated columns:
  - **Estimated Ride Duration:** Since `dropoff_datetime` was missing, duration was estimated using:
    ```
    Estimated Duration (Minutes) = (trip_distance / 30) * 60
    ```
    assuming an average speed of 30 km/h.
  - Extracted date parts: hour, day, month for time trend analysis.

**Tools & Techniques:**  
- Power BI for cleaning, transformation, DAX calculations, and interactive visuals.
- DAX formulas for duration calculation, custom measures, and dynamic filters.
- Dashboard designed with consistent color palette, professional formatting, and clear interactivity.

---

## 📊 Analysis

The analysis focused on four main areas:

1️⃣ **Fare Distribution**  
- Histogram and box plot visuals show how fares are distributed.
- Most fares are in the $10–$20 range with some high-value outliers.
- Box plot helps identify median, quartiles, and extreme fare values.

2️⃣ **Estimated Ride Durations**  
- Since true drop-off times are unavailable, duration was estimated as described.
- Histograms and box plots show that most rides last between 10–20 minutes.
- Time-based visuals (line charts) reveal how estimated durations vary by hour of day.

3️⃣ **Time Series Trends**  
- Analyzed total ride volume by hour, day, and weekday.
- Identified clear peaks during morning (7–9 AM) and evening (5–7 PM) rush hours.
- Trend lines show consistent weekly patterns with higher demand on weekdays.

4️⃣ **Geographic Distribution**  
- Map visuals plot pickup coordinates.
- Clusters highlight the highest ride density in city centers and key hotspots.
- Geographic insights help identify high-demand areas for resource allocation.

---

## 🔑 Results

**Key findings include:**

- **Fare Range:** Majority of fares are between **$10–$20**, with few outliers.
- **Ride Duration:** Estimated durations mostly cluster around **10–20 minutes**, typical for city trips.
- **Peak Times:** Clear demand peaks during commuter rush hours.
- **Hotspots:** Central business districts and major intersections show highest pickup density.

---

## 📝 Conclusion

The Uber Fares analysis provides actionable insight into rider behavior:
- Short trips dominate the data, suggesting local urban rides.
- Clear time patterns indicate predictable daily peaks.
- Spatial patterns reveal the importance of targeted driver distribution.

---

## 💡 Recommendations

Based on the findings, the following actions are recommended:

1️⃣ **Optimize Driver Placement:**  
Position drivers strategically in high-demand zones during peak hours to minimize wait times.

2️⃣ **Dynamic Pricing:**  
Implement surge pricing during rush hours to balance demand and supply while maximizing revenue.

3️⃣ **Off-Peak Promotions:**  
Offer discounts during off-peak times to encourage more rides and utilize driver capacity.

4️⃣ **Outlier Monitoring:**  
Investigate unusually high fares for potential data entry errors or fraudulent activity.

---

## 📎 Notes

- **Estimated Duration Limitation:**  
  The ride duration is an estimate based on an assumed average speed. For precise operational modeling, real pickup and drop-off timestamps are recommended.

---

## ✅ Author

**MUNEZERO Cindy*  
**Adventist University of Central Africa/Introduction to Big Data**  
**25** July 2025

