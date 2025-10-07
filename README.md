# Projects



# 🧠 First Linear Regression Project

## 📌 Objective
Predict **Sales** based on advertising budgets for **TV**, **Radio**, and **Newspaper** channels using **Linear Regression**.

---

## 🧾 Dataset
- **Dataset:** Advertising dataset (200 samples, 4 columns: TV, Radio, Newspaper, Sales)  
- **Source:** Educational dataset (scikit-learn or CSV version)  
- **Missing Values:** None  
- **Shape:** (200, 4)

---

## 🧮 Process Overview

### 1️⃣ Data Exploration
- Checked for null values  
- Reviewed dataset shape and summary  
- Visualized relationships using `seaborn.pairplot()`

### 2️⃣ Model Building
- Split data into **Train (80%)** and **Test (20%)**  
- Trained model using `sklearn.linear_model.LinearRegression`  
- Evaluated model on test data

### 3️⃣ Model Performance
| Metric | Value |
|:-------|:------:|
| **R² Score** | 0.899 |
| **RMSE** | 1.78 |
| **MAE** | 1.46 |

---

## 📊 Visualizations
- 📈 **Actual vs Predicted Sales**
- 🔹 **Residuals vs Predicted Sales**
- 📊 **Feature Importance Bar Chart**

---

## 🧩 Key Findings
- **TV and Radio** have the strongest positive impact on Sales.  
- **Newspaper** ads show minimal influence.  
- The model explains **~90% of the variance** in Sales — very high accuracy for a simple regression model.  
- Residuals are **randomly scattered around 0**, confirming that model assumptions hold.

---

## 💡 Recommendations
- Increase spending on **TV and Radio** advertising.  
- Reconsider **Newspaper** investments due to weak correlation with Sales.  
- Consider exploring **interaction effects** between TV and Radio ads.

---

## 🔧 Tech Stack
- **Language:** Python 🐍  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook / Google Colab

---

## 🏁 Outcome
This project demonstrates a complete **Data Science workflow**:
1. Data understanding and preprocessing  
2. Model building and evaluation  
3. Visualization and interpretation  
4. Actionable insights  

✅ Built a predictive model that **accurately forecasts sales** with minimal error.  
✅ Great starting point for learning **machine learning and regression analysis**.

---

## 📂 Future Improvements
- Add **interaction and polynomial features**  
- Use **Ridge and Lasso regression** for regularization  
- Deploy model using **Streamlit** or **Flask**

---

👤 **Author:** Sudipto Bhadra  
📅 **Project:** First Linear Regression Project  
