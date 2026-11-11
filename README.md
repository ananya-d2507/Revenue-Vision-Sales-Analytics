# RevenueVision – Sales Analytics and Forecasting Platform

## 1. Project Overview

RevenueVision is a Data Science and Machine Learning project developed to analyse historical sales data, understand customer purchasing behaviour, identify business trends, and forecast future sales.

The project uses the Superstore Sales Dataset obtained from Kaggle. It combines data analysis, SQL queries, customer segmentation, and machine learning techniques to generate meaningful business insights.

## 2. Project Objectives

- Analyse historical sales data.
- Identify sales and profit trends.
- Understand category-wise and region-wise performance.
- Identify top-performing products.
- Perform customer segmentation using clustering.
- Build machine learning models for sales forecasting.
- Develop a user-friendly interface to display predictions.

## 3. Dataset Description

**Dataset:** Superstore Sales Dataset

**Source:** Kaggle

The dataset contains 9,994 records and 21 columns.

Important features include:

- Order Date
- Ship Date
- Customer ID
- Customer Name
- Segment
- Region
- Category
- Sub-Category
- Product Name
- Sales
- Quantity
- Discount
- Profit

The dataset provides information about customer orders, products, sales, and profitability.

## 4. Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SQLite
- Scikit-learn
- XGBoost
- Gradio
- Google Colab

## 5. Project Workflow

### Step 1: Data Preprocessing

The dataset was loaded and inspected using Python. Missing values, duplicate records, and data types were checked. Date columns were converted into appropriate datetime formats.

### Step 2: Feature Engineering

Additional date-related features such as Year, Month, Day, and Quarter were extracted to support data analysis and forecasting.

### Step 3: Exploratory Data Analysis (EDA)

EDA was performed to understand the dataset and discover useful patterns.

The analysis included:

- Descriptive statistics
- Total sales and total profit
- Category-wise sales analysis
- Region-wise sales analysis
- Sub-category analysis
- Monthly sales trends
- Customer segment analysis
- Discount and profit relationship
- Correlation analysis and heatmap

### Step 4: SQL Analysis

SQLite was used to perform database queries on the Superstore dataset.

SQL analysis included:

- Total sales calculation
- Category-wise sales analysis
- Region-wise sales analysis
- Top-selling product identification

### Step 5: Customer Segmentation

K-Means Clustering was used to group customers based on their purchasing behaviour.

Customer features included:

- Total Sales
- Total Profit
- Total Quantity
- Total Orders

StandardScaler was used to scale the data before applying the clustering algorithm. Customers were divided into three clusters for further analysis.

### Step 6: Model Building and Training

Machine learning models were developed to forecast monthly sales.

The models used were:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Historical monthly sales and lag-based features were used to train the models. The dataset was split chronologically into training and testing sets.

### Step 7: Model Evaluation

The trained models were evaluated using the following metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

The evaluation results were used to compare model performance and select the best-performing model.

### Step 8: Model Saving

The selected machine learning model was saved using Joblib for future use and prediction.

### Step 9: User Interface Integration

A user-friendly interface was developed using Gradio to allow users to provide input values and obtain sales predictions.

## 6. Project Outcomes

- Identified important sales and profit patterns.
- Analysed category-wise and region-wise performance.
- Identified top-selling products.
- Segmented customers using K-Means clustering.
- Developed machine learning models for monthly sales forecasting.
- Created an interactive interface for sales prediction.

## 7. Project Structure

RevenueVision/
│
├── RevenueVision.ipynb
├── best_sales_model.joblib
├── README.md
└── screenshots/

## 8. Conclusion

RevenueVision demonstrates the practical application of Data Science, SQL, and Machine Learning in sales analytics and forecasting.

Through data preprocessing, exploratory data analysis, SQL analysis, customer segmentation, and predictive modelling, the project provides useful insights into business performance.

This project also provided practical experience in data analysis, machine learning model development, evaluation, and interactive application development.

## 9. Author

Developed as a Data Science project using the Superstore Sales Dataset.
