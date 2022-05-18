# Credit Risk Analysis

## Overview of the analysis: 
Using data from LendingClub, we will create and run Machine Learning modules to calculate Credit Risk in loan applications. We will use six machine learning modules to complete this analysis. They are split into two files credit_risk_resampling.ipynb and credit_risk_ensemble.ipynb. 

- Resources 
  - Pandas, Jupyter Notebook
  - LoanStats_2019Q1.csv 
  - scikit-learn and imbalanced-learn libraries

## Results: 
Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all six machine learning models. Use screenshots of your outputs to support your results.

### Six learning modules

#### Sampling Modules:
**1. Naive Random Oversampling**
    - The Random Oversampling model "instances of the minority class are randomly selected and added to the training set until the majority and minority classes are balanced."
    
**2. SMOTE Oversampling**
    - SMOTE stands for Synthetic Minority Oversampling Technique. It is where new values are created based on the proximity of minority values. 
    
**3. Cluster Centroid Undersampling**
    - In Undersampling, the larger data is decreased to match the minority data. 
    
**4. SMOTEENN (Combination Over and Undersampling)**
    - Combining SMOTE and ENN (Edit Nearest Neighbors algorithms, first you oversample with SMOTE and then clean the data using undersampling. Any outliers will be dropped. 
    
#### Ensemble Classifiers:
**5. Balanced Random Forest Classifier**

**6. Easy Ensemble AdaBoost Classifier**
    - The model is trained and evaluated, then another model is trained using the knowlege from the previous model. Each model is built upon from the previous one. 

## Summary: 
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
