# Customer Churn Prediction Using Logistic Regression

## Project Description
This project uses machine learning to predict customer churn in a telecommunications company. The goal is to identify customers who may discontinue their services and help the company make informed customer retention decisions.

## Dataset
The dataset contains 7,032 customer records after data cleaning. It includes customer demographics, contract types, internet services, monthly charges, tenure, and churn status.

## Data Analysis
Exploratory data analysis was performed using Python to examine customer churn patterns. Visualizations were created to explore relationships between churn and customer characteristics.

## Machine Learning Model
A logistic regression model was developed to predict whether a customer is likely to churn. The dataset was divided into 80% training data and 20% testing data.

## Model Performance
- Accuracy: 80.38%
- Churn precision: 65%
- Churn recall: 57%
- Churn F1-score: 61%

## Key Findings
- Approximately 26.58% of customers in the cleaned dataset churned.
- Customers with month-to-month contracts showed higher churn.
- Fiber optic customers had relatively high churn.
- Customers with shorter tenure were more likely to churn.
- Higher monthly charges were associated with increased churn.

## How to Run the Project
1. Download the Jupyter notebook from this repository.
2. Open it in Google Colab or Jupyter Notebook.
3. Install the required Python libraries.
4. Upload the dataset if prompted.
5. Run the notebook cells in order to reproduce the analysis and model training.

## Dependencies
- Python
- pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn
- joblib

## Project Files
- Jupyter notebook (.ipynb): Contains the data analysis, visualizations, model training, and evaluation.
- customer_churn_model.pkl: Contains the saved trained machine learning model.
- README.md: Provides project documentation.

## Conclusion
The project demonstrates how logistic regression can help identify customers at risk of leaving a telecommunications company. The findings may help businesses develop more targeted customer retention strategies.
