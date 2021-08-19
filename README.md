# Kaggle Housing Price Prediction Competition Submission
## Summary
This is my submission for the Kaggle housing price prediction competition. The goal of the competition is to predict the price of houses in Ames, Iowa using 79 explanatory variables.

I compared the performance of Random Forest and Extreme Gradient Boosting (XGBoost) regressors with different hyperparameters tuned by cross-validation. 
The algorithm included in this Jupyter Notebook achieved a mean absolute error of $14,439, placing it in the <b>top 1%</b> of submissions. I found that the keys to reducing the error were data cleaning, which increased the amount of training data used, and using an XGBoost regressor with tuned hyperparameters.

## Competition Introduction
>#### Start here if...
>You have some experience with R or Python and machine learning basics. This is a perfect competition for data science students who have completed an online course
in machine learning and are looking to expand their skill set before trying a featured competition. 

>#### Competition Description
>Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad.
But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.
With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

>#### Practice Skills
>*   Creative feature engineering 
>*   Advanced regression techniques like random forest and gradient boosting

>#### Acknowledgments
>The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It's an incredible alternative for data scientists looking for a modernized and expanded version of the often cited Boston Housing dataset. 

From the competition [homepage](https://www.kaggle.com/c/home-data-for-ml-course/overview).
