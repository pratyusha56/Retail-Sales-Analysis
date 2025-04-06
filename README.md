# Retail-Sales-Analysis
This project performs an end-to-end data analysis and machine learning modeling process on a retail sales dataset obtained from the UCI Machine Learning Repository and Kaggle. The dataset contains 30,000 records of transactions with attributes related to store information, product categories, marketing spend, discounts, holidays, and sales revenue.

#  Comprehensive Retail Sales Data Analysis

---

##  Project Description
This project explores a retail sales dataset from the [UCI Machine Learning Repository and Kaggle](https://www.kaggle.com/datasets/abdullah0a/retail-sales-data-with-seasonal-trends-and-marketing), consisting of 30,000 entries across multiple store locations and product categories. It involves exploratory data analysis, visualization, feature engineering, and the application of various machine learning models to predict sales revenue and understand holiday impact.

---

## Objectives
- Identify the key factors influencing sales revenue  
- Detect seasonal trends and patterns in retail sales  
- Analyze the impact of holidays and discounts on revenue  
- Build and evaluate regression models for sales forecasting

---

##  Project Workflow

### 1. Data Exploration and Cleaning
- Checked for missing values and outliers  
- Parsed dates, extracted month/year  
- Converted categorical variables into dummies

### 2. Exploratory Data Analysis
- Correlation heatmaps  
- Distribution and trend plots  
- Sales patterns across time, category, and holidays

### 3. Model Building
- Regression Models:  
  - Linear Regression  
  - Ridge & Lasso  
  - Decision Tree & Random Forest  
  - Gradient Boosting (Best Performer)  
  - Support Vector Regressor (SVR)  
  - K-Nearest Neighbors (KNN)

- Classification Models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest (to classify holiday vs non-holiday transactions)

### 4. Validation
- 3-fold Cross-Validation  
- Metrics: R², MSE, MAE, ROC-AUC  
- Gradient Boosting achieved **R² = 0.989** on test data

---

##  Results and Key Insights
- **Units Sold** is strongly correlated with **Sales Revenue**  
- **Holidays** and **Discounts** positively influence revenue  
- **Gradient Boosting Regressor** is the best model with high accuracy  
- Preprocessing and feature selection are critical for improving performance

---

##  Technologies & Tools
- Python 3.x  
- pandas, numpy  
- matplotlib, seaborn  
- scikit-learn (modeling and pipelines)

---

##  Use of Online Resources
- Researched error resolutions during implementation  
- Referred to official documentation for `sklearn`  
- Explored blogs and GitHub repositories for modeling strategies and hyperparameter tuning

---

## How to Run
1. Clone the repo or download files locally  
2. Ensure you have the dataset file `Retail_sales.csv` in your working directory  
3. Run the Jupyter Notebook or Python script step-by-step  
4. Use `pip install -r requirements.txt` to install dependencies

---

## License
This project is developed for academic purposes as part of the **UNT Advanced Data Analytics** curriculum.
