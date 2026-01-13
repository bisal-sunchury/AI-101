## **Fitbit Data Analytics Project**



#### **Overview:**

This project aims to analyze and visualize Fitbit activity data to uncover personal health and activity insights. The workflow is structured as a complete data analytics pipeline, from raw data ingestion to feature engineering and exploratory analysis. The project demonstrates skills in data wrangling, cleaning, integration, feature engineering, statistical analysis, and visualization.



I took my personal daily activity data from the Fitbit app on my phone to build this project.



#### **Project Pipeline:**



1. Data Ingestion – Reading raw JSON files from Fitbit export.
   
2. Data Validation \& Quality Checks – Ensuring all required metrics are present and valid.
   
3. Data Cleaning \& Normalization – Converting date/time formats, numeric type enforcement, handling missing values.
   
4. Data Integration (Daily Aggregation) – Combining multiple metrics (calories, steps, distance, active minutes) into a unified daily dataframe.
   
5. Feature Engineering –

   Calculated total active minutes (lightly + moderately + very active minutes)

   Computed active/sedentary ratio

   Derived energy \& movement KPI by combining calories, steps, and distance
   
6. Exploratory Data Analysis (EDA) – Identified trends, correlations, and patterns across metrics.
   
7. Analytics Layer – Aggregate KPIs and compute weekly/monthly summaries
   
8. Dashboard Development – Build visual dashboards for interactive exploration of metrics
   
9. Testing \& Verification – Ensure correctness of computed metrics and dashboard interactivity



#### **Key Findings from EDA:**



* Steps \& Calories: Strong positive correlation (~0.82), indicating higher activity directly increases calorie burn.



* Activity Levels \& Sedentary Time: Strong negative correlation (~-0.97), confirming active minutes replace sedentary behavior.



* Daily Active Minutes Impact: Moderate correlation (~0.36) between today’s total active minutes and the next day, suggesting a slight carryover effect.



* Seasonal Patterns: Notable dips in activity and steps observed during July–August 2025.



#### **Work Completed:**



* Raw JSON data ingestion and validation



* Cleaning and normalization of multiple metrics (calories, distance, steps, lightly\_active\_minutes, moderately\_active\_minutes, very\_active\_minutes, sedentary\_minutes)



* Daily data integration and feature engineering



* Exploratory data analysis with correlation and trend insights



#### **Next Steps:**



* Analytics Layer – Aggregate KPIs and compute weekly/monthly summaries



* Dashboard Development – Build visual dashboards for interactive exploration of metrics



* Testing \& Verification – Ensure correctness of computed metrics and dashboard interactivity



