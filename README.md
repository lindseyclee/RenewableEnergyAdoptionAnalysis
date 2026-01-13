# RenewableEnergyAdoptionAnalysis

Course: CPSC 393 - Machine Learning

## Overview:

This project uses Data Science to examine the impact of adopting renewable energy across countries using a [Global Data on Sustainable Energy (2000-2020) dataset](https://www.kaggle.com/datasets/anshtanwar/global-data-on-sustainable-energy/code) from Kaggle. Key features used in our analysis include country, year, electricity access (%), CO2 emissions (kt), energy intensity level, types of electricity (from fossil fuels, nuclear, or renewables), financial flows, and GDP per capita. 

## Research Topics:

1. Which countries will reach 50% of electricity produced by renewables by 2030? **(Linear Regression Forecast Model)**
2. Which countries will benefit from renewable energy, where they are most effective in cutting down CO2 emissions? **(Random Forest Model)**

## Additional Notes:

* I collaborated on this project with Alex Lark who did work for Question 1, while I did work for Question 2.
* We removed the entity (country), French Guiana, from the dataset as it had too many missing values to be eligible for use.
* We applied a Denoising Autoencoder (DAE) to help us fill in missing data values from the real world dataset. This new dataset, named energy_final, was then used for Question 2.
* Please refer to our final report document for additional details on our methods and analyses.

## References:

* https://www.geeksforgeeks.org/machine-learning/auto-encoders/   
