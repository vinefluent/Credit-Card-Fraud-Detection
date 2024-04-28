# Credit Card Fraud Detection Data Analysis 🛡️💳

## Overview ℹ️
This repository contains a data analysis project focused on credit card fraud detection. The aim of this project is to explore a dataset, develop insights, and build predictive models to detect fraudulent transactions.

## Dataset 📊
The dataset used in this project contains transactions made by credit cards in September 2013 by European cardholders. It consists of a highly unbalanced class distribution, with only 492 frauds out of 284,807 transactions. The dataset features 30 numerical input variables derived from PCA transformations due to privacy concerns. Additionally, it includes the 'Time' and 'Amount' features, representing the seconds elapsed between each transaction and the first transaction in the dataset and the transaction amount, respectively.

## Files 📁
- `credit_card_fraud_detection.ipynb`: Jupyter Notebook containing the data analysis and modeling process.
- `creditcard.csv`: The dataset in CSV format.

## Analysis 📈
1. **Data Exploration:** Exploring the dataset to understand its structure, distributions, and relationships between variables.
2. **Data Preprocessing:** Handling missing values, scaling features, and addressing the class imbalance.
3. **Feature Engineering:** Extracting meaningful features or transforming existing ones to improve model performance.
4. **Model Development:** Building machine learning models to predict fraudulent transactions.
5. **Model Evaluation:** Assessing the performance of the models using appropriate metrics such as accuracy, precision, recall, and F1-score.
6. **Results Interpretation:** Interpreting the results to gain insights into the factors influencing fraud detection.

## Technologies Used 💻
- Python
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Setup 🛠️
To run the Jupyter Notebook, you need to have Python installed along with the required libraries. You can install the dependencies using the following command:

```
pip install -r requirements.txt
```

## Usage 🚀
1. Clone the repository:
```
git clone https://github.com/vinefluent/Credit-Card-Fraud-Detection.git
```
2. Navigate to the project directory:
```
cd Credit-Card-Fraud-Detection
```
3. Launch Jupyter Notebook:
```
jupyter notebook credit_card_fraud_detection.ipynb
```
4. Follow the steps outlined in the notebook to explore the data and run the analysis.
