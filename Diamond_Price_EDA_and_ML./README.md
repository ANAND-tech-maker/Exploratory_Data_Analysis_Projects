# 💎 Diamond Price Prediction (EDA + Machine Learning)

## 📌 Project Overview
This project performs Exploratory Data Analysis (EDA) and builds Machine Learning models to predict diamond prices using physical and categorical attributes. It includes data cleaning, visualization, feature engineering, encoding, and model evaluation.

---

## 📂 Dataset Information
The dataset contains the following columns:

- **carat** – Weight of the diamond  
- **cut** – Quality of the cut  
- **color** – Color grade  
- **clarity** – Clarity level  
- **depth** – Total depth percentage  
- **table** – Width of the top of the diamond  
- **x, y, z** – Physical dimensions  
- **price** – Target variable

---

## 🧹 Step 1: Data Cleaning
- Checked shape, info, describe  
- Handled missing values  
- Removed duplicates  

---

## 🔍 Step 2: Exploratory Data Analysis
### Univariate Analysis:
- Distribution of numerical features (carat, depth, table, price)
- Countplots for categorical features (cut, color, clarity)

### Bivariate Analysis:
- Carat vs Price  
- Cut vs Price  
- Color vs Price  
- Clarity vs Price  

### Multivariate Analysis:
- Correlation heatmap  
- Pairplots for key numerical features  

---

## 🧪 Step 3: Feature Engineering
- Created new features:
  - **volume = x * y * z**
  - **price_per_carat = price / carat**
- Converted categorical variables using Ondrinalencoder
- Scaled numerical features

---

## 🤖 Step 4: Model Building
Models trained:
- Linear Regression  
- Random Forest Regressor  
- DecisionTreeRegressor
- KNeighborsRegressor 

---

## 📊 Step 5: Model Evaluation
Metrics used:
- MAE (Mean Absolute Error)  
- MSE (Mean Squared Error)  
- RMSE (Root Mean Squared Error)  
- R² Score  

---

## 🏁 Final Outcome
- Successfully built a regression model to predict diamond prices.
- Performed complete EDA with insights.
- Feature engineering improved model accuracy.
- Identified strongest predictors like **carat**, **cut**, **clarity**, and **volume**.

---

## 📎 Tools & Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-Learn  
- XGBoost  
