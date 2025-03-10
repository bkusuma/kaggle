# House Prices - Advanced Regression Techniques

## Description

This is a Kaggle "Getting Started Prediction Competition" for the purpose of predicting sales prices and practicing feature engineering, random forests, and gradient boosting.

The Ames Housing dataset was compiled by Dean De Cock for use in data science education. With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition issues the challenge to predict the final price of each home.

### Who might benefit from this project?  How? 
- Housing companies like Zillow or Redfin, private buyers or sellers, or banks could all benefit to know how to predict house values

### What is the goal?
- To train a model on house values given certain inputs
1. Analyze house dataset for actionable insights
2. Create model with .138 or lower RMSLE

    N.B. The Root Mean Squared Log Error (RMSLE) is the square root of the expected value of the squared logarithmic (quadratic) error or loss.

    If $\hat{y}_i$ is the predicted value of the $i$-th sample, and $y_i$ is the corresponding true value, then the RMSLE estimated over $n_{\text{samples}}$ is defined as:

    $ \text{RMSLE}(y, \hat{y})$ =

    $\sqrt{\frac{1}{n_\text{samples}} \sum_{i=0}^{n_\text{samples} - 1} (\ln(1 + y_i) - \ln(1 + \hat{y}_i))^2 }$

    Where $\ln (x)$ means the natural logarithm of $x$

## Table of Contents

- [Exploratory Data Analysis](#Exploratory)
- [Data Processing](#Data)
- [Modelling](#Modelling)
- [Acknowledgements](#Acknowledgements)

## Exploratory Data Analysis

### What does the data describe? (What is a row?)
- All the characteristics of a house. A row is the data from a house.

### What is the shape of the data?
- The shape of the DataFrame is 1460 observations (rows), 80 features (columns)
- There are 37 numeric and 43 object features
- There are 79 features for use in predicting the house sale price indicated by target column `SalePrice`

## Data Processing

## Modelling

## Acknowledgments

In the process of developing this file, I used not only my own ideas: I read many recommendations for README files, examined real READMEs in actual use, and tried to distill the best ideas into the result you see here.

Sources included the following:

* [mhucka's readmine](https://github.com/mhucka/readmine)