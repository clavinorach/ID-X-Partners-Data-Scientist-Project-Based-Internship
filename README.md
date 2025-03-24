# ID-X-Partners-Data-Scientist-Project-Based-Internship

# Credit Risk Prediction - Data Science Internship Project

This project is a part of the **Data Scientist Project-Based Internship** at **ID/X Partners**. It focuses on building a machine learning model for **credit risk prediction** to help financial companies identify high-risk borrowers. The goal is to improve decision-making and reduce losses by accurately predicting loan defaults.

## Project Overview

The **Credit Risk Prediction** project aims to enhance the accuracy of credit risk assessments in the multi-finance industry, where assessing the ability of borrowers to meet their financial obligations is crucial. The project involves analyzing historical loan data to predict the likelihood of default, with features such as loan amount, interest rate, duration, credit history, and key dates.

## Technologies Used

- **Python**
- **Pandas** (for data manipulation)
- **NumPy** (for numerical operations)
- **Matplotlib/Seaborn** (for data visualization)
- **Scikit-Learn** (for machine learning models)
- **XGBoost**, **Random Forest**, **Logistic Regression** (for classification models)
- **SMOTE** (for handling class imbalance)

## Dataset Description

The dataset contains historical loan data, including information on:
- Loan amounts
- Interest rates
- Loan terms (36 months, 60 months)
- Employment length
- Credit history
- Other key financial and demographic data

The dataset includes over **466,000 rows** and **75 features**, some of which contain missing values that were cleaned and imputed during data preprocessing.

## Project Steps

1. **Data Cleaning**  
   Handling missing values, formatting columns, and preparing the dataset for modeling.  
   - Columns such as `term`, `emp_length`, and `date-related` fields were cleaned for better data quality.

2. **Exploratory Data Analysis (EDA)**  
   - Identified patterns in loan performance based on attributes like loan term, payment delays, and borrower credit history.
   - Visualized the data to understand trends, such as loan durations and default rates.

3. **Data Preprocessing and Feature Engineering**  
   - Used **SMOTE** (Synthetic Minority Over-sampling Technique) to balance the dataset due to the class imbalance.
   - Derived new features such as the "Months Since Earliest Credit Line" for improved model prediction.

4. **Modeling**  
   - Built and evaluated multiple models:
     - **Logistic Regression** - Accuracy: 85.02%
     - **Random Forest** - Accuracy: 95.40%
     - **XGBoost** - Accuracy: 94.31%
   
5. **Model Evaluation**  
   - Evaluated models using metrics like **precision**, **recall**, and **F1-score**.
   - **XGBoost** performed the best with the lowest false negatives and false positives.

## Key Findings

- The majority of loans with high default rates were issued between 2010-2014, especially in 2013-2014.
- Loan duration and credit history were significant factors influencing default predictions.
- **XGBoost** was identified as the most accurate and reliable model for credit risk prediction.

## Project Links

- [Project Video Presentation](https://drive.google.com/file/d/1Imup2J2hzUbaqTETFa0y-7Zw9N8dh36k/view?usp=sharing)
- [Project Code in Google Colab](https://colab.research.google.com/drive/1D-yVuaA7BO5tUTIMVfaBE4q4KVlbEBBh?usp=sharing)

## Authors

- **Clavino Ourizqi Rachmadi** – Data Scientist Intern  
  [LinkedIn](http://linkedin.com/in/clavinorachmadi) | [Email](mailto:clavinorachm@gmail.com)
