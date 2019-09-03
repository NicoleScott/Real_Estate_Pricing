# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png)  Project 2:  Ames Housing Data and Kaggle Challenge
Creating and Tuning a Linear Regression Model to Predict Housing Prices in Ames, IA

---
## Problem Statement

You are tasked with creating a regression model based on the Ames Housing Dataset. This model will predict the price of a house at sale. The Ames Housing Dataset is an exceptionally detailed and robust dataset with over 70 columns of different features relating to houses.

---
## Executive Summary

This technical report includes statistical analysis and data visualizations to illustrate the process of creating a regression model to predict the sale price of a home in Ames, IA. The top 10 Features most closely correlated to sale price of a home in Ames, IA were determined to be:
 - Overall Quality
 - Gross Living Area
 - Garage Cars
 - Year Built
 - Garage Area
 - Full Bath
 - Total Basement Square Footage
 - Year of Remodel/Addition
 - Foundation
 - 1st Floor Square Footage

---
## Technical Report
A detailed technical report illustrating my process and predictions can be accessed via links in the Contents section below.

### Contents:
- [EDA, Modeling and Kaggle Steps](02_Ames_EDA_Modeling_and_Kaggle.ipynb)

### Kaggle Competition:
Requirements for the Kaggle competition portion of this project:
 1. Create an account at [Kaggle](https://www.kaggle.com/) 
 2. Click this link ([Regression Challenge Sign Up](https://www.kaggle.com/t/2507fed3dd314a4789002d80122d0e68)) to **join** the competition
 3. Make at least one successful prediction submission on [DSI-US-8 Regression Challenge](https://www.kaggle.com/c/dsi-us-8-project-2-regression-challenge)
 4. Check your name in the "[Leaderboard](https://www.kaggle.com/c/dsi-us-8-project-2-regression-challenge/leaderboard)" tab.

---
## Conclusions and Recommendations

#### Model Results
My final R2 score was 90.7 which represents the percentage of explained variance in my model. While my training and test scores (.92 and .90 respectively) are relatively close together, my model is still overfit and could use additional tuning. To reduce variance in the model, I recommend introducing some feature engineering options, including:
 - remove some (but not all) of the noisy, less closely correlated features
 - combine some new features related to Garage and Bathrooms, as well as Roofing and Heating, which intuitively (based on weather) seem like they would add value to homes in a cold winter state like Iowa

#### Kaggle Results
At the end of the Kaggle competition, my submission was #88 on the leaderboard. Given that the competition results were based on the RMSE evaluation metric and my model was evaluated based on R2 score, I would recommend re-evaluating and resubmitting to Kaggle based on RMSE score.

