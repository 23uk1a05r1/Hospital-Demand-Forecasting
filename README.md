# Hospital Demand Forecasting Using Time-Series Analysis

## 1. Project Overview

The Hospital Demand Forecasting project uses Python and time-series forecasting techniques to analyze historical hospital demand and predict future patient visits and admissions.

The main goal is to help hospitals improve resource planning, including staffing, bed availability, and healthcare service management.

## 2. Project Objectives

- Analyze historical hospital patient records.
- Perform data cleaning and preprocessing.
- Explore patient demand patterns using data visualization.
- Analyze weekly hospital demand trends.
- Build and compare multiple time-series forecasting models.
- Forecast hospital demand for the next 13 weeks.
- Estimate hospital bed requirements.

## 3. Dataset Description

This project uses a synthetically generated dataset containing approximately 500,000 hospital visit records from January 2023 to October 2026.

The dataset represents four fictional hospitals in Pune.

Important features include:
- Hospital
- Visit date
- Department
- Visit type
- Patient age
- Laboratory tests
- Billing amount
- Diagnosis code
- Length of stay
- Discharge date

**Note:** The dataset is synthetic and does not contain actual patient records.

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- Prophet
- Jupyter Notebook

## 5. Project Workflow

1. Environment setup and library installation
2. Synthetic hospital data generation
3. Data cleaning and preprocessing
4. Exploratory Data Analysis (EDA)
5. Weekly demand aggregation
6. Time-series analysis
7. Baseline forecasting models
8. Advanced forecasting models
9. Prophet forecasting
10. Model validation and evaluation
11. Business insights and recommendations

## 6. Forecasting Models

The following models were implemented and compared:

- Naive Forecasting
- Seasonal Naive Forecasting
- ARIMA
- SARIMA
- Prophet

## 7. Model Evaluation

The models were evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Percentage Error (MAPE)

### Model Comparison Results

| Model | MAE | RMSE | MAPE |
|---|---:|---:|---:|
| Prophet | 19.95 | 25.56 | 3.53% |
| SARIMA | 23.50 | 28.56 | 4.19% |
| Seasonal Naive | 39.13 | 46.56 | 6.59% |
| Naive | 49.33 | 54.57 | 8.90% |
| ARIMA | 52.32 | 59.34 | 9.42% |

Prophet achieved the best average performance among the five evaluated models.

## 8. Final Results

The selected Prophet model was used to generate 13-week forecasts for four hospitals across:

- Total patient visits
- Outpatient department (OPD) visits
- Hospital admissions

The project also estimated bed requirements using forecasted admissions and historical average length of stay.

## 9. Business Applications

The forecasts can demonstrate how hospitals may:

- Plan staffing requirements.
- Manage bed availability.
- Allocate medical resources.
- Anticipate patient demand.
- Improve operational planning.

## 10. Project Limitations

- The dataset is synthetically generated.
- The results are illustrative rather than real-world hospital predictions.
- Only four fictional hospitals are included.
- Bed requirements are approximate estimates.

## 11. Conclusion

This project demonstrates the application of Python, data analysis, and time-series forecasting to hospital demand planning. It provides practical experience in data preprocessing, exploratory analysis, forecasting model development, model evaluation, and business interpretation.

## 12. Author

Developed as a Hospital Demand Forecasting project using Python and time-series analysis.
