# ecommerce-customer-spending-prediction
Machine Learning project using Simple and Multiple Linear Regression to predict yearly ecommerce customer spending based on session length, app usage, website usage, and membership duration using Python and Scikit-learn.
# Ecommerce Customer Spending Prediction Using Linear Regression

## 1. Project Overview

This project focuses on predicting the yearly spending of ecommerce customers using Machine Learning regression algorithms.

The project uses the **Ecommerce Customers Dataset** to understand how customer behavior and platform usage influence their yearly spending.

Two regression techniques are explored:
- Simple Linear Regression
- Multiple Linear Regression

The main objective is to build a predictive model that estimates a customer's yearly spending based on their interaction with an ecommerce platform.

## 2. Problem Statement

Ecommerce businesses need to understand customer behavior to improve their marketing strategies and business performance.

This project aims to predict the yearly amount spent by customers using different behavioral factors, such as average session length, time spent on the mobile application, time spent on the website, and membership duration.

## 3. Project Objectives

- Understand and analyze the ecommerce customer dataset.
- Perform data cleaning and preprocessing.
- Conduct Exploratory Data Analysis (EDA).
- Identify relationships between independent and dependent variables.
- Implement Simple Linear Regression.
- Implement Multiple Linear Regression.
- Evaluate model performance using regression metrics.
- Predict yearly customer spending using the trained model.

## 4. Dataset Description

**Dataset Name:** Ecommerce Customers.csv

The dataset contains 500 customer records and 8 columns.

### Dataset Features

| Column | Description |
|---|---|
| Email | Customer email address |
| Address | Customer address |
| Avatar | Customer avatar information |
| Avg. Session Length | Average session duration |
| Time on App | Time spent on mobile application |
| Time on Website | Time spent on website |
| Length of Membership | Duration of customer membership |
| Yearly Amount Spent | Total yearly spending by customer |

### Independent Variables (X)

The following four numerical features are used as input variables:

1. Avg. Session Length
2. Time on App
3. Time on Website
4. Length of Membership

### Dependent Variable (Y)

**Yearly Amount Spent**

This is the target variable that the model predicts.

## 5. Machine Learning Algorithms

### Simple Linear Regression

Simple Linear Regression is used to understand the relationship between one independent variable and one dependent variable.

Formula:

Y = b0 + b1X

### Multiple Linear Regression

Multiple Linear Regression is used to predict a dependent variable using two or more independent variables.

Formula:

Y = b0 + b1X1 + b2X2 + b3X3 + b4X4

For this project, Multiple Linear Regression uses all four numerical input features to predict yearly customer spending.

## 6. Technologies and Libraries Used

**Programming Language:**
- Python

**Libraries:**
- Pandas – Data manipulation and analysis.
- NumPy – Numerical calculations.
- Matplotlib – Data visualization.
- Seaborn – Statistical visualization.
- Scikit-learn – Machine Learning model development and evaluation.

**Development Environment:**
- Jupyter Notebook / Google Colab / VS Code

## 7. Project Workflow

The project follows these steps:

1. Import required Python libraries.
2. Load the ecommerce customer dataset.
3. Explore the dataset using Pandas.
4. Check missing values and duplicate records.
5. Perform Exploratory Data Analysis.
6. Visualize relationships using scatter plots and a correlation heatmap.
7. Select independent and dependent variables.
8. Split the dataset into training and testing sets.
9. Build a Simple Linear Regression model.
10. Build a Multiple Linear Regression model.
11. Train and test the models.
12. Evaluate model performance.
13. Visualize actual and predicted values.
14. Make predictions for new customers.

## 8. Model Evaluation Metrics

The following evaluation metrics are used:

| Metric | Purpose |
|---|---|
| MAE | Measures average absolute prediction error |
| MSE | Measures average squared prediction error |
| RMSE | Measures prediction error in the target variable's units |
| R² Score | Measures the proportion of variance explained by the model |

A higher R² score generally indicates better model performance, while lower MAE, MSE, and RMSE indicate smaller prediction errors.

## 9. Installation and Setup

### Step 1: Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### Step 2: Navigate to the project directory

```bash
cd Ecommerce-Customer-Spending-Prediction
```

### Step 3: Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

### Step 4: Open Jupyter Notebook

```bash
jupyter notebook
```

### Step 5: Run the project

Open the project notebook and execute the cells sequentially.

Make sure the CSV dataset is available in the correct project directory.

## 10. Project Structure

```text
Ecommerce-Customer-Spending-Prediction/
│
├── Ecommerce Customers.csv
│
├── Ecommerce_Linear_Regression.ipynb
│
└── README.md

```

## 11. Expected Output

After successfully executing the project, the following outputs will be generated:

- Dataset information and statistical summary.
- Missing value and duplicate checks.
- Correlation heatmap.
- Scatter plots and EDA visualizations.
- Simple Linear Regression model.
- Multiple Linear Regression model.
- Actual versus predicted value visualization.
- Model evaluation metrics.
- Predicted yearly spending for new customers.

## 12. Conclusion

This project demonstrates how Linear Regression algorithms can be applied to ecommerce customer data to predict yearly customer spending.

By comparing Simple Linear Regression and Multiple Linear Regression, the project helps demonstrate the importance of using multiple relevant features for prediction.

The model can help ecommerce businesses understand customer spending patterns and make data-driven decisions.

## 13. Future Improvements

- Implement Ridge and Lasso Regression.
- Perform feature selection and hyperparameter tuning.
- Compare additional regression algorithms.
- Develop an interactive dashboard using Streamlit.
- Deploy the trained model as a web application.

## 14. Author

**Project:** Ecommerce Customer Spending Prediction Using Linear Regression

**Domain:** Machine Learning

**Algorithm:** Simple Linear Regression and Multiple Linear Regression

**Language:** Python

---

⭐ If you find this project useful, consider giving the repository a star on GitHub!
