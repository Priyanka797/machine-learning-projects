# Diabetes Prediction using Logistic Regression

A machine learning project that predicts whether a patient has diabetes
based on health metrics, using logistic regression.

## Overview
This project uses the Pima Indians Diabetes dataset to build a binary
classification model. It walks through data cleaning, exploratory analysis,
model training, and evaluation.

## Dataset
- **File:** `diabetes.csv`
- **Records:** 768 patients
- **Features:** Pregnancies, Glucose, Blood Pressure, Insulin, BMI,
  Diabetes Pedigree Function, Age
- **Target:** Outcome (1 = diabetic, 0 = non-diabetic)

## Steps
1. **Data cleaning** – replaced invalid zero values in Glucose, Blood Pressure,
   Insulin, and BMI with the column median; checked for duplicates and nulls.
2. **Exploratory data analysis** – visualized distributions, correlation
   heatmap, and feature relationships.
3. **Model** – trained a Logistic Regression classifier (scikit-learn),
   split 80/20 train/test.
4. **Evaluation** – measured accuracy and reviewed a confusion matrix.

## Results
- Model accuracy: ~78%
- Glucose and BMI showed the strongest relationship with the outcome.

## Tools
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## How to Run
Open the notebook in Google Colab and run all cells
(Runtime → Run all). The dataset loads directly from this repository.
