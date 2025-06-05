# Credit Card Fraud Detection
**TASK 2 – Machine Learning Internship at CODSOFT**

# Objective
Develop a machine learning model to identify fraudulent credit card transactions using the [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection).

# Dataset
- **Dataset**: [Credit Card Fraud Detection dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection).
- **Description**: Contains 284,807 transactions, with only 492 labeled as fraud (0.172% of all transactions), making it highly unbalanced.
- **Features**: 30 anonymized features resulting from PCA transformation, along with 'Time' and 'Amount' columns. The target variable is 'Class' (1 for fraud, 0 for legitimate).

# Techniques Used
- **Data Preprocessing**:
  - Loaded dataset using pandas.
  - Dropped unnecessary columns.
  - Encoded categorical variables using LabelEncoder.
  - Handled missing values by filling numerical NaNs with the median and categorical NaNs with 'Unknown'.
- **Modeling**:
  - Split data into training and testing sets (70% train, 30% test).
  - Trained a Logistic Regression model on the training data.
- **Evaluation**:
  - Evaluated model performance using accuracy score, confusion matrix, and classification report.

# Results
- **Accuracy**: Approximately 99.6% on the test set.
- **Confusion Matrix**:


Files
 - Credit_Card_Fraud_Detection.ipynb – Full code in Colab
 - README.md – Project description (attached with dataset link)

