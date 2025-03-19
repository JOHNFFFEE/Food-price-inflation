# Monthly Food Price Inflation Estimates by Country

## Overview

This project analyzes **monthly food price inflation** across countries over the last two years (2021–2023). Food price inflation is a critical economic indicator that affects poverty, food security, and overall economic stability. By understanding trends in food price inflation, policymakers, researchers, and organizations can make informed decisions to address global food security challenges.

The project involves:

1. **Data Collection**: Gathering monthly food price inflation data from reliable sources like the World Bank, FAO, and national statistical offices.
2. **Data Pipeline**: Building an ETL (Extract, Transform, Load) pipeline to clean, process, and store the data.
3. **Exploratory Data Analysis (EDA)**: Identifying trends, patterns, and correlations in the data.
4. **Visualization**: Creating interactive dashboards and visualizations to communicate insights.
5. **Insights and Recommendations**: Summarizing key findings and suggesting actionable recommendations.

---

## Objectives

- Analyze **monthly food price inflation trends** across countries.
- Identify **countries and regions** most affected by food price inflation.
- Explore **correlations** between food price inflation and other economic indicators (e.g., GDP, unemployment).
- Provide **actionable insights** for policymakers and organizations working on food security.

---

## Data Sources

The project uses data from the following sources:

1. **World Bank Open Data**: [https://data.worldbank.org/](https://data.worldbank.org/)
   - Indicators: Consumer Price Index (CPI), Food Inflation.
2. **FAO (Food and Agriculture Organization)**: [https://www.fao.org/statistics/en/](https://www.fao.org/statistics/en/)
   - Indicators: FAO Food Price Index, country-specific food price data.
3. **International Monetary Fund (IMF)**: [https://www.imf.org/en/Data](https://www.imf.org/en/Data)
   - Indicators: World Economic Outlook (WEO) databases.
4. **National Statistical Offices**:
   - Examples: US Bureau of Labor Statistics, Eurostat, India Ministry of Statistics.

---

## Tools and Technologies

- **Data Ingestion**: Python, APIs, Airflow/Prefect.
- **Data Storage**: AWS S3, Google Cloud Storage, BigQuery, Snowflake.
- **Data Processing**: Pandas, PySpark, SQL.
- **Visualization**: Tableau, Power BI, Streamlit, Plotly.
- **Deployment**: Docker, Kubernetes, AWS/GCP/Azure.
