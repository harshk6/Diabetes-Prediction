# Diabetes Prediction Project

This project is centered around predicting the likelihood of diabetes in patients based on various health metrics. The project utilizes machine learning techniques and is implemented in a Jupyter notebook (`Diabetes_Prediction.ipynb`).

## Table of Contents
- [Overview](#overview)
- [Dataset](#dataset)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)

## Overview
The goal of this project is to predict whether a patient has diabetes based on several medical attributes such as glucose level, BMI, age, etc. The notebook walks through the data analysis, feature selection, model training, and evaluation processes.

## Dataset
The dataset used for this project contains several key features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: A function which scores likelihood of diabetes based on family history
- **Age**: Age of the patient (years)
- **Outcome**: Binary variable (1 if diabetic, 0 otherwise)

## Features
- Data exploration and visualization
- Data preprocessing (handling missing values, feature scaling)
- Model building with various machine learning algorithms (logistic regression, decision trees, etc.)
- Model evaluation using accuracy, precision, recall, and ROC curve

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/diabetes-prediction.git
## Usage

1. Open the Jupyter notebook:
   ```bash
   jupyter notebook Diabetes_Prediction.ipynb
2. Once the notebook is open, run the cells step by step:
   - Start by loading the dataset.
   - Perform data preprocessing, such as handling missing values and feature scaling.
   - Train the machine learning models.
   - Evaluate model performance using metrics like accuracy, precision, recall, and ROC curve.

3. You can modify the notebook to:
   - Experiment with different machine learning algorithms.
   - Adjust hyperparameters for improved model performance.
   - Explore additional insights and visualizations from the dataset.
## Results

After training several machine learning models, the XGBoost model achieved the highest accuracy of **0.7965**.

Other models were evaluated, but XGBoost outperformed them in terms of accuracy. More details on the model performance, including precision, recall, and the ROC curve, can be found in the notebook.

Feel free to experiment with different algorithms and hyperparameters to improve the performance further.
