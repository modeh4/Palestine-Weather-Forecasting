# Palestine Weather Forecasting

This repository contains the code and notebooks for multi-variable weather forecasting using meteorological data from Palestine.

## Project Overview

This study compares statistical, classical machine learning, and deep learning models for multi-station weather forecasting. The dataset contains daily observations from five weather stations in Palestine between 2015 and 2025.

## Forecasting Models

The evaluated models include:

- Persistence baseline
- ARIMA
- SARIMA
- Random Forest
- XGBoost
- CNN
- LSTM
- GRU
- ConvLSTM
- CNN-GRU
- CNN-LSTM with station embedding

## Dataset

The main dataset used for the experiments is:


data/final_filled_climate_cleaned.xlsx

The dataset includes the following variables:
	•	Temperature
	•	Relative Humidity
	•	Wind Speed
	•	Rainfall
	•	Atmospheric Pressure
	•	Sunshine Duration
	•	Station ID
	•	Date
Feature Engineering
The models use:
	•	30-day historical sequences
	•	Temporal features: Month, Week, DayOfWeek
	•	Station encoding / station embedding
	•	Chronological train-validation-test split
Evaluation Metrics
The models are evaluated using:
	•	Mean Absolute Error (MAE)
	•	Mean Squared Error (MSE)
	•	Root Mean Squared Error (RMSE)
	•	Coefficient of Determination (R²)
Installation
Option 1: Using pip

pip install -r requirements.txt

Option 2: Using Conda

conda env create -f environment.yml
conda activate palestine_weather_forecasting

How to Run
Run the notebooks in the following order:

notebooks/01_preprocessing.ipynb
notebooks/02_statistical_models.ipynb
notebooks/03_machine_learning_models.ipynb
notebooks/04_deep_learning_models.ipynb
notebooks/05_evaluation.ipynb

Reproducibility Notice
Deep learning models may show small run-to-run variations due to random weight initialization, optimization dynamics, hardware differences, and software versions. The overall trends and conclusions remain consistent.
Data Availability
The meteorological dataset was obtained from the Palestinian Meteorological Authority. If redistribution is restricted, only the cleaned dataset or sample data should be included, and access to the full dataset should be requested from the data provider.
Repository Structure

Weather-Palestine-Forecasting/
│
├── data/
├── notebooks/
├── src/
├── figures/
├── results/
├── docs/
├── README.md
├── requirements.txt
├── environment.yml
└── LICENSE

Citation
If you use this repository, please cite the associated research article.


Also create a second file inside `data/` named `README.md`:

```md
# Dataset Information

This folder contains the dataset used for the weather forecasting experiments.

## File

```text
final_filled_climate_cleaned.xlsx

Description
The dataset contains daily meteorological observations collected from five weather stations in Palestine between 2015 and 2025.
Variables
	•	Station
	•	Date
	•	Temperature
	•	Relative Humidity
	•	Wind Speed
	•	Rainfall
	•	Atmospheric Pressure
	•	Sunshine Duration
Preprocessing
The dataset was cleaned before model training. The preprocessing steps included:
	•	Date standardization
	•	Missing-value handling
	•	Pressure zero correction
	•	Sunshine correction for unavailable station records
	•	Temporal feature extraction
	•	Station encoding
	•	Chronological train-validation-test split

