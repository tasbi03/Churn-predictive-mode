# Predictive Analytics to Increase Telecom Customer Retention 📶

## Overview 📝
This project aims to predict customer churn for a telecom company, assisting the business in identifying and retaining at-risk customers. We used various machine learning models to predict whether customers would churn based on their data profiles. This repository contains all the codes and files used in this analysis.

## Team 👥
- **Aeraf Mohammed Khan**
- **Madhur Saluja**
- **Tasbi Tasbi**

**👩‍🏫 Supervised by:** Vida Movahedi

## Badges 🏆
![Python](https://img.shields.io/badge/python-3.8-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Table of Contents 🗂
- [Installation](#installation)
- [Usage](#usage)
- [Methodology](#methodology)
- [Results](#results)
- [Conclusion](#conclusion)
- [License](#license)

## Installation 🛠
To set up the project environment, run the following commands:


pip install -r requirements.txt


## Usage 🚀

Each notebook is self-contained and includes steps from data processing to model evaluation. Open the Jupyter notebooks in the following order to replicate the analysis:

- `DataPreparation.ipynb` - Preprocessing and cleaning data.
- `ModelTraining.ipynb` - Training baseline models.
- `AdvancedModels.ipynb` - Employing more complex models.
- `FeatureEngineering.ipynb` - Enhancing features for better predictions.
- `FinalEvaluation.ipynb` - Testing and final model evaluation.

## Methodology 🧪

- **Data Exploration and Preprocessing:** The dataset was cleaned and prepared, removing unnecessary features and encoding categorical variables.
- **Model Training:** Baseline models (Logistic Regression and Decision Tree) were trained.
- **Advanced Models:** Included Random Forest and SVM to enhance predictive accuracy.
- **Feature Engineering:** Refined features to improve model inputs.
- **Hyperparameter Tuning:** Used GridSearchCV for optimizing model parameters.
- **Final Testing:** Evaluated the tuned models on unseen test data.

## Results 📊

The Logistic Regression model exhibited notable performance improvements after SMOTE adjustment and hyperparameter tuning, surpassing the baseline Decision Tree model in all significant metrics. Feature engineering and careful model selection played critical roles in achieving high accuracy and recall.

## Conclusion 🔍

This project demonstrates the effectiveness of machine learning in predicting customer churn. The insights derived from this analysis can help telecom companies implement more focused customer retention strategies.

## Detailed Report
For more in-depth analysis, you can view the [Detailed Analysis Report](Report.pdf).

