# Credit Card Fraud Detection Project

## Overview

Welcome to the Credit Card Fraud Detection project! As a passionate engineering student and lead project manager on the credit card fraud detection team for Aggie Data Science Club. I have helped develop a system that detects fraudulent credit card transactions. This project aims to utilize machine learning techniques to identify anomalous patterns in credit card transactions and enhance the security of financial transactions.

## Project Structure

The project is structured into several key components:

1. **Data Collection:**
   - The dataset used for this project is named `creditcard.csv`. It contains features such as time, transaction amounts, and various anonymized numerical features (V1-V28).
   - The data was obtained from real credit card transactions, and the 'Class' column indicates whether a transaction is fraudulent (Class 1) or not (Class 0).

2. **Exploratory Data Analysis (EDA):**
   - The Jupyter notebook `Credit_Card_Fraud_Detection.ipynb` contains the exploratory data analysis phase. It involves importing essential libraries such as pandas, seaborn, and matplotlib, and analyzing the dataset to gain insights into its structure.

3. **Data Preprocessing:**
   - The notebook includes steps to scale the 'Time' and 'Amount' columns to bring uniformity to the feature scales. It also deals with the class imbalance in the dataset.

4. **Machine Learning Model:**
   - XGBoost, a popular machine learning algorithm, is employed for building the fraud detection model. The model is trained on an upsampled dataset to handle the class imbalance.

5. **Model Evaluation:**
   - The notebook evaluates the model using standard machine learning metrics such as accuracy, precision, recall, F1 score, and the Area Under the Precision-Recall Curve (AUC-PRC).

## Getting Started

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/aniketshirodkar/CreditCardFraudDetection.git

2. **Go to Kaggle's Credit Card Fraud Detection dataset page:**
   - [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

3. **Download the `creditcard.csv` file:**

4. **Place the downloaded `creditcard.csv` file in the project directory:**
   - After downloading, move or copy the `creditcard.csv` file into the directory where you have cloned the project repository.

## Dependencies
The following Python libraries are required to run the Credit Card Fraud Detection project:

- `pandas`
- `seaborn`
- `matplotlib`
- `scikit-learn`
- `xgboost`

Install these dependencies using the following command:

```bash
pip install pandas seaborn matplotlib scikit-learn xgboost


