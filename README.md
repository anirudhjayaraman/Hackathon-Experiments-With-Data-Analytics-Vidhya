# Hackathon-Experiments-With-Data-Analytics-Vidhya
My approach in Python (with Jupyter Notebooks) for a hackathon / workshop conducted by Analytics Vidhya. This repository contains the train and test data along with my approach and submission files.

All missing data in this dataset were for categorical variables. I did a simple mode-imputation to deal with such missing values.

I approached the problem by first attempting some feature engineering (not including missing value treatment) on the data, after which I ran a basic logistic classifier and a random forest classifier. However, the models performed better without feature engineering, so maybe the dataset was already quite clean and informative to start with, which might have been the case for this competition.

I later attempted gradient boosting with parameter tuning and maximizing scores.

Here's a link to the [leaderboard](https://datahack.analyticsvidhya.com/workshop/experiments-with-data-5/lb). I'm anirudhjay :)
