# Melting Winters, Shifting Seasons: Tracking 50 Years of Climate Change in the UK  
### SAS Curiosity Cup 2025 – 

---

## Project Overview

This project investigates how the UK climate has evolved over the past five decades and forecasts future changes up to 2050. By analyzing historical weather station data (1974–2024) using **SAS Viya, Python, and Excel**, we uncovered long-term trends in **temperature**, **frost days**, **rainfall**, and **sunshine hours**, while applying **SARIMA forecasting** to project these metrics into the future.

The project reveals significant shifts, such as **warmer winters**, **shorter frost seasons**, **earlier spring onset**, and **increased rainfall variability**—key indicators of climate transformation that affect agriculture, biodiversity, infrastructure, and daily life in the UK.

---

## Objectives

- Analyze 50 years of UK historical climate data from Met Office station records
- Conduct deep Exploratory Data Analysis (EDA) and climate trend analysis
- Engineer new climate features (e.g., growing season length, frost events)
- Apply **SARIMA** models to forecast climate variables up to 2050
- Present results with **interactive dashboards** and compelling visuals

---

## Methodology

- **Data Cleaning & Preprocessing:** Removed stations with missing/incomplete records and standardized sunshine sensor transitions (Campbell-Stokes vs Kipp & Zonen)
- **Feature Engineering:** Created features for average temperature, last spring frost, growing season, extreme rainfall, and seasonal indicators
- **Trend Analysis:** Identified warming trends in winters, shifting seasonal boundaries, and rising rainfall intensity
- **Forecasting:** Used **SARIMA** to project future values for max/min temperature, rainfall, sunshine, and frost days
- **Tools Used:** 
  - **SAS Viya for Learners** (Visual Analytics + Time Series Forecasting)
  - **Python** (Data Wrangling, EDA, Visualization)
  - **Excel** (Data exploration, preprocessing)

---

## Key Findings

- **UK winters have warmed** by ~1.5°C since the 1970s, with frost days declining steadily.
- **Spring is arriving ~11 days earlier** now than in 1974, with longer growing seasons (+22 days).
- **Extreme rainfall events have increased**, with more frequent “wet years” since 2000.
- **Forecasts predict** further warming trends, fewer frost days, and longer summers by 2050.
- **Sunshine hours are increasing**, potentially supporting agriculture—but also contributing to drought risks.

---

## Future Enhancements

- Incorporate **crop yield**, **biodiversity**, and **disaster data** to explore real-world impact
- Expand modeling to regional levels using **GIS** and **geospatial clustering**
- Apply **deep learning models** for multivariate time series forecasting
- Enhance interactivity and storytelling in dashboards

---

## How to Use This Repository

Explore our full project report and Jupyter notebook to understand how we analyzed 50 years of UK climate data and forecasted future conditions using statistical modeling and SAS Viya tools. These resources showcase how we used EDA, feature engineering, and SARIMA forecasting to uncover and predict climate trends across the UK.

- [**View Full Project Report**](https://github.com/magarSushant/Climate-Evolution-UK-1974-to-2050-SAS-Curiosity-Cup-2025/blob/main/Curiousity%20Cup_Data%20Ninja_Climate%20change%20UK%20analysis.pdf) – *Curiosity Cup: Climate Change UK Analysis (PDF)*  
- [**Open EDA Jupyter Notebook**](https://github.com/magarSushant/Climate-Evolution-UK-1974-to-2050-SAS-Curiosity-Cup-2025/blob/main/SAS%20Curiosity%20CUP%20EDA.ipynb) – *Python EDA & Climate Trend Analysis*


---

## Data Source & Usage

The dataset used in this project was obtained from the **UK Met Office Historic Station Data**. It was cleaned and prepared by the team for academic and research purposes as part of the Curiosity Cup 2025. Certain features, such as sunshine duration corrections, are based on methodology described in Met Office documentation.

Data Source: [Met Office Historic Station Data](https://www.metoffice.gov.uk/research/climate/maps-and-data/historic-station-data)

---




