# Wildfire & Climate Anomaly Analysis (2000–2023)

Computational analysis of wildfire activity and climate anomalies across western U.S. states using Python-based statistical visualization and environmental datasets.

---

## Overview

This project explores the relationship between climate anomalies and wildfire activity in California, Arizona, and Oregon between 2000 and 2023. Using historical wildfire and NOAA climate datasets, the analysis investigates whether increasing temperatures and changing precipitation patterns are associated with changes in wildfire frequency over time.

The project combines environmental data analysis, visualization, and statistical methods to examine how climate variability may influence wildfire behavior.

---

## Research Question

How are temperature and precipitation anomalies related to wildfire frequency in western U.S. states?

---

## Datasets

- National Interagency Fire Center (NIFC) wildfire data
- NOAA climate anomaly datasets
  - Temperature anomalies
  - Precipitation anomalies

States analyzed:
- California
- Arizona
- Oregon

---

## Methods

- Cleaned and organized multi-source environmental datasets
- Combined yearly wildfire counts with annual climate anomaly data
- Visualized wildfire and climate trends over time
- Performed correlation analysis between wildfire frequency and climate variables
- Generated boxplots and heatmaps to compare climate variability across states

---

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Key Findings

- Wildfire counts did not consistently increase alongside rising temperatures.
- Temperature anomalies generally increased over time across all three states.
- California showed the greatest variability in temperature and precipitation anomalies.
- Correlations between wildfire frequency and climate variables were relatively weak, suggesting wildfire activity is influenced by multiple interacting environmental and human factors.

This project highlights the complexity of wildfire systems and demonstrates that climate variables alone may not fully explain wildfire behavior.

---

## Future Improvements

Potential next steps include:
- Analyzing acres burned instead of wildfire counts
- Incorporating wildfire severity metrics
- Applying machine learning models for prediction
- Comparing human-caused vs. natural wildfires
- Expanding analysis to additional states or regions

---

## Repository Structure

wildfire-climate-analysis/
│
 - wildfire_anomalies.ipynb
 - README.md
 - writeup
 - data/
 - presentation/


---

## How to Run

Install required libraries:

pip install pandas numpy matplotlib seaborn

Run the notebook:

jupyter notebook wildfire_anomalies.ipynb

---

## Presentation

This project was presented as a 12-minute environmental data analysis presentation focused on climate variability and wildfire trends in the western United States.
