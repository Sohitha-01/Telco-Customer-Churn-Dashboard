# 📊 Telco Customer Churn Analysis

## 📝 Project Overview  
This project analyzes customer churn patterns in the **Telco dataset**, aiming to uncover key factors that drive customer retention and attrition. Insights were visualized through **interactive Tableau dashboards** and extended with a **machine learning workflow in Python** for churn prediction.  

---

## 📂 Project Structure  
```
Telco_Customer_Churn_Analysis/
│
├── Dashboard/
│   └── Telco_Customer_Churn_Analysis.twb      # Tableau dashboard
│
├── Dataset/
│   ├── Telco-Customer-churn.csv               # Raw dataset
│   └── Telco_Churn_Clean.csv                  # Cleaned dataset
│
├── Document Report/
│   └── Telco_Customer_Churn_Executive_Report.pdf   # Executive summary report
│
├── Images/
│   ├── Demographics and customer churn.png    # Demographics Dashboard
│   ├── Financial Impact of Customer Churn.png # Financial Impact Dashboard
│   ├── Services & Product Impact.png          # Services & Products Dashboard
│   └── Teleco Customer Churn.png              # Customer Churn Overview
│
├── Python/
│   └── Data_Cleaning.ipynb                    # Data Cleaning notebook
│   └── Preprocessing_&_Training.ipynb         # Data preprocessing & Training notebook
```
---

## 🎯 Objectives  
- Identify customer demographics and services linked to higher churn rates  
- Highlight revenue impact of customer attrition  
- Provide actionable insights for churn reduction strategies  
- Extend analysis with a **predictive churn model**  

---

## 🛠️ Tech Stack  
- **Visualization:** Tableau  
- **Programming:** Python (pandas, scikit-learn, matplotlib)  
- **Data Source:** Telco Churn Dataset  

---

## 📊 Tableau Dashboards  
Interactive dashboards created in Tableau include:  
- **Churn Overview** – High-level churn statistics and trends  
- **Demographic Insights** – Churn by gender, senior citizen status, dependents, etc.  
- **Service Usage** – Impact of internet services, contracts, and payment methods on churn  
- **Revenue Analysis** – Monthly charges and total revenue loss from churn  

---

## 🐍 Machine Learning Extension  
In addition to dashboards, this project includes a **Python-based churn prediction model**:  

- **Data Preprocessing:**  
  - Handled missing values and encoded categorical features  
  - Train/test split with stratification  

- **Model Training (Basic):**  
  - Logistic Regression baseline model  
  - Metrics: **Accuracy, Precision, Recall**  
  - Confusion Matrix visualization for error analysis  

- **Notebook:**  
  - [`Preprocessing_&_Training.ipynb`](./Preprocessing_&_Training.ipynb) – preprocessing + churn prediction  

This workflow complements the dashboards by showing how churn insights can be turned into a **predictive model** to anticipate future customer behavior.  

---

## 📈 Key Insights  
- Overall churn rate ≈ **26.5%**.  
- Customers on **month-to-month contracts** churn disproportionately more than yearly contract customers.  
- **Senior citizens** and **single customers** show higher churn rates.  
- **Fiber optic users** churn at higher rates compared to DSL.  
- Customers paying by **Electronic Check** are most likely to churn.  
- Estimated monthly revenue loss: **≈ 30% of total revenue (~$139K)**.  

---

## 📸 Sample Dashboards  
This project includes four dashboards to analyze churn patterns:  

- **Customer Churn Overview**  
- **Demographics Dashboard**  
- **Services & Products Dashboard**  
- **Financial Impact Dashboard**  

👉 [View Dashboard Images](https://github.com/Sohitha-01/Telco-Customer-Churn-Dashboard/tree/7a7f158d8371c1e7a57618155476c9044079fb40/Images)  

---

# 🏆 Why This Project Matters  
Customer churn has a direct impact on recurring revenue. This project highlights risk segments, quantifies financial losses, and provides data-driven insights to support **targeted retention strategies**. The dashboards are designed for executives to quickly identify where action is needed.  

---

## 📎 Dataset  
[Kaggle: Telco Customer Churn](https://www.kaggle.com/blastchar/telco-customer-churn)  

---

## 📧 Author  
👩‍💻 **Sohitha**  
For feedback or collaboration, connect via GitHub.

---

## 📜 License

This project is open-source and licensed – feel free to use it.
