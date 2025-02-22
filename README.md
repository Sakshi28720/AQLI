# Air Quality Life Index (AQLI) Analysis

## Project: Air Pollution and Life Expectancy Analysis

This project systematically examines air pollution levels across various regions and their impact on life expectancy. The **Air Quality Life Index (AQLI)** provides a framework for quantifying the potential years of life lost due to exposure to **particulate matter (PM2.5)** pollution.

---

## Project Overview

This study focuses on processing, analyzing, and visualizing air pollution data spanning **1998 to 2021** using **statistical and geospatial methodologies**. The primary objectives include:

- Identifying **temporal pollution trends** and variations.
- Determining the **most polluted regions** globally over the dataset's timeframe.
- Estimating the **impact of PM2.5 exposure** on life expectancy.
- Benchmarking pollution levels against **World Health Organization (WHO) guidelines**.

This project integrates **quantitative analysis, geospatial assessments, and policy evaluation** to provide actionable insights into pollution control measures.

---

## Data Sources

The analysis utilizes datasets provided by **AQLI**, including:

- **AQLI 1998-2021 GADM2 Dataset (CSV)** – Contains pollution levels at the GADM2 regional level.
- **AQLI 1998-2021 GADM2 Shapefile** – Used for geospatial visualization and mapping.
- **AQLI Data Dictionary** – Provides variable definitions and dataset explanations.

---

## Methodology

The analytical workflow consists of the following phases:

1. **Data Acquisition** – The AQLI 1998-2021 GADM2 dataset is imported, and relevant regional data is extracted for analysis.
2. **Data Cleaning** – The dataset is preprocessed to handle missing values, inconsistencies, and outliers, ensuring data integrity.
3. **Exploratory Data Analysis** – Statistical methods and visualizations are used to identify highly polluted regions and analyze trends.
4. **Geospatial Mapping**: The GADM2 shapefiles are processed to create GIS-based pollution distribution maps, which provide insights into air quality variations.

---

## Tools & Technologies

| **Category**         | **Tools & Frameworks**           |
|----------------------|---------------------------------|
| **Programming**      | Python                     |
| **Data Processing**  | Pandas, NumPy                   |
| **Visualization**    | Matplotlib, Geopandas    |
| **Version Control**  | Git, GitHub                     |
| **GIS & Geospatial Analysis (for future work)** | QGIS, Geopandas, Folium|


This project adopts a **modular, reproducible** approach, ensuring scalability for future analyses.

---

## Key Findings

- **Most Polluted Countries (2021):** Bangladesh, India, and Nepal recorded the highest annual average PM2.5 levels.
- **Consistently Affected Regions (1998-2021):** Delhi, India, remained among the most polluted urban areas.
- **Life Expectancy Impact:** Exposure reduction to WHO-recommended levels could lead to significant gains in life expectancy.
- **Policy and Regulatory Challenges:** Enforcing air quality standards remains a major challenge, particularly in South Asia, due to urbanization, industrial emissions, and inadequate regulatory frameworks.

---

## Output Files

Processed datasets, analytical results, visualizations, and comprehensive reports are stored in the [`Output`](https://github.com/Assignment/Output) directory.

Key deliverables include:

- **Processed CSV Files** – Cleaned and structured datasets.
- **Visual Reports** – Statistical charts, GIS maps, and trend visualizations.
- **Geospatial Analysis Files** – Shapefiles and interactive maps.
- **Technical Documentation** – Methodology reports and analytical scripts.

---

## Acknowledgments

This project is based on publicly available data from:

- **Air Quality Life Index (AQLI)**
- **Energy Policy Institute at the University of Chicago (EPIC)**

If you would like more information, please visit the **[AQLI official website](https://aqli.epic.uchicago.edu/)**.
