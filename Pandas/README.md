# 🛒 Customer Purchase Data Analysis  

A complete, end-to-end notebook that performs **exploratory data analysis (EDA)** on a synthetic customer purchase dataset. It covers **data inspection, demographic profiling, spending behavior analysis, profession insights, credit card usage patterns, and customer engagement segmentation**.  

---

## ✨ Key Features  
- 🧭 **Data Overview**: `head()`, `info()`, `describe()`, missing-value detection & visualization  
- 👥 **Demographics**: Age distribution (min, max, mean), most common customer names  
- 📊 **Dataset Structure**: Row/column counts, missing values bar chart  
- 👷 **Professions**: Frequency counts, Structural Engineer insights by gender & province  
- 💳 **Credit Card Analysis**: Visa users, CC-linked email checks, duplicate phone numbers  
- 💵 **Spending Patterns**: Minimum, maximum, and average spending amounts  
- 🎯 **Customer Segmentation**:  
  - Zero-spend customers (deal targeting)  
  - Loyal high spenders (≥100 CAD reward program)  
- 📧 **Email Insights**: Top 5 providers (e.g., Gmail, Yahoo, etc.)  
- 📅 **Temporal Trends**: Busiest weekdays for customer visits  

---

## 🚀 Getting Started  
Open and run the notebook directly in **Google Colab**.  
You can interactively explore the dataset, view statistics, and generate visualizations.  

🔗 **Colab Notebook**: [Customer Purchase EDA](https://colab.research.google.com/drive/14F-uNlFlCmLcjG4wrfXOUy9IMK1aDlAt?usp=sharing)  

---

## 🧩 Dataset Assumptions  
- Customer profile includes: `fullname`, `age`, `gender`, `profession`, `province`, `phone`, `email`  
- Transaction details: `price(CAD)`, `cc_type`, `cc_no`, `weekday`  
- Synthetic dataset generated for educational purposes  

---

## 📊 Results You’ll See  
- ✅ Missing-value bar chart  
- ✅ Age statistics (max, min, mean)  
- ✅ Top customer names & duplicate phone numbers  
- ✅ Profession distributions (overall & filtered)  
- ✅ Spending behavior (min/max/avg, zero vs. loyal spenders)  
- ✅ Credit card usage by type  
- ✅ Most common email providers  
- ✅ Top weekdays for purchases  

---

## 🖼️ Visualizations Included  
- 📦 Missing values (bar chart)  
- 📈 Spending distribution  
- 🏆 Top professions (bar chart)  
- 📧 Email provider frequencies  
- 📅 Weekday customer trends  

---

## 🛠️ Tech Stack  
- 🐍 Python  
- 📓 Google Colab + Drive Integration  
- 📊 Pandas, NumPy  
- 📈 Matplotlib  

