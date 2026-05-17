# 📊 Impact of Quick Commerce on Retail Stores

## 🚀 Project Overview
This project analyzes the **impact of Quick Commerce (Q-commerce)** on traditional retail stores using **consumer survey data**. It explores how platforms like Zepto, Blinkit, etc., are transforming customer behavior, spending patterns, and retail store visits.

---

## 🎯 Objectives
- Analyze the impact of quick commerce on retail stores  
- Identify factors driving customers toward Q-commerce  
- Study changes in:
  - Shopping frequency  
  - Spending behavior  
  - Consumer preferences  

---

## 📂 Dataset Information
- 📌 Source: Google Form (Primary Data)
- 📊 Records: **147 rows**
- 📑 Features: **19 columns**
  - 15 categorical  
  - 4 numerical  

✔ No missing values  
✔ No duplicate records  

---

## 🔍 Methodology

### 1️⃣ Data Collection
- Survey-based dataset (17 questions)
- Target variable: **Shopping Preference**

### 2️⃣ Exploratory Data Analysis (EDA)
- Data cleaning & preprocessing  
- Outlier detection using **Winsorization**  
- Visualization of trends  

### 3️⃣ Hypothesis Testing
Performed statistical tests to validate relationships:

- ✅ **Chi-Square Test**
  - Shopping Preference vs Platform  
  - Shopping Preference vs Cost Effectiveness  
  - Shopping Preference vs Retail Frequency  

- ✅ **One-Way ANOVA**
  - Monthly Spend  
  - Store Visit Replacement  
  - Overall Satisfaction  

---

## 🤖 Model Building

### Model Used:
👉 **Logistic Regression**

### Steps:
- Data preprocessing (encoding categorical variables)  
- Train-test split  
- Feature selection  
- Model training  

### 📈 Performance:
- Training Accuracy: ~75%  
- Test Accuracy: **~80%**  
- ROC Curve indicates **good model performance (0.75–0.80 range)**  

---

## 📊 Key Insights

✔ Quick commerce is causing a **structural shift in consumer behavior**  
✔ Customers prefer Q-commerce due to:
- Faster delivery  
- Discounts & offers  
- Convenience  

✔ Retail store visits are **declining significantly**  

✔ Quick commerce users:
- Spend more monthly  
- Show higher satisfaction  

✔ Traditional retail still holds strength in:
- Product trust  
- Physical experience  
- Immediate purchase  

---

## 🛠️ Tech Stack

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **SciPy / Statsmodels**

---

## 📁 Project Structure

```
├── data/
│   └── survey_data.csv
├── notebook/
│   └── analysis.ipynb
├── presentation/
│   └── Impact_of_Quick_Commerce.pdf
├── README.md
```

---

## 📌 Future Scope

- Add more data for better generalization  
- Try advanced ML models (Random Forest, XGBoost)  
- Build a **Power BI dashboard**  
- Deploy as a **web app using Streamlit**  

---

## 👨‍💻 Team Members
- [Drashti](https://github.com/drashtipatodia)
- [Manasi](https://github.com/shindemanasi47-sketch)
- [Pritesh](https://github.com/Pritesh-S)
- [Varad](https://github.com/Varad2k03)

---

## 📢 Conclusion
Quick Commerce is reshaping the retail ecosystem by prioritizing **speed, convenience, and pricing strategies**. While traditional retail still plays a role, Q-commerce is rapidly becoming the preferred choice for modern consumers.
