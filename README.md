# Loan Approval Prediction

## Project Overview
This project aims to predict loan approval using machine learning techniques. It involves data preprocessing, exploratory data analysis (EDA), and model training. The dataset consists of various features related to applicants, including income, education, and credit history.

## Dataset
The dataset contains information about loan applicants, including:
- **Loan_ID**: Unique identifier for a loan application.
- **Gender**: Male or Female.
- **Married**: Marital status of the applicant.
- **Dependents**: Number of dependents.
- **Education**: Graduate or Not Graduate.
- **Self_Employed**: Whether the applicant is self-employed.
- **ApplicantIncome**: Income of the applicant.
- **CoapplicantIncome**: Income of the co-applicant.
- **LoanAmount**: Loan amount requested.
- **Loan_Amount_Term**: Term of the loan in months.
- **Credit_History**: Whether the applicant has a good credit history.
- **Property_Area**: Urban, Semiurban, or Rural.
- **Loan_Status**: Approved (Y) or Not Approved (N) (Target Variable).

## Project Steps
1. **Data Preprocessing**
   - Handling missing values.
   - Encoding categorical variables.
   - Normalizing numerical features.
2. **Exploratory Data Analysis (EDA)**
   - Visualization of feature distributions.
   - Correlation analysis between variables.
3. **Splitting Data**
   - Splitting into training and testing sets (80% training, 20% testing).
4. **Model Training & Evaluation**
   - Training machine learning models such as Logistic Regression, Decision Trees, and Random Forest.
   - Evaluating model performance using accuracy and other metrics.

## Requirements
To run this project, install the following dependencies:
```
pandas
numpy
matplotlib
seaborn
sklearn
```
Install dependencies using:
```
pip install -r requirements.txt
```

## Usage
Run the Python script to preprocess the dataset and train the model:
```
python loan_prediction.py
```

## Results
The trained models will predict loan approval based on applicant details. The accuracy and other performance metrics will be displayed at the end of execution.

## Contributing
Feel free to contribute by improving data processing, model performance, or adding new features!


