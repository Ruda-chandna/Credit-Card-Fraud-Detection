# Credit-Card-Fraud-Detection
This project uses machine learning models to detect fraudulent credit card transactions. By analyzing real transaction data, the notebook demonstrates end-to-end fraud detection: from data cleaning and visualization to model building, evaluation, and prediction.

## What the Project Does

- Loads and explores a large dataset of credit card transactions.
- Handles class imbalance (very few frauds compared to normal transactions).
- Applies machine learning algorithms to differentiate between fraudulent and legitimate transactions.
- Evaluates model performance using accuracy, precision, recall, F1 score, and ROC-AUC.
- Visualizes results and provides actionable insights.

## Technologies Used

- **Python** (Google Colab Notebook)
- **Pandas**, **NumPy** for data manipulation
- **Matplotlib**, **Seaborn** for visualization
- **Scikit-learn** for machine learning models and evaluation
- **Imbalanced-learn** (optional) for SMOTE and over/undersampling

## Key Features

- Data preprocessing and exploratory data analysis
- Addressing imbalanced datasets (fraud vs. non-fraud)
- Use of classification algorithms such as Logistic Regression, Random Forest, Decision Tree, and others
- Performance metrics for evaluating model effectiveness
- Clear plots for analysis and reporting

## Getting Started

1. Download or clone the repository.
2. Upload your `creditcard.csv` dataset to the notebook environment.
3. Open and run the `Credit Card Fraud Detection.ipynb` notebook in Google Colab.

## Dataset

- The [creditcard.csv](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset contains European credit card transactions (anonymized) with labels for fraud or legitimate activity.

## Results

- The models trained are able to detect the majority of fraudulent transactions with high precision and recall, while minimizing false positives.

## Author

- Rudra Chandna
