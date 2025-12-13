# Predicting Customer Churn Using Scikit-learn MLP Classifier

This project analyzes customer transaction data to predict customer churn using a Scikit-learn MLP Classifier. The workflow includes data preprocessing, feature encoding, building a model pipeline, and evaluating model performance.

It is a basic neural network project using MLPClassifier from Scikit-learn. MLP, or Multi-Layer Perceptron, is a feedforward neural network consisting of one or more hidden layers with nonlinear activation functions such as ReLU. In this project, the pipeline trains the neural network to predict customer churn, which is a typical supervised learning task on tabular data.

## Steps:

1. Load the Customer_Transactions.csv dataset from Kaggle.
2. Clean the dataset by handling missing values and formatting columns.
3. Remove leak-prone or unwanted columns.
4. Standardize numeric features using scaling.
5. Encode categorical features using OneHotEncoder.
6. Create an MLP Classifier for churn prediction.
7. Build a Scikit-learn pipeline combining preprocessing and model.
8. Split the dataset into train and test sets.
9. Fit the model to the training data.
10. Evaluate the model and calculate accuracy on the test set.


## Files:

- customer_churn.ipynb
- Customer_Transactions.csv (Dataset from Kaggle - https://www.kaggle.com/datasets/fares279/customers-transactions/data)
- requirements.txt


## Future Scope:

- The model can be enhanced by safely incorporating text data through sentiment analysis or embeddings to capture customer feedback patterns.
- Further improvements can be achieved using advanced models like XGBoost or LightGBM and hyperparameter tuning.