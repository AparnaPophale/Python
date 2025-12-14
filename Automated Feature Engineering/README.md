# Automated Feature Engineering Workflow

This project demonstrates automated feature engineering for a simple regression problem.
It uses a preprocessing pipeline with:

- OneHotEncoder for categorical variables
- Passthrough for numeric features
- RandomForest for prediction

## Steps:

1. Load dataset
2. Split into training/testing sets
3. Automatically transform numerical + categorical features
4. Train RandomForest regression model
5. Evaluate using RMSE

## Files:

- automated_feature_engineering.ipynb
- sales.csv
- requirements.txt

## Future Scope:

- Incorporate advanced feature engineering such as interaction terms, polynomial features, and domain-specific ratios to enhance model performance.
- Experiment with additional regression models (Random Forest, Gradient Boosting, XGBoost) and compare results using cross-validation.
- Automate the entire pipeline by integrating feature generation, model training, and evaluation into a reusable, production-ready workflow.

### License
© 2025-2026 APARNA S POPHALE. All rights reserved.

This repository is public for viewing and educational purposes only.
Unauthorized reuse, modification, or redistribution of any part of this project
requires explicit written permission from the author.



