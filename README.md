# 🌡️ Annual Temperature Trends Analysis in Barahona (2000–2020)

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)

## 📌 Project Description
Exploratory analysis of historical temperature observations recorded in Barahona, Dominican Republic. This project implements a reproducible workflow to process and aggregate daily meteorological data from NOAA into annual trends (TMAX, TMIN, TAVG).

Detailed findings, statistical discussions, and final visualizations are documented in the accompanying LaTeX report included in this repository.

## ⚙️ Tech Stack & Methodology
This project demonstrates the implementation of a structured data-processing pipeline using:

* **Language:** Python
* **Environment:** Jupyter Notebook, Visual Studio Code
* **Key Libraries:** `matplotlib.pyplot`, `pathlib`, `csv`
* **Core Logic:** * Parsing and cleaning structured CSV datasets from NOAA.
    * Manual yearly aggregation of daily observations.
    * Handling of missing-data and invalid entries.
    * Computation of annual temperature averages.

## ⚠️ Study Limitations
* **Local Scope:** Data corresponds to a single meteorological station; results reflect local trends only.
* **Data Integrity:** Presence of missing observations and incomplete records in specific years.
* **Timeframe:** Dataset is limited to the 2000–2020 period.
* **Nature of Study:** This is an exploratory technical implementation, not a definitive climatological assessment.

## 📂 Repository Structure
* `data/`: Original CSV files from NOAA Climate Data Online.
* `/climate-data-project.ipynb`: Jupyter Notebook with the data processing and visualization logic.
* `report/`: Full analysis, graphs, and conclusions in LaTeX format.

## 🚀 Future Scope
* Implementation of interactive dashboards (Streamlit/Plotly).
* Integration of statistical trend significance testing.
* Expansion to include multiple meteorological stations across the Dominican Republic.

---
*Data Source: [National Oceanic and Atmospheric Administration (NOAA)](https://www.ncdc.noaa.gov/cdo-web/search)*