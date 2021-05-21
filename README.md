# Text-Topic-Classification-for-QA-Website-Posts

## Project Overview
This project is a text classification problem for the comments posted on two Q&A websites.   
All of these comments are classified into 16 different topics.   

## Description of Project Folders
### 00_data
There are 955,454 comments in the training data and 552,735 comments in the test data.

### 01_eda  
 - `01_eda.ipynb`  
This file contains EDA for class distribution, word clouds and most frequent words for each class.  

### 02_feature_engineering  
 - `02-01_statistical_features.ipynb`   
This file creates features based on statistical characteristics.

 - `02-02_lda_based_features.ipynb`  
This file creates features based on the most frequent words for each class.

### 03_model  
This folder contains the models for two running cases.

 - `03-01_baseline_model.ipynb`  
Baseline model without feature engineering, using CountVectorizer, Multinomial Naïve Bayes and Bayesian Optimization.     

 - `03-02_best_score_model.ipynb`  
Best performance model with all features and the ‘Pseudo-Labelling’ method.

### 04_report
This folder contains the final project report. 
