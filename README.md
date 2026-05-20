# Analysis of road accidents in Madrid (2019–2025)

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Data Analysis](https://img.shields.io/badge/Data-Analysis-green?style=for-the-badge)

## Project description
This project conducts a comprehensive analysis of road traffic accidents recorded by the Municipal Police in the city of Madrid over a six-year period. The aim is to consolidate multiple data sources, clean the data and visualise temporal and geographical patterns of accident rates.

**Dataset:** the analysis is based on open microdata from Madrid City Council, consolidating annual files into a single corpus of **312,980 records**.

## Technologies and libraries
* **Python**: data processing.
* **Pandas**: merging datasets (Merge/Concat) and cleaning.
* **Matplotlib / Seaborn**: generation of time series and bar charts.

## Key points of the analysis

### 1. Consolidation of local Big Data
* **Merging of sources**: integration of 4 separate CSV files (2019 to 2025) into a single master DataFrame.
* **Handling of null values**: identification and management of missing values in critical columns such as `severity`.

### 2. Severity and typology analysis
* **Safety metrics**: classification of accidents by severity (ranging from minor injuries to fatalities).
* **Types of accidents**: analysis of the most common causes (head-on and side-impact collisions, rear-end collisions, pedestrians being hit).

### 3. Temporal patterns
* **Analysis by hour**: identification of ‘peak times’ for accidents (highlighting the increase at 14:00 and between 18:00 and 19:00).
* **Monthly analysis**: comparison of accident rates throughout the year to detect seasonality.

## How to run it?

1. Ensure you have the accident CSV files (2019 to 2025) in the same folder as the notebook.
2. Install the dependencies:
   ```bash
   pip install pandas matplotlib seaborn
   
3. Run the `EDA_Accidentalidad.ipynb` file

## Academic context

This project forms part of the Python for Data Science module, which focuses on the ability to process large volumes of municipal data and transform them into actionable visualisations.

**Developed by:** Alicia Santamaría Román 

**Contact:** https://linkedin.com/in/aliciasantamariaroman


