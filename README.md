# Rainfall Prediction Classifier

This project builds a machine learning model to predict whether it will rain tomorrow based on historical weather data from the Australian Bureau of Meteorology. The data includes daily weather observations like temperature, humidity, wind, and pressure.

## Dataset

* Source: [Bureau of Meteorology](http://www.bom.gov.au/climate/dwo/)
* Kaggle: [Weather Dataset - Rattle Package](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)
* Target Variable: `RainTomorrow` (Yes/No)

## Workflow

* Data cleaning and handling missing values
* Feature encoding and scaling
* Model training using Logistic Regression, Random Forest, and XGBoost
* Evaluation using Accuracy and ROC-AUC metrics

## Results (Approximate)

| Model               | Accuracy | ROC-AUC |
| ------------------- | -------- | ------- |
| Logistic Regression | \~83%    | \~0.84  |
| Random Forest       | \~85%    | \~0.87  |
| XGBoost Classifier  | \~86%    | \~0.88  |

## Tools & Libraries

* Python, Pandas, NumPy
* scikit-learn, XGBoost
* Matplotlib, Seaborn
