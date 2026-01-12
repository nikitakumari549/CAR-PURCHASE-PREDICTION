
# Car Purchase Prediction Machine Learning Project

This project focuses on predicting whether a potential customer will purchase a car based on their demographic and financial profile. By analyzing factors like annual salary and net worth, the model helps businesses understand purchasing behavior to optimize marketing efforts.

## Project Overview

The primary goal is to take customer data and determine if a purchase is likely. While the raw dataset contains a "Car Purchase Amount" target, this project treats the task as a **binary classification problem** (1 for purchase, 0 for no purchase) to better target potential buyers.

## Dataset Description

The dataset includes the following attributes for each potential customer:

* **Customer Information:** Full Name and E-mail.


* **Personal Information:** Country of residence, Gender, and Age.


* **Financial Information:** Annual Salary, Credit Card Debt, and Net Worth.


* **Target Variable:** Car Purchase Amount (transformed for classification).



## Technical Workflow

The project follows a standard machine learning pipeline:

1. **Data Preprocessing & EDA:** Handling missing values, outliers, and inconsistencies while exploring patterns through visualization.


2. **Correlation Analysis:** Identifying relationships between independent variables to avoid multicollinearity.


3. **Feature Selection:** Selecting the most appropriate columns to train the model.


4. **Modeling:** Splitting the data into training and testing sets and applying a **Random Forest** model.


5. **Evaluation:** Using statistical measures like R-squared () to assess accuracy and generalization.



## Model Selection & Results

The **Random Forest** model was chosen because it handles complex influences from multiple financial factors like salary and net worth in a hierarchical way to yield the best results.

**Performance Metrics:**

* **Random Forest CV :** 0.9427 


* **Random Forest Test :** 0.9526 



## How to Access

* **Google Colab Notebook:** [View the code here]([https://colab.research.google.com/drive/1oYTXs-TwBzFk6SothIvwGHc2Ku9EDrOH?usp=sharing](https://colab.research.google.com/drive/1V6xjZ2p1MYh_-DmANG4LKIK1avcn6p-3?usp=sharing)).



---

**Developed by:** Nikita Kumari
