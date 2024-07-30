# Temperature Prediction by Time Series

This repository contains a project for predicting temperature using time series analysis. The project is implemented using Python and uses real temperature data stored in a CSV file.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project aims to predict future temperatures based on historical temperature data using time series analysis techniques. Time series analysis is a powerful tool for forecasting data points in the future by analyzing the trends and patterns in historical data.

## Dataset

The dataset used in this project contains historical temperature data. The data is stored in a CSV file named `temperature_data.csv`. Each row in the CSV file represents a temperature observation at a specific time.

## Dependencies

To run this project, you need to have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- statsmodels

You can install these dependencies using the following command:

```bash
pip install pandas numpy matplotlib scikit-learn statsmodels


##Usage
1. Clone this repository: git clone https://github.com/alexuuhat/Temperature-Prediction-by-Time-Series.git
2. cd Temperature-Prediction-by-Time-Series
3. Place your temperature data CSV file (temperature_data.csv) in the root directory of the project.
4. Run the main script to perform temperature prediction: python main.py

#Project Structure
Temperature-Prediction-by-Time-Series/
│
├── data/
│   └── temperature_data.csv        # The dataset used for training and prediction
│
├── notebooks/
│   └── EDA.ipynb                   # Jupyter notebook for exploratory data analysis
│   └── ModelTraining.ipynb         # Jupyter notebook for model training and evaluation
│
├── src/
│   ├── data_preprocessing.py       # Data preprocessing functions
│   ├── model_training.py           # Functions for training the model
│   ├── prediction.py               # Functions for making predictions
│
├── main.py                         # Main script to run the prediction
├── requirements.txt                # List of dependencies
└── README.md                       # Project README

##Results
The results of the temperature prediction will be displayed in the console and plotted using Matplotlib. The model's performance will also be evaluated using appropriate metrics.

##Contributing
Contributions are welcome! If you have any suggestions or improvements, please create an issue or submit a pull request.
