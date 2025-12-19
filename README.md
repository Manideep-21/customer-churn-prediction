# Customer Churn Prediction using Machine Learning

This project focuses on analyzing customer behavior and predicting customer churn using machine learning techniques. The goal is to identify customers who are likely to leave the service, helping businesses take proactive retention measures.

---

## Project Overview
- **Problem Type**: Binary Classification
- **Target Variable**: Churn
- **Techniques Used**: Data Analysis, Data Preprocessing, Machine Learning
- **Framework**: Python (scikit-learn)

---

## Exploratory Data Analysis
- Analyzed churn distribution
- Studied relationships between churn and key features such as contract type, tenure, and monthly charges
- Identified important patterns influencing customer churn

---

## Data Preprocessing
- Handled categorical variables using encoding techniques
- Removed irrelevant features
- Applied feature scaling
- Split data into training and testing sets

---

## Model Building & Selection
The following models were trained and evaluated:
- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Models were compared using accuracy, precision, recall, and F1-score to select the best-performing model.

---

## Results
- Random Forest achieved the best overall performance
- The model effectively identifies customers at risk of churn

---

## How to Run
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
