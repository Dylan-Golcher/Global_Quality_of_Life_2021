# Global Quality of Life Rankings 2021
This project examined the factors that affect global quality of life rankings for the year 2021. Advanced analytical techniques, such as geospatial analysis, supervised machine learning, and unsupervised machine learning, were used to generate insights that were later exported for visualization in a dashboard report.

## Overview
The primary goal of the project was to understand how seven key metrics, Stability, Rights, Health, Safety, Costs, Climate, and Popularity, influenced a total quality of life score and the subsequent rankings by country. The variables were explored first using correlation matrixes to discover which had the most meaningful
relationships with the quality of life score. Next, the variables were visualized on a map using geospatial analysis for visual comparison. Linear regressions analysis was then performed with supervised machine learning, followed by a clustering analysis with unsupervised machine learning. The most important findings of the analyses were visualized in Tableau using plots, charts, and maps.

## Key Questions
The following questions guided the analysis:

1. Which indicators have the highest correlation with quality of life rankings?
2. What insights about quality of life rankings can be revealed by grouping data points using algorithms?
3. What can be learned from analyzing correlations with geospatial data?
4. What can be learned from clusters in geospatial data?


## Analysis Tools
The following programs were used to faciliate the analysis:
- Python with: Pandas, Numpy, Matplotlib, Seaborn, Folium, JSON files, Scikit-Learn, and Statsmodels API
- Anaconda
- Jupyter
- Excel

## Data Sources
The data for this project was open-source and aggregated from several different global organizations:

[Quality of life in a country comparison](https://www.kaggle.com/datasets/shivamsingh0194/quality-of-life-in-a-country-comparison) (data shown is from 2021)

The time series analysis in the scripts section of this repository was not a part of this report. The data for this, however, can be found here:

[Consumer Price Index-Australia](https://data.nasdaq.com/data/RATEINF/CPI_AUS-consumer-price-index-australia)

## Deliverables

[Global Quality of Life Report 2021](https://public.tableau.com/app/profile/dylan.golcher/viz/GlobalQualityofLifeRankings2021/QuallityofLifeProject)
