# Project 1: NYC-Property-Tax-Fraud-Detection

## Reposititory File Description

1. NY_Fraud_DQR.ipynb - Python Jupyter notebook containing a preliminary quantitative analysis that explores and documents the basic characteristics of the NYC property dataset
2. NY_Fraud.ipynb - Python Jupyter notebook containing the full code for this project including data cleaning, featur engineering and modeling

## Dataset
Property Valuation and Assessment Data Dataset Source: Open data of NYC government Dataset URL: https://data.cityofnewyork.us/Housing-Development/Property-Valuation-andAssessment-Data/rgy2-tti8 

## Summary
I analyzed New York City’s (NYC’s) real estate data to identify property tax fraud for 107 K+ NYC property records with 31 data fields. I first performed exploratory data analysis, completed Data Quality Report(DQR), and filled in missing values with median of each group after aggregating by categorical variables. Second I created 45 expert variables by calculating product, ratio and aggregated values of original variables, scaled(z-scale) all variables and reduced dimensionality by Principle Component Analysis(PCA).Finally I built a heuristic function of z-score model and a neutral net auto-encoder model to get two fraud scores for each property, and scaled each score by quantile binning to combine them into a final fraud score.
