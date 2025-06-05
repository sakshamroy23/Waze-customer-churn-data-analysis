# 📊 Waze User Engagement & Retention Analysis

This project analyzes user engagement and retention for the Waze app. It provides insights into user behavior, churn, and usage patterns based on key activity metrics over time.

---

## 🧾 Overview

The notebook explores usage data to answer the following key questions:

- How frequently do users engage with the app?
- What are typical driving behaviors (distance, time, days)?
- What factors correlate with user retention or churn?
- Are there usage trends based on device type?
- How do we handle outliers and data quality?

---

## 📁 Key Metrics Analyzed

- **`total_sessions`** – Total app openings per user
- **`n_days_after_onboarding`** – Days since user onboarding
- **`driven_km_drives`** – Distance driven
- **`duration_minutes_drives`** – Drive duration
- **`activity_days` & `driving_days`** – Frequency of activity
- **Retention by device type**
- **Churn rate based on driving days**
- **Session trends in the most recent month**

---

## 🔧 Tools & Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📈 Analysis Techniques

- Descriptive statistics
- Handling missing values
- Retention curve plotting
- Outlier detection and removal
- Comparative bar plots and histograms

---

## 🧠 Insights

- Users with more driving days tend to stay longer.
- Device type can influence retention.
- Higher session frequency correlates with long-term engagement.
- Outlier removal significantly improves metric reliability.

---
