#  Car Price Prediction Project  

This project focuses on building a **machine learning model** to predict the price of cars based on various features such as brand, model, year, mileage, fuel type, and other specifications. The goal is to assist businesses or individuals in estimating fair car prices using data-driven insights.  

---

##  Project Workflow  

### 1. Data Understanding & Cleaning  
- Loaded raw dataset containing car details (brand, model, year, mileage, engine, fuel type, etc.).  
- Checked for missing values, duplicates, and outliers.  
- Handled missing values using appropriate imputation techniques.  
- Converted categorical variables into numerical representations.  

### 2. Exploratory Data Analysis (EDA)  
- Visualized distributions of key features (e.g., year, mileage, fuel type).  
- Analyzed correlations between features and car price.  
- Detected outliers and trends (e.g., newer cars tend to have higher prices, higher mileage lowers the price).  

### 3. Feature Engineering  
- Encoded categorical variables (One-Hot Encoding / Label Encoding).  
- Created new features such as car age.  
- Scaled numerical features to improve model performance.  

### 4. Model Building  
- Split the dataset into training and testing sets.  
- Trained multiple regression models (e.g., Linear Regression, Random Forest, Gradient Boosting).  
- Tuned hyperparameters for optimal performance.  

### 5. Model Evaluation  
- Evaluated models using metrics such as:  
  - **MAE (Mean Absolute Error)**  
  - **RMSE (Root Mean Squared Error)**  
  - **R² Score**  
- Compared models to select the best-performing one.  

---
