# UMOJA HACK AFRICA 2022 Intermediate Challenge

This challenge is part of the Zindi Umoja Hack Series for African University students.

A Repo of my solution to the Umoja HAck Intermediate Challenge Competition Hosted on Zindi.africa 5th Place Solutuion

Position on Leader Board -- 5th of 253 (Top 1%)

To get the Data check the link Below
link -- https://zindi.africa/competitions/umojahack-africa-2022-intermediate-challenge

# Monthly Insurance Claim Prediction

Short-term insurance claims are one of the largest costs in the insurance industry, and are extremely difficult to forecast. Zimnat Insurance wants to predict the value of future claims per client, in order to better forecast annual costs.

The objective of this challenge is to create a ##machine learning model to predict how much a client will claim from Zimnat per month for a whole year.

The solution will aid Zimnat in being better prepared to address claims that are submitted, and improve customer satisfaction by alerting clients to possible claims they will make in the future.# Predict if the text would be considered positive, neutral or negative (for an average user).


## MY Solution Approach
- A Catboost Model
    - Exploratory Data Analysis 
    - Data Transformation and Feature Engineering to Create More Features
    - Created new Feature with the Loss Date Column and drop some column that were acting as noise after creating a baseline model
    - Used a Kfold of 10 Splits as this perform well
    -Used Deafault parameters for training 

## Other Notebook and Experiment i tried
- KMode Notebook
- LGBM Log Transform
- aws Baselne Notebook
