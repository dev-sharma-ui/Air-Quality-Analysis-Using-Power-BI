Air Quality Analysis Using Power BI

This project presents a comprehensive analysis of multi-year air quality data using Power BI, with a focus on visualizing pollutant trends, seasonal variations, geographic distribution, and overall air quality health based on AQI classification.
The goal of this project is to convert raw environmental data into an interactive, insight-driven dashboard that supports decision-making for pollution monitoring and environmental management.

📌 Project Overview

Air pollution directly affects public health, environmental stability, and policy decisions. This project analyzes pollutant concentrations such as PM2.5, Nitrogen Dioxide (NO₂), and Ozone (O₃) across multiple districts and seasons over several years.

Using Power BI, a fully interactive dashboard was built to uncover:

Temporal trends

Seasonal behavior

Regional pollution hotspots

Pollutant correlations

AQI category distribution

This project demonstrates the full pipeline: data preprocessing → feature engineering → visualization → insight generation.

📂 Repository Structure
├── Air_Quality.csv         # Raw dataset
├── CA2 OF POWER BI.pbix    # Power BI dashboard file
├── Project Report.docx     # Detailed project report (academic format)
└── README.md               # Project documentation

📊 Dashboard Features

The Power BI dashboard includes the following analytical modules:

1. AQI Category Distribution

Classification of pollutant readings into Good, Moderate, Unhealthy, Very Unhealthy, and Hazardous categories.
Helps evaluate overall environmental health.

2. Pollutant Trend Analysis Over Time

Multi-year trend analysis for PM2.5, NO₂, and O₃.
Highlights long-term improvements, deteriorations, and recurring patterns.

3. Seasonal Variation of Pollutants

Comparison of pollutant behavior across Winter, Summer, Spring, and Autumn.
Reveals strong meteorological influence on pollution levels.

4. Geographic Comparison

Region-wise pollutant averages to identify the most polluted districts.
Useful for targeted policymaking and urban planning.

5. Pollutant Correlation Analysis

Correlation heatmap between PM2.5, NO₂, and O₃.
Shows whether pollutants share emission sources or inverse seasonal behavior.

🛠️ Data Preprocessing Summary

Key preprocessing steps performed before visualization:

Removed redundant columns (Unique ID, Indicator ID, Message)

Converted Start_Date to proper date format

Created engineered features:

Year

Month

Season

AQI_Category

Cleaned text fields (trimming, formatting)

Applied correct data types for smooth modeling

Generated pivoted pollutant tables for correlation analysis

📈 Key Insights

NO₂ shows a declining trend over multiple years, reflecting improved emission control.

Ozone peaks during Summer, while PM2.5 and NO₂ rise during Winter, indicating strong seasonal dependency.

Certain districts repeatedly appear as pollution hotspots.

AQI classification shows that while most readings fall under Good/Moderate, periodic Unhealthy spikes persist.

PM2.5 and NO₂ exhibit positive correlation, while O₃ shows partial negative correlation with NO₂.

📘 Tools & Technologies Used

Power BI Desktop – interactive dashboard creation

Power Query Editor – data cleaning and transformation

DAX (Data Analysis Expressions) – measures and calculated columns

Excel / CSV handling – dataset management

📄 Full Project Report

A complete academic-style project report (introduction, methodology, analysis, conclusion, and future scope) is included in:

Project Report.docx

🚀 How to Use This Repository

Download or clone the repository:

git clone https://github.com/dev-sharma-ui/Air-Quality-Analysis-Using-Power-BI.git


Open the .pbix file in Power BI Desktop.

Load /Air_Quality.csv if needed to refresh visuals.

Explore dashboard pages, slicers, and visuals.

🔮 Future Scope

Integrating real-time Air Quality Index APIs

Adding meteorological features (temperature, humidity, wind speed)

Building predictive models to forecast pollutant levels

Enhancing geospatial mapping with longitude/latitude data

Deploying the dashboard on Power BI Service for real-time monitoring

📬 Contact

If you'd like to discuss the dashboard, data modeling steps, or analytical process, feel free to reach out or connect.
