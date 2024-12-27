# Loan Status Prediction Project
This repository contains the code and resources for analyzing and predicting loan status using machine learning techniques. The project focuses on performing data preprocessing, exploratory data analysis (EDA), feature engineering, and implementing classification algorithms to predict loan status effectively.
## Table of contents
- [Introduction](#Introduction)
- [Dataset Description](#Dataset-Description)
- [Project Workflow](#Project-Workflow)
- [Technologies Used](#Technologies-Used)
- [Installation](#Installation)
- [Usage](#Usage)
- [Results](#Results)
- [Contributing](#Contributing)
- [License](#License)

---

## Introduction
The objective of this project is to predict whether a loan application will be approved or not based on various factors. By analyzing historical data, we aim to provide insights into key factors affecting loan approval and build a machine learning model to automate this decision-making process.

## Data Description
The dataset includes features such as:
 - `pdays`: Number of days since the client was last contacted.
 - `previous`: Number of contacts performed before the current campaign.
 - `no_previous_contact`: Binary feature indicating whether there were previous contacts.
 - `poutcome_success`: Binary feature indicating the success of the previous marketing campaign.

Other features include client demographics, loan details, and historical interactions. The target column is `Loan_Status_label`, which indicates loan approval status.

## Project Workflow
1. **Data Preprocessing**:
   - Understanding the data
   - Handling missing values.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzing distributions of key variables.
   - Visualizing correlations and dependencies between features.
3. **Feature Engineering**:
   - Selecting and transforming relevant features.
4. **Model Implementation**:
   - Building and evaluating models (such as., Logistics Regression, SVM, Decision Tree, KNN).
   - Hyperparameter tuning for optimal performance.
5. **Model Evaluation**:
   - Metrics used: Accuracy, Precision, Recall, F1-score.
   - Analyzing feature importance.

 ## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn (for data visualization)
- Scikit-learn (for machine learning)

## Installation

## Usage
1. Open the Jupyter Notebook file Pregrad_Major_Project.ipynb.
2. Follow the steps in the notebook to:
   - Preprocess and analyze the dataset.
   - Train and evaluate machine learning models.
3. View the results and insights.
