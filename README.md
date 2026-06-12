# NILM-Household-Energy-Disaggregation

Non-Intrusive Load Monitoring (NILM) for Household Appliance Energy Disaggregation
Overview

This project implements an end-to-end Non-Intrusive Load Monitoring (NILM) system that disaggregates household appliance energy consumption from a single aggregate smart meter signal.

The system identifies and estimates the energy consumption of:

Kettle
Fridge
Washing Machine
Dishwasher

using Deep Learning models trained on the REFIT dataset.

Features
Deep Learning based appliance detection
CNN-BiLSTM architectures
Leave-One-House-Out (LOHO) evaluation
Streamlit deployment
Energy analytics dashboard
Electricity bill estimation
Energy forecasting
Savings simulator
Technologies
Python
PyTorch
Streamlit
Pandas
NumPy
Google Colab
Results
Appliance	F1 Score
Kettle	0.784
Fridge	0.688
Washing Machine	0.577
Dishwasher	0.726
Skills Demonstrated
Machine Learning
Deep Learning
Time Series Analysis
Feature Engineering
Model Evaluation
Data Preprocessing
Streamlit Deployment
