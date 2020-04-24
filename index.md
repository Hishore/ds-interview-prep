## Welcome to Data Science Interview Prep 欢迎光临数据科学面试准备

This will cover data science interview questions from "120 Data Science interview questions", and "Data_Science_Product_Questions", and real interview questions from various companies.

### Q1 (Given a Dataset) Analyze this dataset and give me a model that can predict this response variable.

- Start by fitting a simple model (multivariate regression, logistic regression), do some feature engineering accordingly, and then try some complicated models. Always split the dataset into train, validation, test dataset and use cross validation to check their performance.
- Determine if the problem is classification or regression
- Favor simple models that run quickly and you can easily explain.
- Mention cross validation as a means to evaluate the model.
- Plot and visualize the data.

- Problem Determination -> Data Cleaning -> Feature Engineering -> Modeling
- Benchmark Models
  - Linear Regression (Ridge or Lasso) for regression
  - Logistic Regression for Classification
- Advanced Models
  - Random Forest, Boosting Trees, and so on
    - Scikit-Learn, XGBoost, LightGBM, CatBoost
- Determine if the problem is classification or regression
- Plot and visualize the data.
- Start by fitting a simple model (multivariate regression, logistic regression), do some feature engineering accordingly, and then try some complicated models. Always split the dataset into train, validation, test dataset and use cross validation to check their performance.
- Favor simple models that run quickly and you can easily explain.
- Mention cross validation as a means to evaluate the model.
