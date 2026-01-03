# Exam Score Prediction with MLP and Decision Tree

## Overview
This project predicts **students’ performance tiers** based on factors such as study habits, attendance, sleep quality, and other academic attributes using **supervised machine learning models**. Two classifiers are implemented and compared: a **Multilayer Perceptron (MLP) Neural Network** and a **Decision Tree**.

The project demonstrates a complete machine learning workflow, including data preprocessing, feature engineering, model training, evaluation, and visualization, using **Python** and **scikit-learn**.

---

## Objective
- To design and implement an end-to-end machine learning pipeline that predicts students’ academic performance tiers using behavioral and academic indicators, applying supervised learning models (MLP Neural Network and Decision Tree) to compare predictive performance, interpretability, and classification effectiveness.

---

## Data Source
- Exam_Score_Prediction.csv
- Dataset from Kaggle: [Exam Score Prediction Dataset](https://www.kaggle.com/datasets/kundanbedmutha/exam-score-prediction-dataset?resource=download)

---

## Methods & Tools

### Programming Environment
- Python 
- Jupyter Notebook

### Libraries Used

- **Data Processing:** NumPy, Pandas
- **Machine Learning:** Scikit-learn
- **Preprocessing:** StandardScaler, OneHotEncoder, ColumnTransformer
- **Models:** MLPClassifier, DecisionTreeClassifier
- **Evaluation & Visualization:** matplotlib, seaborn

---

## Workflow (End-to-End Pipeline)
1. Load the dataset and inspect data types and missing values  
2. Perform feature engineering:
   - Create the target variable `performance_tier` using score bins  
   - Map ordinal feature `sleep_quality` to numerical values  
   - Drop irrelevant columns to prevent data leakage  
3. Preprocessing:
   - Identify numerical and categorical features  
   - Apply `StandardScaler` to numerical features  
   - Apply `OneHotEncoder` to categorical features using `ColumnTransformer`  
4. Train-test split:
   - Split data into 80% training and 20% testing sets  
   - Use stratification on the target variable  
5. Model definition:
   - MLP Classifier (Neural Network)  
   - Decision Tree Classifier  
6. Model training and evaluation:
   - Train both models using pipelines (preprocessing + model)  
   - Evaluate performance using `classification_report`  
7. Visualization:
   - Plot MLP loss curve to monitor learning progress  
   - Visualize the top levels of the decision tree to interpret decision rules  
8. Confusion matrices:
   - Analyze misclassification patterns for both models  

---

## Project Structure
```text
├── exam_score_prediction.ipynb   # Complete ML workflow and visualizations
├── Exam_Score_Prediction.csv     # Dataset (Kaggle: Exam Score Prediction)
├── requirements.txt              # Python dependencies
├── README.md                     # Project documentation
└── LICENSE                       # MIT License
```

---

## Future Enhancements
- Extend analysis using advanced ensemble models such as Random Forest or XGBoost
- Incorporate additional student data (e.g., assignments, extracurricular activities)
- Perform hyperparameter tuning for improved model performance
- Explore fairness and bias considerations in educational predictions

---

## Results & Insights
- Successfully classified students into performance tiers based on behavioral and academic indicators
- Compared model behavior:
- MLP Classifier: Captures complex, non-linear relationships; learning progress monitored via loss curve
- Decision Tree: Provides interpretable decision rules for understanding feature impact
- Confusion matrices revealed strengths and weaknesses of each model in handling class imbalance and misclassification

---

## Practical Applications
- Educational data mining and learning analytics
- Early identification of students at academic risk
- Model comparison for structured tabular datasets
- Demonstration of end-to-end ML pipelines using scikit-learn

---

## How to Run the Project
1. Clone the repository: *git clone https://github.com/yourusername/your-repo-name.git*
2. Install dependencies: *pip install -r requirements.txt*
3. Open the notebook: *jupyter notebook exam_score_prediction.ipynb*
4. Run the cells sequentially to reproduce the analysis



### License
This project is licensed under the MIT License.

**Ethical Use Notice:**
This project is intended for educational, research, and professional learning purposes.

Misrepresentation of authorship or deceptive use is unethical. Attribution is required under the MIT License.

