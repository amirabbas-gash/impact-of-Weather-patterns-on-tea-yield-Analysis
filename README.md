# The Impact of Weather Patterns on Annual Fluctuations in Tea Yield in Northern Iran (1961–2023)

## Overview

This study investigates the relationship between large-scale atmospheric patterns and interannual tea yield variability in northern Iran using **ERA5 climate reanalysis data and machine learning**.

Focusing on the tea-growing regions of Gilan and Mazandaran, the study combines weather pattern classification, statistical analysis, and predictive modeling to identify atmospheric conditions associated with favorable and unfavorable tea yields.

## Methodology

- **Climate data:** ERA5 reanalysis data for the April–October growing season (1961–2023).
- **Yield data:** FAOSTAT annual tea production and yield statistics.
- **Weather pattern classification:** MiniBatch K-Means clustering to identify 30 distinct weather patterns.
- **Statistical analysis:** Spearman correlation and analysis of weather pattern frequency across yield categories.
- **Predictive modeling:** Regression and classification models, including SVR, Random Forest, SVM, Decision Trees, and KNN.
- **Climate indicator:** Development of a composite Weather Pattern Index (WP Index).

## Key Findings

- Identified weather patterns associated with higher and lower tea yields.
- Developed a WP Index to quantify the balance between favorable and unfavorable atmospheric conditions.
- Achieved a mean classification accuracy of **61.9%** using Support Vector Machine (SVM).
- Identified near-surface air temperature and dew point temperature as influential predictors of tea yield.
- Demonstrated the potential of weather-pattern-based modeling for climate-informed agricultural planning.

## Technologies

`Python` · `Machine Learning` · `Scikit-learn` · `ERA5` · `Climate Data Analysis` · `Time Series Analysis`

## Authors

- **M. Molavi-Arabshahi** — Corresponding Author
- **E. Shahabinezhad**
- **A. A. Gashtil**
- **R. Iranshahi**

## Data Sources

- [Copernicus Climate Data Store — ERA5](https://cds.climate.copernicus.eu/)
- [FAOSTAT — Food and Agriculture Organization of the United Nations](https://www.fao.org/faostat/)

---

*This repository documents the research framework for investigating climate-driven tea yield variability and supporting climate-resilient agricultural decision-making.*
