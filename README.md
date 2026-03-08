# NYC Airbnb Insights

Exploratory data analysis, time series forecasting, and regression modelling on New York City Airbnb listings to uncover pricing patterns and booking demand trends.

## Dataset

- **Source:** [Kaggle — NYC Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data)
- **File:** AB_NYC_2019.csv
- **Records:** 48,895 listings
- **Features:** 16 columns
- **Scope:** New York City (5 boroughs), Year 2019

## What This Project Covers

- **Data Cleaning** — Handling missing values, removing outliers using IQR, dropping invalid listings
- **Exploratory Data Analysis** — Descriptive statistics, price distributions, borough comparisons, correlation heatmap, geographic scatter plot
- **Hypothesis Testing** — Welch's t-test comparing Manhattan vs Brooklyn listing prices
- **Time Series Forecasting** — Holt-Winters Exponential Smoothing to predict monthly booking demand
- **Regression Modelling** — Linear Regression and Random Forest to predict listing prices
- **Model Evaluation** — MAE, RMSE, R², MAPE metrics across all models

## Key Findings

- Manhattan listings average **$150/night** — significantly higher than Brooklyn ($90) confirmed by t-test (p < 0.0001)
- **Entire home/apartment** listings command the highest prices across all boroughs
- Booking demand **peaks every June–August** — investors should maximise availability in summer
- **Random Forest** outperforms Linear Regression with R² of 0.58 vs 0.18
- **Location (lat/lon)** accounts for 61% of feature importance in price prediction

## Tools & Libraries

| Tool | Purpose |
|------|---------|
| Python | Core language |
| Pandas & NumPy | Data manipulation |
| Matplotlib & Seaborn | Data visualisation |
| Scikit-learn | Regression modelling |
| Statsmodels | Time series forecasting |
| SciPy | Hypothesis testing |
| Google Colab | Development environment |

## How to Run

1. Clone the repository
```bash
   git clone https://github.com/YOUR_USERNAME/nyc-airbnb-insights.git
```
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) and place `AB_NYC_2019.csv` in the project folder
3. Open `nyc_airbnb_insights.ipynb` in Google Colab or Jupyter Notebook
4. Run all cells

## Project Structure
```
nyc-airbnb-insights/
│
├── nyc_airbnb_insights.ipynb   # Main analysis notebook
├── AB_NYC_2019.csv             # Dataset (download from Kaggle)
└── README.md                   # Project documentation
```
##
<p align="center"><i>All rights reserved © DilshanKodithuwakku.</i></p>