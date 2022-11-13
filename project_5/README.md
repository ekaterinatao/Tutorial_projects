# Project 5. Homework 5. Linear regression.

## Table of contents
[1. Description](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_5/README.md#Description)   
[2. Aim](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_5/README.md#Aim)  
[3. Datasets](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_5/README.md#Datasets)  
[4. Results](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_5/README.md#Results)  

## Description
There is oil and gas company. We should perform linear regression model to evaluate factors that influense on gas production.

## Aim
To evaluate factors that influense on gas production.  

**Briefing**  
- There is dataset.
- We should perform linear regression model with target parameter 'Prod'.  

**Skills**  
Learn to write good code.  
Train to write linear regression code on your own.  
Train Sklearn skills.  

## Datasets
You can find original dataset in the project folder.  

**Parameters**
- Well — well ID;
- Por — porosity (%);
- Perm — permeability;
- AI —  acoustic impedance (kgm);
- Brittle — brittleness index (%);
- TOC — total organic carbon (%);
- VR — vitrinite reflectance (%);
- Prod — production per day (million cubic feet).  

## Results
- There is short analytics at the beginning of the notebook.  
- Multi-collinear predictors were removed.
- Data was standardized using StandardScaler.
- Simple linear regression model was performed on your own, than using sklearn.
- Polinominal features transformation was performed using sklearn.preprocessing.
- Lasso- and Ridge-regression were performed using sklearn.
- All models were evaluated using sklearn cross validation on 5 folds.
- Metrics that were used: mean absolute percentage error and mean squared error.