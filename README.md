#  FitBit Fitness Tracker Data Analysis

A comprehensive analysis of user activity data from FitBit fitness trackers to uncover behavioral trends, daily activity levels, and calorie-burning patterns.

---

##  Project Overview

This project focuses on analyzing daily activity data collected from 33 FitBit users, including steps taken, minutes spent in different activity levels, calories burned, and more. The goal is to extract meaningful insights about user behavior, daily patterns, and health-related metrics using Python and data visualization techniques.

- **Dataset**: [FitBit Fitness Tracker Data](https://www.kaggle.com/code/nadaemad2002/fitbit-fitness-tracker-data)
- **Tools Used**: Python, pandas, matplotlib, seaborn, plotly

---

##  Data Cleaning & Preprocessing

- Selected relevant features such as total steps, activity minutes, sedentary minutes, and calories.
- Removed null values and duplicates.
- Converted `ActivityDate` to datetime format.
- Created new columns: `TotalMinutes`, `TotalHours`, and `DayOfWeek`.

---

##  Exploratory Data Analysis (EDA)

- Users spent the most time in **sedentary activity**, followed by **light**, **fair**, and **very active minutes**.
- **Calories burned** had a positive correlation with both **total steps** and **activity duration**.
- Most activity occurred on weekdays, with noticeable drops on weekends.
- Weekdays like **Tuesday and Wednesday** had higher step counts and calorie burn.
- Created insightful plots:
  - **Day of week activity frequency**
  - **Steps vs. Calories** scatter plot with medians
  - **Total activity hours vs. Calories** scatter plot
  - **Pie chart** showing activity type distribution

---

##  Key Findings

- Most users burned the highest number of calories on days when total steps and active minutes were above median values.
- **24 hours of total activity** (including sedentary) is consistently recorded, showing data completeness.
- Activity levels and calorie expenditure showed **clear behavioral patterns across days of the week**.
- Majority of users were highly sedentary (visualized in the pie chart breakdown).

---

##  Files Included

- `FitBit_Fitness_Tracker_Data.ipynb`: Full Jupyter Notebook with data loading, cleaning, visualizations, and insights.

---

##  Resume Summary

> Analyzed fitness tracker data from 33 users to uncover trends in activity levels, step counts, and calorie expenditure. Visualized correlations and daily patterns using Python libraries such as pandas, matplotlib, seaborn, and plotly.

---

##  Credits

Dataset: [FitBit Tracker Data on Kaggle](https://www.kaggle.com/code/nadaemad2002/fitbit-fitness-tracker-data)

---
