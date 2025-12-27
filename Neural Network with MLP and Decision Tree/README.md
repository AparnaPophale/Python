# Exam Score Prediction with MLP and Decision Tree

This project predicts students' performance tiers based on study habits, attendance, sleep quality, and other factors using **MLP (Neural Network)** and **Decision Tree** classifiers. 


## Steps:
  
1. Load dataset and inspect data types, and missing values.
2. Feature Engineering
       - Create the target variable `performance_tier` using bins:  
       - Map ordinal feature `sleep_quality` to numerical values.
       - Drop irrelevant columns to prevent data leakage.
3. Preprocessing  
   - Define numerical and categorical features.
   - Apply `StandardScaler` for numerical features.
   - Apply `OneHotEncoder` for categorical features using `ColumnTransformer`.
4. Train-Test Split  
   Split the data into training (80%) and testing (20%) sets with stratification on the target.
5. Model Definition  
   - MLP Classifier
   - Decision Tree Classifier 
6. Model Training and Evaluation
   - Train both models using a pipeline (preprocessing + model).
   - Evaluate performance with `classification_report`.
7. Visualizations 
   - MLP Loss Curve to monitor learning progress.  
   - Decision Tree visualization (top 2 levels) to understand decision rules.  
8. Confusion Matrices  
   Display confusion matrices for both models to analyze misclassification patterns.


## Files:

- exam_score_prediction.ipynb 
- Exam_Score_Prediction.csv – Dataset from Kaggle: [Exam Score Prediction Dataset](https://www.kaggle.com/datasets/kundanbedmutha/exam-score-prediction-dataset?resource=download)  
- requirements.txt

## Future Scope:

- Extend the analysis using advanced models like Random Forest or XGBoost for improved accuracy.
- Incorporate additional student data (e.g., assignments, extracurricular activities) to better predict performance.


### License
© 2025-2026 APARNA S POPHALE. All rights reserved.

This repository is public for viewing and educational purposes only.
Unauthorized reuse, modification, or redistribution of any part of this project
requires explicit written permission from the author.

