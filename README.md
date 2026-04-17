# 🌡️ Atmospheric Thermal Variability in the Dominican Republic: A Retrospective Analysis (2000-2024)

## 🔬 Abstract
This scientific research aims to quantify and analyze the evolution of atmospheric temperatures in the Dominican Republic during the first quarter of the 21st century. Through a longitudinal analysis of time-series data, the study identifies warming trends, thermal anomalies, and the magnitude of climate change at a regional level, providing rigorous empirical evidence of meteorological alterations within the national territory.

## 🛠️ Tech Stack & Methodology
To ensure reproducibility and statistical rigor, data processing and visualization are executed within a data science-oriented environment:

* **Language:** Python
* **Data Manipulation & Cleaning:** Parsing and cleaning structured CSV datasets from NOAA. Manual yearly aggregation of daily observations. Handling of missing-data and invalid entries. Computation of annual temperature averages.
* **Scientific Visualization:** Matplotlib
* **Key Libraries:** matplotlib.pyplot, pathlib, csv, datetime

## 📂 Repository Structure
```text
📦 DR-Climate-Analysis-2024
 ┣ 📂 data/               # Raw (NOAA) and processed datasets (CSV)
 ┣ 📂 images/             # Graphic resources
 ┣ 📂 notebooks/          # Jupyter Notebooks containing experimentation and plots
 ┣ 📂 docs/               # Supplemental documentation and Compiled document with findings and conclusions
 ┣ 📜 requirements.txt    # Python environment dependencies
 ┗ 📜 README.md           # This file