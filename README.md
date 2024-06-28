# Retail Sales Prediction using Machine Learning
This project focuses on building a machine learning model to accurately predict retail sales for XYZ, a leading drugstore chain.

## Problem Statement
XYZ struggles with inconsistent sales forecasts across its 3,000 stores.

## Project Objective
Develop a machine learning model to accurately predict sales, improving decision-making and efficiency.

## Project Scope
  - Utilize historical sales data from 1,115 stores, considering factors like promotions, holidays, and store locations.
  - Data Sources:
        1. Salesdata.csv: Over 1 million rows of historical sales data.
        2. Store.csv: Detailed information about each of the 1,115 stores.
    
## Methodology:
  - Data Exploration and Visualization: Explore the dataset, identify key features, and visualize relationships between variables.
  - Data Preprocessing: Merge datasets, handle data errors, and manage missing values.
  - Feature Engineering: Create new features and transform existing ones to improve model performance.
  - Feature Selection: Identify and select relevant features using domain knowledge and feature importance techniques.
  - Model Building: Train and evaluate various machine learning models including Linear Regression, Decision Tree, Random Forest, and XGBoost.
  - Model Evaluation: Assess model performance using metrics like MAE, MSE, RMSE, MAPE, R², and Accuracy.
  - Model Selection: Choose the best performing model based on evaluation results and domain insights.
  - Feature Importance Analysis: Identify the most influential features for sales prediction.
  - Conclusion and Recommendations: Provide insights and recommendations for XYZ based on the model results.
    
## Key Findings:
  - Random Forest emerged as the best performing model, achieving 91.5% accuracy and generalization.
  - Key features impacting sales include: Customers, CompetitionDistance, StoreType_d, and Promo.
  - The model highlights the need for strategic customer engagement, competitive store locations, targeted marketing efforts, and well-planned promotions.
