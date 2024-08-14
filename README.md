# Air Quality Index (AQI) Prediction

This repository contains code and resources for predicting the Air Quality Index (AQI) using machine learning techniques. The project involves data preprocessing, handling missing values, and applying predictive models to forecast AQI levels based on historical data.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Air Quality Index (AQI) is a critical measure used to communicate how polluted the air currently is or how polluted it is forecast to become. This project aims to predict the AQI using historical air quality data. The model can assist in understanding the factors affecting air quality and help in proactive measures to improve it.

## Dataset

The dataset used in this project contains air quality data, including various pollutant levels and weather conditions. The data was collected from the Narayanganj region and includes the following columns:

- Date
- PM2.5
- PM10
- NO2
- SO2
- CO
- O3
- Temperature
- Humidity
- Wind Speed

Ensure that the dataset is in CSV format and correctly preprocessed before running the model.
## Installation

Make sure you have the following packages:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- missingpy
- fancyimpute

## Usage

1. **Load the Dataset**: Update the file path in the notebook to point to your local dataset.
2. **Preprocess Data**: Handle missing values, outliers, and other preprocessing steps.
3. **Modeling**: Apply machine learning models to predict AQI.

To run the notebook:

```bash
jupyter notebook air_quality_prediction.ipynb
```
## Modeling

The project uses several techniques for imputing missing data and predicting AQI:

- **Imputation**: Missing values are handled using techniques like `IterativeImputer` and `SimpleImputer`.
- **Outlier Detection**: The data is analyzed for outliers using statistical methods.
- **Model Training**: Various models like Linear Regression, Random Forest, etc., are used for AQI prediction.

## Results

The results are displayed using various visualizations, showing the predicted vs. actual AQI values. Model performance metrics like MAE, RMSE, and R² are also provided.

## Contributing

Contributions are welcome! If you have any improvements or suggestions, please open an issue or submit a pull request.
