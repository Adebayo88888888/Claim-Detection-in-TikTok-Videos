# Claim-Detection-in-TikTok-Videos


## Business Understanding:

The data team at TikTok aims to create a machine learning model to predict if a video contains a claim or an opinion, which would help prioritize user reports more efficiently. Additionally, stakeholders want to explore how different variables relate to a user's verification status.


### Data understanding:

This activity uses a dataset from TikTok, that has 12 columns which includes claim status which is the outcome variable , video Id, duration of video, number of likes, downloads, comments... for 19,400 unique  entries.


#### Modeling and Evaluation:

The project started with EDA, and data wrangling to fin patterns and trends in the dataset. We then moved to building a regression model and feature Importance table to see what features are most important to the prediction. We also conducted hypothesis test on some of the variables to see if the outcomes are statistically significant or due to chance. We wrapped the process up by building a supervised machine learning algorithms to classify if a video is a claim or opinion.


## Conclusion:

We came to a conclusion that with a 99% accuracy and precision of our model, from XGBOOST which is the champion model, there is no need to engineer any new features. Also we highly recommend that the stakeholders deploy our model in order to reduce the backlog of user reports and prioritize them more efficiently.
