# Hematopoietic Stem Cell Transplant Survival Analysis

Group Project 

## Overview
This project analyzes data from patients who underwent hematopoietic stem cell transplant (HSCT) and predicts survival outcomes using a clinical dataset containing detailed patient information and associated variables.

The project focuses on survival analysis using multiple machine learning approaches, including:
- Random Survival Forest (RSF)
- XGBoost with Kaplan-Meier estimators
- Cox Proportional Hazards with Kaplan-Meier estimators
- Deep learning-based survival models
- Graph Neural Networks (GNN)

## Project Structure
The project includes the following major components:

- **Data Engineering & Cleaning**  
  Preprocessing and cleaning of raw data to prepare it for analysis and modeling.

- **Exploratory Data Analysis (EDA)**  
  Initial data exploration, visualization, and summary statistics.

- **Model Development and Implementation**
  - Random Survival Forest
  - XGBoost with Kaplan-Meier estimators
  - Cox Proportional Hazards with Kaplan-Meier estimators
  - Deep learning survival model
  - Graph Neural Network (GNN) survival model

## Performance Metric: Concordance Index
The primary evaluation metric used in this project is the **Concordance Index (C-index)**.

The C-index measures the agreement between predicted risk scores and actual observed survival outcomes. It reflects the inverse relationship between risk scores and survival times, where a higher value indicates better predictive performance.

## Prerequisites
Before running the project, make sure you have **Python 3.7 or higher** installed.

Install the required packages with:

```bash
pip install torchtuples pycox
pip install lifelines
pip install scikit-survival pandas numpy
pip install xgboost
