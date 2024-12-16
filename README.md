# ecommerce-customer-churn-analysis-and-prediction

## Overview
ML classification project to predict customers that are about to churn

## Link to dataset
https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction/data

## Project approach
1) Data cleaning
2) Exploratory data analysis
3) Sci-kit learn base models + LightGBM + XGBoost
4) Feature engineering
5) Hyperparameter tuning using Grid Search

## Best set of results
Best f1-score: RF model with hyperparameter tuning (accuracy = 96.62%, recall = 86.27%, precision = 93.16%, f1 = 89.58%)
Model with best overall score across metrics: VotingClassifier model made up of RF, LightGBM and XGBoost with hyperparameter tuning (accuracy = 96.44%, recall = 89.08%, precision = 89.72%, f1 = 89.40%)
