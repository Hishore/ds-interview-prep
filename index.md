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

### Q [Data Analysis] What is the curse of dimensionality? [WIP]

- The curse of dimensionality refers to various phenomena that arise when analyzing and organizing data in high-dimensional spaces that do not occur in low-dimensional settings such as the three-dimensional physical space of everyday experience.

### Q [Product Metrics] What would be good metrics of success for an advertising-driven consumer product? (Buzzfeed, YouTube, Google Search, etc.) A service-driven consumer product? (Uber, Flickr, Venmo, etc.)

- Pageviews, daily actives, CTR (Click-Through Rate), & CPC (Cost Per Click) are good metrics of success for an advertising-driven consumer product
- Number of purchases & conversion rate are good metrics of success for a service-driven product

### Q [Product Metrics] What would be good metrics of success for a productivity tool? (Evernote, Asana, Google Docs, etc.) A MOOC? (edX, Coursera, Udacity, etc.)

- Daily actives, & conversion rate are good metrics of success for a productivity tool
- Number of purchases, conversion rate, & completion rate are good metrics of success for a MOOC

### Q [Product Metrics] What would be good metrics of success for an e-commerce product? (Etsy, Groupon, Birchbox, etc.) A subscription product? (Netflix, Birchbox, Hulu, etc.) Premium subscriptions? (OKCupid, LinkedIn, Spotify, etc.)

- E-commerce:
  - Conversion rate
  - Number of purchases (Hourly/daily/weekly/monthly/quarterly/annual sales)
  - Cost of goods sold
  - Site visits
  - Unique visitors versus returning visitors
  - Customer service phone call count
  - Time to resolution
  - Inventory levels
- Subscription
  - Churn rate (possible indicator of customer dissatisfaction, cheaper and/or better offers from the competition, more successful sales and/or marketing by the competition, or reasons having to do with the customer life cycle)
  - Customer acquisition cost
  - ARPU (Average Revenue Per User)
  - MRR (Monthly Recurring Revenue)
  - LTV (Life Time Value)
- Premium subscriptions
  - subscription rate

### Q [Product Metrics] What would be good metrics of success for a consumer product that relies heavily on engagement and interaction? (Snapchat, Pinterest, Facebook, etc.) A messaging product? (GroupMe, Hangouts, Snapchat, etc.)

- Daily/monthly actives, daily/monthly number of: content publishes per active user, shares per active user (or similar depending on the product), likes per active user (or similar depending on the product) would be good metrics for a consumer product that relies heavily on engagement and interaction.
- Daily/monthly actives, daily/monthly number of messages per active user would be good metrics for a messaging product.

### Q [Product Metrics] What would be good metrics of success for a product that offered in-app purchases? (Zynga, Angry Birds, other gaming apps)

- Conversion rate (active to purchasing users), number of purchases, revenue per user, revenue per purchasing user would be good metrics of success for a product that offered in-app purchases.

