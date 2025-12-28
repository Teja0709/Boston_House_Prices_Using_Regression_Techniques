# Boston_House_Prices_Using_Regression_Techniques
Predicts Boston house prices using Linear Regression and Random Forest with feature importance analysis in Python.

## 📌 Project Overview
This project predicts the median value of owner-occupied homes (`MEDV`) in Boston using machine learning techniques.  
We use **Linear Regression** and **Random Forest Regressor** to model the data, compare their performance, and identify important features that influence house prices.

> **Note:** The dataset is **not included** in this repository. You can use the Boston Housing dataset from `scikit-learn` or other public sources.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- scikit-learn (Linear Regression, Random Forest)

---

## 📊 Features
- CRIM: per capita crime rate by town  
- ZN: proportion of residential land zoned for lots over 25,000 sq.ft.  
- INDUS: proportion of non-retail business acres per town  
- CHAS: Charles River dummy variable (1 if tract bounds river, 0 otherwise)  
- NOX: nitric oxides concentration (parts per 10 million)  
- RM: average number of rooms per dwelling  
- AGE: proportion of owner-occupied units built prior to 1940  
- DIS: weighted distances to five Boston employment centers  
- RAD: index of accessibility to radial highways  
- TAX: full-value property-tax rate per $10,000  
- PTRATIO: pupil-teacher ratio by town  
- B: 1000(Bk - 0.63)^2, where Bk is the proportion of blacks by town  
- LSTAT: % lower status of the population  
- MEDV: median value of owner-occupied homes (target variable)

---

## 📈 Project Steps
1. Load and explore the dataset  
2. Visualize feature distributions and correlations  
3. Scale features for Linear Regression  
4. Train Linear Regression and evaluate RMSE & R²  
5. Train Random Forest Regressor and evaluate RMSE & R²  
6. Compare both models and identify the best model  
7. Analyze feature importance  

---

## 📌 Conclusion
- Random Forest outperforms Linear Regression in RMSE and R²  
- Most important features: `RM` (average rooms) and `LSTAT` (% lower status population)  
- Model can predict median house price based on input features  

---

## 📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
