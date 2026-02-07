# De-identifying Clinical Text
This project contains a Jupyter notebook (Coding.ipynb) that works with a synthetic clinical dataset and demonstrates how to analyse and model de-identified health records while preserving data utility.

# Project Overview
Uses synthetic patient-level data with fields such as Patient_ID, Age, Gender, Medical_Condition, Treatment, Outcome, Insurance_Type, Income, Region, Smoking_Status, Admission_Type, Hospital_ID, and Length_of_Stay.

Performs exploratory data analysis (EDA) to understand distributions (count, mean, standard deviation, min, max, and quartiles) for key numeric variables.

Shows example patient rows combining demographics, clinical variables and hospital-related information.

Trains a machine learning model on the dataset and reports training and validation loss over several epochs.

# Notebook Contents
Coding.ipynb typically includes:

Data loading and basic cleaning of the synthetic clinical dataset.

Descriptive statistics tables for numeric features (e.g. Age, Income, Hospital_ID, Length_of_Stay).

Display of a sample of patient records to illustrate the structure and types of variables.

Feature preparation for modelling (encoding categorical features and scaling/processing numeric ones).

Model training section, logging Epoch, Training Loss and Validation Loss to monitor learning progress.

# How to Use This Notebook
Explore the synthetic dataset and understand each column’s meaning and distribution.

Experiment with simple de-identification strategies (e.g. removing or transforming Patient_ID, bucketing Age, banding Income, or generalising regions).

Train and evaluate a predictive model (for example, predicting Length_of_Stay or another target) using the prepared features.

Observe how changes in preprocessing or de-identification affect model performance.

# Disclaimer
The data used in this notebook is synthetic and intended purely for learning and experimentation.

The notebook is not a production-ready de-identification solution and should not be applied directly to real patient data without rigorous privacy, legal and ethical review.

License
