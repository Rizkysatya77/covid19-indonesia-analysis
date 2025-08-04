# COVID-19 Analysis and Forecasting in Indonesia

This project presents a comprehensive analysis and forecasting of COVID-19 data in Indonesia using Python. The project involves exploratory data analysis (EDA), time series forecasting of daily cases, deaths, and recoveries, prediction of key epidemiological metrics (Case Fatality Rate and Case Recovered Rate), and classification of COVID-19 risk zones.

## 📌 Project Structure

```
covid19-indonesia-analysis/
|
├── data/
│   ├── covid_19_indonesia_time_series_all.csv          # Main dataset
│   └── indonesia_province_map.geojson                 # GeoJSON map file for visualization
│
├── notebooks/
│   ├── Portofolio_EDA_Covid-19_in_Indonesia.ipynb     # EDA and visual exploration
│   ├── Model_Prediction_Total_Cases_Deaths_Recovered_Daily.ipynb  # Time series prediction
│   ├── Prediction_Case_Recovered_Rate_and_Case_Fatality_Rate.ipynb  # CFR & CRR modeling
│   └── Zone_Risks_Classification.ipynb                # Zone classification based on risk level
│
├── requirements.txt                                   # Python dependencies
├── README.md                                           # Project overview
└── .gitignore
```

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on COVID-19 data in Indonesia.
- Predict daily COVID-19 cases, deaths, and recoveries using time-series forecasting.
- Estimate epidemiological rates like CFR (Case Fatality Rate) and CRR (Case Recovered Rate).
- Classify provincial risk zones using classification models based on relevant features.

## 🔍 Tools and Technologies

- **Language**: Python 3.x
- **Libraries**: pandas, numpy, matplotlib, seaborn, plotly, scikit-learn, xgboost, statsmodels, geopandas
- **Visualization**: GeoJSON mapping, time series charts, correlation heatmaps
- **Modeling**: Linear Regression, Random Forest, MLP, SVR, GradientBoosting, XGBoost

## 📈 Key Features

- **EDA & Visualization**:
  - Daily, weekly, and monthly case trends
  - 7-day moving averages
  - Geographic visualization of provincial cases
- **Prediction Models**:
  - Forecast Total Cases, Deaths, and Recovered using lag features and regression models
  - Calculate predicted CFR and CRR using predicted values
- **Zone Classification**:
  - Classify risk zones based on defined thresholds
  - Apply classification algorithms to map high-risk vs low-risk areas

## 📊 Sample Visualizations

- Heatmaps of correlation between features
- Scatter map of top-affected provinces
- Forecast curves for each predicted component

## 🚀 Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Rizkysatya77/covid19-indonesia-analysis.git
cd covid19-indonesia-analysis
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebooks:

```bash
jupyter notebook notebooks/Portofolio_EDA_Covid-19_in_Indonesia.ipynb
```

## 📂 Data Source

- [Kaggle Dataset (covid\_19\_indonesia\_time\_series\_all.csv)](https://www.kaggle.com/datasets/)
- GeoJSON file for Indonesian provinces from public sources or custom built

## 📄 License

This project is open source and available under the MIT License.


