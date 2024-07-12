# Vehicle CO2 Emissions Prediction

This repository contains code and documentation for predicting CO2 emissions of vehicles in Canada using a Random Forest Regressor. The dataset includes various features such as make, model, vehicle class, engine size, and fuel consumption metrics.


## Introduction

The goal of this project is to develop a machine learning model to predict CO2 emissions from vehicles using features such as engine size, number of cylinders, fuel consumption, and vehicle type. This can help in understanding the factors that influence emissions and aid in developing strategies to reduce them.

## Dataset

The dataset used in this project includes the following features:
- `Make`
- `Model`
- `Vehicle Class`
- `Engine Size(L)`
- `Cylinders`
- `Transmission`
- `Fuel Type`
- `Fuel Consumption City (L/100 km)`
- `Fuel Consumption Hwy (L/100 km)`
- `Fuel Consumption Comb (L/100 km)`
- `Fuel Consumption Comb (mpg)`
- `CO2 Emissions(g/km)`

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the required libraries using the following command:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```bash

## Usage

Clone the repository:

```bash
Copy code
git clone https://github.com/ayomitide96/vehicle-co2-emissions-prediction.git
cd vehicle-co2-emissions-prediction
```bash

## Model Training and Evaluation

The model training involves the following steps

'Data Preprocessing':

Label Encoding for categorical features.
Scaling of numerical features.

'Model Training':

Random Forest Regressor is used as the model.
The dataset is split into training and testing sets.
Model Evaluation:

The model is evaluated using Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE).
Results

The evaluation metrics for the trained model are:

'MAE': 1.80
'MSE': 7.79
'RMSE': 2.79


