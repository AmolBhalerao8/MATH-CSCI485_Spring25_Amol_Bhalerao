Project Title : 
Recursive Feature Elimination (RFE) with Linear Regression

Description
This project implements Recursive Feature Elimination (RFE) using Linear Regression to identify the most significant features in predicting diabetes progression. The analysis is based on the Diabetes dataset from sklearn.datasets.load_diabetes().

The project covers:
 Exploratory Data Analysis (EDA)
 Building a Baseline Linear Regression Model
 Applying RFE for Feature Selection
 Visualizing Feature Importance & R² Scores
 Interpreting Selected Features

Dataset
The dataset consists of 10 features representing patient attributes and a target variable measuring diabetes progression after one year.

Features:

age: Age of the patient
sex: Gender
bmi: Body Mass Index
bp: Average blood pressure
s1 - s6: Blood serum measurements
Target Variable:

A continuous value representing diabetes progression.
Installation & Requirements
Ensure you have Python 3.x installed along with the required libraries.

Install dependencies using:
pip install numpy pandas scikit-learn matplotlib

Usage
Clone the repository:
git clone https://github.com/yourusername/MATH-CSCI485_Spring25_Amol/Assignment_1.git
cd Assignment_1
Run the Jupyter Notebook (RFE_LinearRegression.ipynb)

Open Jupyter Notebook:
Execute the cells in RFE_LinearRegression.ipynb.
Expected Outputs:
 Linear Regression Model Performance (R² Score)
 Feature Importance Ranking
 RFE Iterations & Selected Features
 Graphs: R² Score vs. Number of Features Retained

Project Structure
Assignment_1/
│── Source_code.ipynb                                  # Jupyter Notebook with full implementation    
│── Assignment1_Screenshot_output.pdf                  # Folder containing graphs & outputs  
│── README.md                                          # Project documentation  
│── report.pdf                                         # Final report

Results & Key Insights
Top 3 Features Identified: bmi, s1, s5
BMI is the most significant predictor of diabetes progression.
Cholesterol & LDL (s1, s5) play a crucial role in disease severity.
Age and blood pressure were less important compared to metabolic factors.
