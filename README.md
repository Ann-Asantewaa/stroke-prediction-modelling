

# Stroke Prediction Model Using R

This project aims to build and deploy a **stroke prediction model** using patient demographic and clinical data.  
It applies statistical and machine learning techniques in **R** to predict stroke risk and support early intervention in healthcare.

## Project Overview

Stroke is one of the leading causes of death worldwide.  
Using a dataset of **5,110 patients** and **12 variables**, this analysis explores key predictors such as age, hypertension, heart disease, and glucose levels.

## Data Cleaning and Preprocessing

Key steps included:
- Handling missing values using median and mode imputation.  
- Normalizing numeric variables for consistency.  
- Balancing the dataset using **SMOTE** to address class imbalance.

## Model Building

A **logistic regression model** was trained with:
- 80% training and 20% testing split  
- 5-fold cross-validation  

**Performance (Validation set):**
- ROC AUC: 0.84  
- Accuracy: 0.76  
- Precision: 0.98  
- F1-score: 0.85  


## Model Files

- `final_logistic_workflow.rds` – Trained model workflow  
- `final_recipe.rds` – Preprocessing pipeline  

These can be reloaded in R for deployment or further testing.


## Files in this Repository

| File | Description |
|------|--------------|
| `ModellingStroke.Rmd` | Full analysis code and report |
| `ModellingStroke.html` | Knitted HTML report |
| `Build and Deploy a Stroke Prediction Model Using R.pdf` | PDF version of the final report |
| `final_logistic_workflow.rds` | Trained model file |
| `final_recipe.rds` | Data preprocessing recipe |
| `README.md` | Project overview (this file) |


##  Author
**Angela Asantewaa Adomako**  




