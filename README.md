# House Prices Prediction

## Overview

This repository contains a Jupyter Notebook focused on predicting house prices using machine learning models. The analysis includes data exploration, preprocessing, feature engineering, and the application of two different regression models: Linear Regression and XGBoost.

## Table of Contents

- [Data Overview](#data-overview)
- [Analysis Steps](#analysis-steps)
- [Key Findings](#key-findings)
- [Model Performance](#model-performance)
- [Conclusion](#conclusion)
  
## Data Overview

The dataset used in this analysis is the House Prices dataset, which includes various features related to residential properties. The goal is to predict the sale prices of these properties based on the given features.

## Analysis Steps

1. **Exploratory Data Analysis (EDA):** Understanding the dataset, visualizing distributions, and identifying patterns in the data.

2. **Preprocessing:** Handling missing values, removing redundant features, addressing outliers, and transforming the target variable for better model performance.

3. **Feature Engineering:** Creating new features to enhance the predictive capabilities of the models.

4. **Modeling:** Implementing two regression models - Linear Regression and XGBoost - and evaluating their performance.

## Key Findings

- **Important Features:** Identified key features influencing house prices, such as total square footage and overall property quality.

- **Model Comparison:** Explored the performance of Linear Regression and XGBoost, considering factors beyond RMSE.

- **Feature Importance Discrepancies:** Observed differences in feature importance between the two models.

## Model Performance

- **Linear Regression RMSE:** _(insert value)_
- **XGBoost RMSE:** _(insert value)_

## Conclusion

**Key Findings:**

* **Important Features:**

    * The most crucial factors influencing house prices were identified as the total square footage (TotalSF) and the overall quality (OverallQual) of the property. These findings align with common expectations in real estate, emphasizing the significance of size and quality in determining property values.
    
* **Model Performance:**

    * Linear Regression exhibited a slightly better Root Mean Squared Error (RMSE) compared to XGBoost. However, the choice between models goes beyond RMSE and involves considering additional factors.

* **Distribution of Predicted Prices:**

    * The distribution of predicted prices with XGBoost looked closer to the actual prices, indicating that the model captured complex relationships and patterns more effectively.

* **Feature Importance:**

    * Notably, there were discrepancies in feature importance between Linear Regression and XGBoost. Linear Regression emphasized features differently, which could be attributed to its assumption of linear relationships.
