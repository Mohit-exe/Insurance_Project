# 🏥 Insurance Project

This project analyzes an **insurance dataset** to understand the factors influencing medical charges.  
It applies data cleaning, exploratory data analysis (EDA), visualization, and regression modeling to derive insights.  

---

## 📂 Project Overview
- Cleaned and preprocessed raw insurance data (handling missing values, encoding categorical variables, scaling).  
- Performed **exploratory data analysis (EDA)** with visualizations to study relationships between features such as age, BMI, smoking status, and region.  
- Built **regression models** (Linear Regression, Multiple Regression) to predict medical charges.  
- Evaluated models using performance metrics like **R², Adjusted R², RMSE**.  
- Derived insights on how **smoking, BMI, and age** strongly affect medical expenses.  

---

## 📊 Dataset
- **Features:** Age, Sex, BMI, Children, Smoker, Region  
- **Target:** Charges (Medical Expenses)  
- Size: ~1,300 records  

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:** pandas, numpy, matplotlib, seaborn, scikit-learn  

---

## 🚀 Results
- Smoking is the most significant factor influencing insurance charges.  
- Higher BMI and age are also strongly associated with increased medical costs.  
- Multiple Linear Regression outperformed simple models in predictive accuracy.  

---

## 📌 Future Improvements
- Implement regularization techniques (Ridge, Lasso) to reduce multicollinearity.  
- Try ensemble models (Random Forest, XGBoost) for better predictive performance.  
- Deploy the model as an API or simple dashboard for real-world usage.  

---

## ▶️ How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/your-username/Insurance-Project.git
   cd Insurance-Project
2.Install dependencies:
   ```bash
   pip install -r requirements.txt
```
3.Open the Notebook:
```bash
jupyter notebook Insurance_Project.ipynb


