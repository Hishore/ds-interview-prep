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

### Q [Data Analysis] (Given a Dataset) Analyze this dataset and tell me what you can learn from it.

- Understanding the goal
- Data cleanning (outliner treatment, missing value imputation)
- Exploratory analysis - visualizaitons (numerical values: scatter plot; categorical values: frequencies) to prevent future missteps, identify possible transformations needed
- Confirm assumptions
- Summary statistics (mean, median, mode, minimum value, maximum value, range, standard deviation, etc.)
- Time series, geographic distribution
- Design metrics that can achieve the goal
- Synthesize results and think about additional data that can help

### Q [Data Analysis] What is R-squared? What are some other metrics that could be better than R-squared and why?

- R-squared is the proportion of the variance in the dependent variable that is predictable from the independent variable(s). It is a statistic used in the context of statistical models whose main purpose is either the prediction of future outcomes or the testing of hypotheses, on the basis of other related information. R-squared equals one minus the sum of squares of residules devided by the total sum of squares.
- Adjusted R-squared could be better than R-squared because of its attempt to account for the phenomenon of the R-squared automatically and spuriously increasing when extra explanatory variables are added to the model.
- AIC could also be better than R-squared because it penalizes the inclusion of additional variables to a model.
