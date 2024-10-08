# Bati Bank Credit Scoring Model
The Bati Bank Credit Scoring Model leverages transactional data sourced from the eCommerce platform to establish a robust framework for categorizing users into high-risk and low-risk segments. This initiative involves identifying pertinent predictors of default, selecting relevant features, and constructing predictive models to assess risk probabilities. Ultimately, the model aims to compute credit scores, determine optimal loan amounts, and recommend suitable durations, thereby facilitating informed lending decisions and risk management strategies at Bati Bank.

# Objective
  - Define a proxy variable to categorize users as high risk (bad) or low risk (good).
  - Identify observable features that are good predictors of default.
  - Develop a model to assign risk probability for new customers.
  - Create a credit scoring model from risk probability estimates.
  - Predict the optimal loan amount and duration for each customer.

# Methodologies

1. Exploratory Data Analysis (EDA):

  - Understand the dataset structure.
  - Compute summary statistics.
  - Visualize numerical and categorical feature distributions.
  - Analyze feature correlations.
  - Identify missing values and outliers.
2. Feature Engineering:

  - Create aggregate features (e.g., total transaction amount, average transaction amount).
  - Extract features (e.g., transaction hour, day, month).
  - Encode categorical variables using one-hot and label encoding.
  - Handle missing values through imputation or removal.
  - Normalize/standardize numerical features.
3. Default Estimator and WoE Binning:

  - Construct a default estimator using RFMS (Recency, Frequency, Monetary, Seasonality) formalism.
  - Classify users as good or bad based on RFMS scores.
  - Perform Weight of Evidence (WoE) binning.
4. Modeling:

  - Split the data into training and testing sets.
  - Select models (e.g., Logistic Regression, Decision Trees, Random Forest, Gradient Boosting Machines).
  - Train and tune models using techniques like Grid Search and Random Search.
  - Evaluate models using metrics such as accuracy, precision, recall, F1 score, and ROC-AUC.

# Task Steps

**1. Task 1 - Understanding Credit Risk:**

  - Study credit risk concepts and definitions.
  - Review key references and guidelines (Basel II Capital Accord, credit risk articles).

**2. Task 2 - Exploratory Data Analysis (EDA):**

  - Load the dataset and examine its structure.
  - Calculate summary statistics for numerical features.
  - Visualize distributions of numerical and categorical features.
  - Perform correlation analysis.
  - Identify and handle missing values.
  - Detect and address outliers.

**3. Task 3 - Feature Engineering:**

  - Aggregate features like total, average, and standard deviation of transaction amounts per customer.
  - Extract temporal features such as transaction hour, day, month, and year.
  - Encode categorical variables using appropriate techniques.
  - Handle missing values through imputation or removal.
  - Normalize and standardize numerical features.

**4. Task 4 - Default Estimator and WoE Binning:**

  - Develop a default estimator based on RFMS formalism.
  - Assign users into good and bad categories.
  - Implement WoE binning to transform categorical variables.

**5. Task 5 - Modeling:**

  - Split the dataset into training and testing sets.
  - Select and train multiple models.
  - Tune hyperparameters to optimize model performance.
  - Evaluate models using relevant metrics to select the best-performing model.


# Author: Atnabon Deressa