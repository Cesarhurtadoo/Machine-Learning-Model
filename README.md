
# Credit Card Fraud Detection

This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset used contains anonymized credit card transactions labeled as fraudulent or valid.

## Overview

The repository contains a Python script (`credit_card_fraud_detection.py`) that implements a Random Forest classifier to classify transactions as fraudulent or valid based on various features such as transaction amount, time, and anonymized numerical features (`V1` to `V28`).

## Dataset

The dataset (`creditC.csv`) used in this project consists of 284,807 transactions. Each transaction record includes features such as time, amount, and anonymized numerical features (`V1` to `V28`). The target variable `Class` indicates whether the transaction is fraudulent (1) or valid (0).

## Usage

To run the script, ensure you have Python installed on your system. Then, execute the script using the following command:

```bash
python credit_card_fraud_detection.py
```

The script will train a Random Forest classifier on the dataset and evaluate its performance in detecting fraudulent transactions.

## Dependencies

- Python 3.x
- NumPy
- pandas
- Matplotlib
- Seaborn
- scikit-learn

You can install the dependencies using the following command:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```

## Results

The Random Forest classifier achieved an accuracy of approximately 99.96% and a precision of approximately 97.47% in detecting fraudulent transactions on the test set.

## Conclusion

This project demonstrates the effectiveness of machine learning techniques, specifically Random Forest classification, in detecting fraudulent credit card transactions. The high accuracy and precision achieved by the model suggest its potential utility in real-world applications for fraud detection.

