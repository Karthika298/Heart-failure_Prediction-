# Heart Failure Prediction using Classification Algorithms-
## Overview
This repository contains code for building and evaluating predictive models to classify instances of heart failure based on the provided dataset. The goal is to develop models that can accurately predict the occurrence of heart failure based on various patient attributes and medical indicators.
### Dataset
The dataset used for modeling and evaluation consists of patient data related to heart failure such as age, anemia, creatinine phosphokinase, diabetes, ejection fraction, high blood pressure, platelets etc. 
* The dataset can be downloaded from the repository which is available as [Heart Failure prediction.csv](https://github.com/Karthika298/Heart-failure_Prediction-/blob/main/heart_failure_clinical_records_dataset%20(1).csv)
### Exploratory Data Analysis (EDA)
 * Analysis of target variable distribution to understand class balance or imbalance.
* Visualization of numerical feature distributions using histograms to identify patterns and outliers.
* Examination of correlations between features to understand relationships amongst them.
* Exploration of how the target variable affects numerical features through plots such as violin plots and stacked bar plots.
 ### Predictive Modeling
The repository implements various classification algorithms to build predictive models for heart failure classification. The models are trained and evaluated using metrics such as accuracy, precision, recall, F1-score, and Area Under the ROC Curve (AUC-ROC).
* In summary, **logistic regression**, **XGBoost, ETC, Support Vector Classifier, and Linear Discriminant Analysis** appear to be the top-performing models based on their high accuracy, MCC score, and balanced F1 score, precision, and recall. These models demonstrated good discrimination ability indicated by high AUC scores.
* The codes are available in [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1bh4VT6jPqHleG_gztcIAiFmYpk8l0mpB#scrollTo=c2m_TRVmaUc3) .



