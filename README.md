# 📊 Audience Behavior Analysis Project (3.7M Records)
**End-to-End Data Analysis: From Python Cleaning to Tableau Dashboards**

## 📝Project Overview
This project analyzes a large-scale viewership dataset containing over **3.7 million records**. The goal was to compare engagement patterns between **Movies** and **Series** and identify peak viewing trends through a structured data workflow.

## 🛠 Project Workflow (Step-by-Step)

### 1. Data Cleaning & Preparation (Python)
* Used **Python** (Pandas/NumPy) to process and clean the 3.7M record dataset.
* Handled missing values and standardized duration metrics into seconds for accurate comparison.
* Optimized the data structure for seamless integration with SQL and Tableau.

### 2. Data Aggregation & Analysis (SQL)
* Developed **SQL queries** to aggregate viewership metrics by "Program Class" and "Program Name".
* Applied **Average Duration Logic** to ensure a fair comparison between content types (e.g., episodic series vs. standalone movies).
* Identified temporal trends by analyzing rating distributions across years and days of the week.

### 3. Interactive Visualization (Tableau)
* Developed a comprehensive **Interactive Dashboard** featuring:
    * **Engagement Comparison:** Movies vs. Series.
    * **Top 10 Programs:** Ranked by average viewer session.
    * **Temporal Trends:** Average ratings by day of the week.
* **Dynamic Interactivity:** Implemented **Action Filters** so that selecting a category (e.g., Series) updates all related charts automatically.

## Key Insights
* **Series Dominance:** Series/Episodes consistently show higher average viewing durations than movies.
* **Peak Engagement:** Viewer activity reaches its highest points on **Wednesdays** and **Weekends**.
* **Normalization Impact:** Using "Average" instead of "Sum" revealed that high-quality content like *Breaking Bad* leads in viewer loyalty, regardless of episode length.

## Project Structure
* `Audience_analysis.twbx`: The interactive Tableau Packaged Workbook.
* `Data_Cleaning.ipynb`: Python scripts for data preparation.
* `Analysis_Queries.sql`: SQL scripts used for data aggregation.
