# air-quality-analysis-python
# Air Quality Data Analysis using Python

## Project Overview

This project focuses on **cleaning, analyzing, and visualizing air quality data** to understand pollution trends across different cities and states.

It demonstrates an **end-to-end data analysis workflow**:

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Visualization
* Insight Generation

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dataset Features

The dataset includes:

* Country, State, City, Station
* Pollutant Types (PM2.5, PM10)
* Pollution Levels (Min, Max, Avg)
* Latitude & Longitude
* Timestamp (Last Update)

---

## Data Cleaning Steps

* Removed missing and invalid values
* Converted `'NA'` → `NaN`
* Fixed data types (numeric + datetime)
* Trimmed whitespace in text columns

---

## Feature Engineering

* Extracted: Year, Month, Day, Hour
* Created `pollutant_range`
* Categorized pollution levels (Good → Severe)

---

## Exploratory Data Analysis

* Pollutant distribution analysis
* Top polluted cities (PM2.5)
* State-wise pollution comparison
* Unique counts (cities, stations, pollutants)

---

## Visualizations

### Pollution Distribution

* Bar charts for pollutant frequency
* Average pollution levels

### State-Level Analysis

* Top 10 polluted states

### Pollution Categories

* Pie chart for PM2.5 categories

### Geographic Analysis

* Scatter plot using latitude & longitude
* Color-coded pollution intensity

---

## Output Files

* `air_quality_cleaned.csv` → cleaned dataset
* `air_quality_analysis.png` → visual insights
* `geographic_distribution.png` → geo visualization

---

## Future Enhancements (Predictive Analysis)

* Time series forecasting (ARIMA / Prophet)
* Pollution prediction using ML models
* Dashboard creation using Power BI

---

## Key Learnings

* Handling real-world messy data
* Data preprocessing techniques
* Feature engineering for analysis
* Data visualization & storytelling

---

## How to Run

```bash
pip install pandas numpy matplotlib seaborn
python air_quality_analysis.py
```



Give this repo a ⭐ and connect with me on LinkedIn!

