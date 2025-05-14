# 🏠📊 Household Electricity Consumption Analysis  
**Course:** Modern Energy Systems  
**Team 5:**  
- Efstratios Efstratiou (AEM 10489)  
- Dimitrios Koutsikakis (AEM 10532)  
- Kyriacos Tsokkos (AEM 10496)  

## 📌 Project Overview

This repository presents the second project of the *Modern Energy Systems* course at the Aristotle University of Thessaloniki (AUTH), focusing on the **analysis of household electricity consumption data**.

We utilized real-world time series data from residential energy meters and conducted comprehensive analyses using Python to extract insights on consumption behavior, seasonal trends, and correlations with external factors such as **temperature**.

---

## 🛠️ Tools and Technologies

- **Python**
- **Pandas**: data processing and manipulation  
- **Matplotlib & Seaborn**: visualization  
- **NumPy**: normalization and numerical operations  

All analyses and plots are reproducible through the corresponding `.py` scripts included in the repository.

---

## 📂 Structure of the Project

The project is divided into two main analytical sections:

### 1. **Aggregate Household Consumption Analysis**
- **Weekday vs Weekend Consumption**  
- **Seasonal Consumption Patterns**  
- **Hourly Consumption Profiles**  
- **Weekly Trends Over the Year**
- **Correlation Between Consumption and Temperature**
- **Hourly Demand Variation for Extreme/Typical Temperatures**

These analyses aim to uncover:
- Consumption habits during different times of the day and week
- Seasonal electricity usage shifts
- Impact of temperature on energy demand

### 2. **Device-Level Consumption Analysis (for Consumer #5)**
- **Contribution of individual devices to total usage**
- **Changes in usage between weekdays and weekends**
- **Seasonal variation per device**
- **Hourly demand-temperature correlation at device level**

Notable observations include:
- The **electric water heater** is among the highest-consuming appliances
- **TV and oven** usage remains relatively stable year-round
- **Lighting and dishwashing** increase on weekends
- Consumption decreases significantly in warmer seasons

---

## 📁 Files Included

- 📘 `ΣΕΣ_ΑΝΑΦΟΡΑ.pdf`: Full written report in Greek, detailing methodology and results  
- 📂 Python scripts:
  - `2.1...py` to `3.3...py`: Correspond to specific analyses (clearly referenced in the PDF)
- 📊 Dataset: Time series with 15-minute resolution consumption and temperature data  
*(Note: The dataset is required locally – update `file_path` in scripts accordingly.)*
