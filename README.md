# House-Price-Prediction
**Data Analysis | Machine Learning | Python | Predictive Modeling**

## Project Overview
Used the **Ames Housing dataset from Kaggle** to analyze factors associated with residential home prices and develop machine learning models to predict sale prices.

## Project Objective
- Identify property characteristics strongly associated with sale price
- Compare regression models based on prediction performance
- Generate predictions for previously unseen properties

## Data Preparation
- Examined dataset structure, data types, dimensions, and missing values
- Handled missing numerical values using median imputation
- Converted categorical variables using one-hot encoding
- Separated **SalePrice** from the predictor variables
- Prepared the original Kaggle test dataset for final predictions

## Exploratory Data Analysis
Analyzed relationships between property characteristics and sale prices, focusing on:
- **Above-ground living area (`GrLivArea`)**
- **Overall quality (`OverallQual`)**
- Correlations between numerical features and sale price
- Distribution of home sale prices

### Key Findings
- Larger living areas generally corresponded with higher sale prices.
- Overall quality showed a strong positive relationship with sale price.
- Higher-quality homes consistently tended to sell for more.

## Model Development
Compared two regression models:
1. **Linear Regression**
2. **Random Forest Regression**

The Kaggle training data was divided into an **80/20 training and validation split**, while the original Kaggle test dataset remained separate for final predictions.

## Model Evaluation
Models were evaluated using **Root Mean Squared Error (RMSE)**, where a lower score indicates better predictive performance.

The models were compared using the same validation data to determine which approach performed better.

## Feature Importance
Used Random Forest feature importance to examine which property characteristics contributed most strongly to the model's predictions.

## Final Predictions
The project generated predicted sale prices for the original Kaggle test dataset and combined those predictions with property IDs for potential Kaggle evaluation.

## Conclusion
This project demonstrated an end-to-end predictive analytics workflow, including **data cleaning, exploratory analysis, feature analysis, regression modeling, model evaluation, and prediction**. The analysis identified overall quality and living area as important factors associated with residential home prices.

## Tools & Technologies
**Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn | Kaggle**

## Skills Demonstrated
**Data Cleaning • Exploratory Data Analysis • Data Visualization • Feature Selection • Feature Engineering • Regression Modeling • Random Forest • Model Evaluation • RMSE • Feature Importance • Predictive Analytics**
