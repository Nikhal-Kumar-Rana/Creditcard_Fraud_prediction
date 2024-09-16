I have completed the Assesment for making CreditCard_fraud_prediction system. Hence I tried to make an api and deploy it as well .But the problem i faced is that my Main (Random_forestClassifier.pkl) file was not uploading 
as some how it's size exceeded 500mb, I don't know how it was too large in size . I have that file saved on my pc but was not able to upload it here on github.


# Credit Card Fraud Detection System
### Overview
This project focuses on detecting fraudulent credit card transactions using machine learning techniques. By analyzing patterns in the data, the system can identify potentially fraudulent activities in real-time, helping to minimize losses for financial institutions and protect consumers.

### Features
#### Data Preprocessing:

Handled categorical data using label encoding and reverse mapping to retain original data interpretations.
Managed missing values and cleaned the dataset for optimal model performance.
#### Class Imbalance Handling:

#### Used SMOTE (Synthetic Minority Over-sampling Technique) to address class imbalance, ensuring that the model can effectively detect fraud cases, which are typically rare in the dataset.
#### Machine Learning Models:

Deployed a variety of machine learning classifiers:
XGBoost
Random Forest
Gradient Boosting
AdaBoost
Logistic Regression
These models were trained and evaluated using various metrics to select the most effective model for fraud detection.
### Model Evaluation:

Performance metrics used for evaluation include:
Accuracy
Precision
Recall
F1-Score
Deployment:

The model was deployed using a Flask API, allowing real-time prediction of fraudulent transactions.
The system is designed to be scalable and deployable on cloud services such as Heroku, AWS Lambda, or Google Cloud.
### Technologies Used
Programming Languages: Python
#### Libraries:
pandas, NumPy for data manipulation 
scikit-learn for machine learning algorithms
Flask for API deployment
XGBoost for boosting model
SMOTE for handling class imbalance
Flask for API development
