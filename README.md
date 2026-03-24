# Strategic Audience Engagement & Churn Analysis (3.7M Records)
**High-Scale Data Analysis: From Python Pipelines to Tableau Insights**

## Executive Summary
This project analyzes a massive dataset of **3.7 million records** to understand viewership patterns and "Content Churn" (programs users start but don't finish). By leveraging **Python** for heavy-duty data cleaning and **Tableau** for interactive BI, I identified key engagement drivers across Movies and Series.

## Technical Workflow (Python-Driven)
* **High-Scale Data Cleaning:** Used **Python (Pandas/NumPy)** to process 3.7M+ records, optimizing memory and handling missing data/formatting durations.
* **Churn Analysis (High Churn):** Developed logic to identify content with low completion rates (e.g., *Rebel in the Rye*, *Bad Teacher*) to provide strategic recommendations.
* **Data Aggregation:** Calculated **Average Viewing Durations** to ensure a fair comparison between episodic series and standalone movies.
* **BI Integration:** Engineered the final dataset and exported it via `to_csv()` for seamless visualization in **Tableau**.

## Strategic Insights
* **Engagement Leader:** Series/Episodes consistently outperform Movies in average session duration.
* **Top Performers:** Analysis shows high loyalty for programs like *The Social Network* and *Coco* based on completion and rating metrics.
* **Peak Windows:** Audience activity and ratings reach their highest points on **Wednesdays** and **Weekends**.
* **Actionable Advice:** Identifying "High Churn" content allows platforms to optimize their library and marketing strategies.

## Interactive Dashboard (Tableau)
* **Dynamic Filtering:** Implemented **Action Filters** to allow stakeholders to toggle between Series and Movies instantly.
* **Trend Analysis:** Visualized rating distributions across the week to identify prime time slots.

## Project Structure
* `stc_analysis.ipynb`: Full Python Notebook (Cleaning, Churn Analysis, Export).
* `Audience_analysis.twbx`: Interactive Tableau Packaged Workbook.

