## Data Science Interview Prep 数据科学面试准备

This will cover data science interview questions from "120 Data Science interview questions", and "Data_Science_Product_Questions", and real interview questions from various companies.

### Q1 [Predictive Modeling] (Given a Dataset) Analyze this dataset and give me a model that can predict this response variable.

- Problem Determination -> Exploratory Analysis -> Data Cleaning -> Feature Engineering -> Modeling -> Evaluation
- Determine if the problem is classification or regression
- Plot and visualize the data
- Start by fitting a simple model (multivariate/logistic regression), do some feature engineering accordingly, and then try some complicated models. Always split the dataset into train, validation, test dataset and use cross validation to check model performance.
- Benchmark Models
  - Regression: Linear Regression (Ridge or Lasso)
  - Classification: Logistic Regression
- Advanced Models
  - Random Forest, Boosting Trees, and so on
    - Scikit-Learn, XGBoost, LightGBM, CatBoost
- Use cross validation as a means to evaluate the model
- Favor simple models that run quickly and are easy to explain

### Q2 [Programming] Write a function to calculate all possible assignment vectors of 2n users, where n users are assigned to group 0 (control), and n users are assigned to group 1 (treatment).

- Idea 1: Use existing functions in python

- Idea 2: Use a recursive approach to do it.
