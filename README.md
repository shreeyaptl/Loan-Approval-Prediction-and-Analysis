# Loan-Approval-Prediction-and-Analysis
Project Description

This project focuses on loan approval prediction and analysis using statistical methods and machine learning. The dataset (loan_data.csv) contains demographic, financial, and credit-related information about applicants, along with their loan approval status.
The project is structured into four main parts:

1. Data Exploration & Preprocessing
Checked for missing values, data types, and summary statistics.
Explored variance across numeric columns.
Visualized distributions of numeric and categorical features using histograms, boxplots, and bar charts.
Generated a correlation heatmap and scatterplots to identify relationships between income, loan amount, and loan approval.

2. Hypothesis Testing
Tested whether income significantly influences loan approval using a t-test.
Analyzed the impact of credit score on loan approval.
Evaluated whether loan intent (purpose) affects approval rates via a chi-square test.
Investigated potential gender bias in loan approvals.
Results showed statistically significant influences for some factors (income, credit score, loan intent), while others (gender) were less significant.

3. Feature Engineering & Data Transformation
Applied label encoding for binary categorical variables.
Applied one-hot encoding for multi-class categorical variables such as education, home ownership, and loan intent.
Standardized numerical variables (e.g., income, age, loan amount, credit score) for balanced model performance.
Split the dataset into training (70%) and testing (30%) sets with stratification to preserve target distribution.

4. Model Development & Evaluation
Implemented three machine learning models:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Compared performance metrics including accuracy, precision, recall, F1-score, and confusion matrices.
Logistic Regression provided interpretability, while Random Forest achieved stronger predictive performance with balanced accuracy.

Key Findings
Income and credit score are significant predictors of loan approval.
Loan intent also influences approval decisions, while gender bias was not strongly evident.
Among tested models, Random Forest delivered the best balance of accuracy and robustness.

Tools & Libraries
Python: Pandas, NumPy, Matplotlib, Seaborn, SciPy
Machine Learning: scikit-learn (Logistic Regression, Decision Tree, Random Forest)
Statistical Tests: t-test, chi-square
