# Credit Card Fraud Detection with Databricks & PySpark

## Overview

This project develops a machine learning solution for detecting fraudulent credit card transactions using Databricks and PySpark. The objective is to identify high-risk transactions and support real-time fraud prevention in financial services.

## Data Source

https://www.kaggle.com/datasets/kartik2112/fraud-detection/data

## Business Problem

Credit card fraud causes significant financial losses and operational risks for financial institutions. This project analyzes transaction patterns and customer behavior to predict fraudulent transactions and improve fraud detection accuracy.

## Dataset

The project uses a credit card transaction dataset containing transaction details, customer information, merchant data, geographic information, and timestamps.

Target Variable:

* `is_fraud`

  * 1 = Fraudulent Transaction
  * 0 = Legitimate Transaction

## Technologies

* Databricks
* PySpark
* Python
* Data Visualization

## Project Workflow

1. Data ingestion and preprocessing
2. Data cleaning and feature engineering
3. Temporal feature extraction (hour, day, month)
4. Spatial feature engineering (transaction distance)
5. Exploratory Data Analysis (EDA)
6. Model training and evaluation
7. Fraud risk prediction

## Machine Learning Models

* Logistic Regression (Baseline)
* Gradient-Boosted Trees (GBT)

## Key Findings

* Fraud occurrence shows temporal patterns rather than purely random behavior.
* Transaction timing is an important indicator of fraud risk.
* Gradient-Boosted Trees outperform Logistic Regression by capturing complex non-linear relationships in the data.
* High-risk periods can be identified and used to strengthen fraud prevention controls.

## Results

The Gradient-Boosted Trees model achieved superior fraud detection performance and demonstrated the value of feature engineering and big-data processing for fraud analytics.

## Repository Structure

* Databricks Notebook
* Data preprocessing pipeline
* Feature engineering workflow
* Model training and evaluation
* Fraud detection analysis

## Authors

Hyeonjeong Yoon, Jiajia Li, Hyeonji Jo, Shuwen Zheng
