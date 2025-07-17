# Athens Water Reserves & Production Dataset

This repository contains structured, historical data on **daily and annual water reserves, production, and savings** related to the water supply system for **Athens, Greece**. The data is collected via the [OpenWaterAPI](https://data.gov.gr/datasets/open-water-api/) and provided by **EYDAP** (Athens Water Supply and Sewerage Company), curated and updated monthly by the iMEdD team.

### Data Files

- `water_production.csv`  Daily water production data (in cubic meters). 
- `water_prod_by_year.csv`  Annual aggregated water production data. 
- `water_savings.csv`  Daily water savings data (in cubic meters). 
- `water_savings_by_year.csv`  Annual aggregated water savings data. 

> **Note:** Data for all reservoirs begins on **January 1, 1985**, except for the **Evinos reservoir**, which begins on **December 26, 2001**. This first release includes data up to **July 10, 2025**.

---

### Analysis Notebooks

- `water_production-2025.ipynb`  Data cleaning, visualization, and analysis of daily/annual water production. 
- `water_savings-2025.ipynb`  Analysis and plots of water savings over time, including trends and anomalies.
