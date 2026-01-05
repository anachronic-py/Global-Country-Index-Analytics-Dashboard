Project Title: End-to-End Global Analytics Pipeline: From Raw Kaggle Data to Interactive Power BI Insights
Project Overview
This project demonstrates a complete data lifecycle. I transformed a raw, "noisy" global dataset into a high-performance interactive dashboard. The project specifically solves the challenge of maintaining global context (Top 5 comparison) while allowing for granular, country-specific exploration.

Technical Workflow
1. Data Sourcing (Kaggle)
Extracted a comprehensive dataset containing diverse global indicators including GDP per Capita, Population, and Ecological Footprints.

2. Data Audit (Excel)
Performed an initial inspection to identify data quality issues.

Discovery: Identified "dirty" data in the quality metrics where numerical values were appended with random characters (e.g., 3B, 3L, 3T), which would have corrupted any ranking or aggregation logic.

3. ETL & Transformation (Power Query)
Used Power Query to automate the cleaning of alphanumeric strings.

Converted data types to ensure all indices were recognized as numerical values, enabling accurate sorting for the "Top 5" visuals.

4. Dashboard Architecture (Power BI)
Dynamic Slicers: Integrated a country-level slicer that updates Map visuals and KPI cards (e.g., Denmark at $61,413.60 GDP per Capita).

Fixed Benchmarking: Implemented Edit Interactions to "freeze" the Top 5 Population chart (China, India, USA, etc.).

Result: This allows a user to look at a specific country like El Salvador while immediately seeing how it compares to the world's most populous nations.

Key Metrics Tracked
Social: Population (millions), HDI (Human Development Index).

Economic: GDP per Capita.

Environmental: Carbon Footprint, Forest Land, and Biocapacity.

Tools Used
Excel: Data Auditing.

Power Query: ETL & Data Cleaning.

Power BI: Data Modeling & Visualization.
