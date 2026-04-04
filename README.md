# Bellabeat Data Analysis Case Study

## Project Overview
This repository contains my Capstone Project for the **Google Data Analytics Professional Certificate**. The analysis focuses on **Bellabeat**, a high-tech manufacturer of health-focused products for women. 

The goal was to analyze smart device usage data (FitBit) to identify consumer trends and provide data-driven marketing recommendations to the Bellabeat executive team using a strictly programmatic approach.

## Tech Stack
* **Language:** Python 3.x
* **Libraries:** * **Pandas:** Data manipulation, cleaning, and merging.
    * **NumPy:** Mathematical operations and array handling.
    * **Seaborn & Matplotlib:** Statistical data visualization and exploratory plotting.

## Dataset Information
* **Source:** [FitBit Fitness Tracker Data](https://www.kaggle.com/datasets/arashnic/fitbit) (CC0: Public Domain)
* **Scope:** 31 days of wellness data (activity, calories, sleep) from 30+ users.
* **Key Findings:**
    * **Correlation:** Discovered a **0.41 moderate positive correlation** between daily steps and sleep quality.
    * **Sedentary Trends:** Identified that users spend an average of **16 hours (over 80%)** of their day in a sedentary state.
    * **Data Integrity:** Uncovered a significant tracking gap (530 days of activity data missing corresponding sleep logs), suggesting a barrier to 24/7 wearable usage.

## The Analytical Process
1. **Ask:** Defined the business task: How do non-Bellabeat users engage with smart devices?
2. **Prepare:** Validated data using the ROCCC framework and handled 18 separate CSV files.
3. **Process:** * Cleaned date-time objects for time-series analysis.
    * Merged activity and sleep datasets into a unified "Golden Table" using inner joins to ensure data consistency.
4. **Analyze:** Conducted descriptive statistics and grouped users into activity-based personas.
5. **Share:** Produced high-fidelity statistical visualizations using **Seaborn** to communicate trends to stakeholders.
6. **Act:** Developed 3 core marketing recommendations focused on "Active Breaks" and "Weekend Engagement."

## Key Visualizations (Seaborn)
The notebook includes several automated visualizations:
* **Regression Plots:** Visualizing the relationship between Total Steps and Calories.
* **Activity Breakdowns:** Pie charts illustrating the ratio of Sedentary vs. Active minutes.
* **Weekly Trends:** Categorical bar plots showing the "Weekend Slump" in user activity.

## 🔗 Links
* **Full Python Notebook:** https://www.kaggle.com/code/rachelmifor/bella-beats-competitor-analysis

---
**Support:**
This project was made possible through a learning opportunity funded by **She Code Africa** in partnership with **Grow with Google** and **Coursera**.
