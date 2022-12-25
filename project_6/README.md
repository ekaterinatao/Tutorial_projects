# Project 6. Homework 6. Optimization: coordinate descent, stochastic gradient descent  

## Table of contents
[1. Description](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_6#description)   
[2. Aim](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_6#aim)  
[3. Datasets](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_6#datasets)  
[4. Results](https://github.com/ekaterinatao/Tutorial_projects/tree/main/project_6#results)  

## Description
There is Advertising dataset. We should perform linear regression model and optimize its loss-function with both coordinate descent and stochastic gradient descent.

## Aim
Realizing and comparing algorithms of coordinate descent and stochastic gradient descent.  

**Briefing**  
- There is dataset.
- We should perform linear regression model with target parameter 'sales'.
- We should optimize loss-function without using sklearn. Two algorithms were tested (coordinate and stochastic gradient descent).

**Skills**  
Learn to write good code.  
Realizing algorithms of coordinate descent and stochastic gradient descent on your own.   

## Datasets
You can find original dataset in the project folder.  

**Parameters**
- TV — advertising costs on TV;
- radio — advertising costs on radio;
- newspaper — advertising costs on newspaper;
- sales.  

## Results
- Data was standardized using own algorithm.
- Naive prediction isn't accurate.
- Result of own coordinate descent algorithm is equal to sklearn realization.
- Stochastic gradient descent minimises loss-function with small number of iterations, but it depends on initial random choise, given treshold and learning rate.
- Metrics that were used: mean squared error.