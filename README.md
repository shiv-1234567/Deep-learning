# Credit Card Churn Prediction

## Project Overview
This project focuses on predicting customer churn for a credit card company using an Artificial Neural Network (ANN). The goal is to identify customers who are likely to leave, enabling businesses to take proactive retention measures.

## Dataset Glimpse
The dataset contains 10,000+ customer records with features such as:

- **Customer Demographics:** Age, Gender, Geography
- **Account Information:** Credit Limit, Balance, Tenure
- **Usage Patterns:** Transaction history, Number of products, Credit score
- **Churn Indicator:** Whether the customer left the service (0 = No, 1 = Yes)

Example of a few rows:
<img width="1251" height="482" alt="image" src="https://github.com/user-attachments/assets/7e8558b9-ec63-4872-9397-1115ff0e434e" />


| CustomerID | Age | Gender | Geography | Balance | NumOfProducts | CreditScore | Exited |
|------------|-----|--------|-----------|---------|---------------|------------|-------|
| 15634602   | 42  | Female | France    | 50000   | 2             | 650        | 1     |
| 15647311   | 41  | Male   | Spain     | 60000   | 1             | 720        | 0     |

## Project Objective
The project aims to:

1. Preprocess the dataset by handling categorical variables, feature scaling, and normalization.
2. Train an Artificial Neural Network to predict customer churn.
3. Evaluate the model's performance using training and validation accuracy.
4. Provide actionable insights for customer retention strategies based on predicted churn risk.

## Methodology
- Implemented an **Artificial Neural Network (ANN)** using **TensorFlow/Keras**.
- Optimizer: **Adam**
- Loss function: **Binary Cross-Entropy**
- Training: 10 epochs
- Input features were preprocessed with scaling and encoding to ensure uniformity.

## Results
- **Training Accuracy:** 84.07%
- **Validation Accuracy:** 84.69%
- The model demonstrates robust predictive performance for real-world churn analytics.




## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/shiv-1234567/Deep-learning/tree/main

<img width="845" height="373" alt="image" src="https://github.com/user-attachments/assets/57565087-22cb-49f7-b562-b9b7a409fd73" />



Technologies Used

Python

TensorFlow/Keras

Pandas, NumPy

Scikit-learn for preprocessing

Author

Shivendra Prasad Mishra | MSc Mathematics, IIT Delhi
