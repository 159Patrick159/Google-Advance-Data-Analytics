# Predicting Employee Turnover Rates

### Overview
The goal of this project was to create a predictive model either through multiple logistic regression or through machine learning algorithms such as Random Forest Classifers or Categorical Gradient Boosting estimators. This project utilized employee statistics recorded by Salifort Motors and is the capstone project for Google's Advance Data Analytics Professional Certificate. The champion model for this analysis was a random forest with tuned hyper-parameters. The following metrics were used to evaluate the algorithm's success.

|Model Name|F1 Score|Precision|Recall|Accuracy|
|:---:|:---:|:---:|:---:|:---:|
|Tuned Random Forest| 97.21%| 98.47%| 95.98%| 98.65%|

The random forest model determined the most relevant features for separating employees that are likely to leave to those who won't are `satisfaction_level`, `time_spent_with_company`, and `hours_per_project`. We note that the latter features was engineered and that it represents the employees engagement in the company's goals.