# Conquering Imbalance: A Machine Learning Odyssey for Fraud Detection

## Introduction
This Jupyter Notebook project focuses on tackling the challenge of fraud transaction detection using machine learning models, specifically addressing the issues related to an imbalanced dataset. The primary goal is to build a reliable fraud detection model that effectively identifies fraudulent transactions within the financial system. 

## Dataset Selection
The project begins with the selection of a dataset from Kaggle ([Dataset link](https://www.kaggle.com/datasets/chitwanmanchanda/fraudulent-transactions-data)). The dataset provides insights into real-life financial transactions, comprising a massive 6,362,620 rows. However, only 8,213 rows pertain to fraudulent transactions, representing a mere 0.12% of the dataset.

## Key Features of the Dataset
- **step:** Maps a unit of time in the real world, with 1 step equivalent to 1 hour.
- **type:** Transaction types include CASH-IN, CASH-OUT, DEBIT, PAYMENT, and TRANSFER.
- **amount:** The transaction amount in local currency.
- **nameOrig:** Customer initiating the transaction.
- **oldbalanceOrg:** Initial account balance before the transaction.
- **newbalanceOrig:** New balance after the transaction.
- **nameDest:** Recipient of the transaction.
- **oldbalanceDest:** Initial recipient's balance before the transaction.
- **newbalanceDest:** New recipient's balance after the transaction.
- **isFraud:** Transactions made by fraudulent agents within the simulation.
- **isFlaggedFraud:** Identifies illegal attempts, such as transferring more than $200,000 in a single transaction.

## Challenges and Objectives
The main challenge lies in the dataset's significant imbalance, where the majority of transactions are non-fraudulent. The project's objectives include addressing this imbalance, creating a model capable of accurately detecting fraudulent transactions, and improving financial security.

## Key Highlights

1. **Data Preprocessing:** To address dataset imbalance, we employed resampling techniques such as undersampling and oversampling.
2. **Feature Engineering:** Detailed exploration of financial transactions to create relevant features.
3. **Machine Learning Models:** Evaluated multiple models including Random Forest, Gradient Boosting, XGBoost, LightGBM, and Logistic Regression.
4. **Hyperparameter Tuning:** Fine-tuned model parameters to optimize performance.
5. **Evaluation Metrics:** Focused on F1-score, recall, and accuracy to assess fraud detection performance.

## Project Impact
The project aims to enhance financial security by optimizing machine learning models and managing imbalanced datasets. We believe this approach will protect the interests of all parties involved, enhancing the system's capacity to identify and prevent fraudulent transactions.

## Conclusion
This project is a testament to our dedication to using machine learning and data science to solve real-world problems. Through advanced technology, data preparation, and comprehensive model evaluation, we aim to make a significant contribution to the fight against financial fraud, creating a more reliable and secure financial system for everyone.

## Technologies Used
- Python
- Jupyter Notebook
- Libraries: NumPy, Pandas, Matplotlib, Seaborn, Scikit-Learn, XGBoost, LightGBM

## Getting Started
- Clone this repository to your local machine.
- Install the required libraries mentioned in the Jupyter Notebook.

## Acknowledgments
- Kaggle for providing the dataset used in this project.
