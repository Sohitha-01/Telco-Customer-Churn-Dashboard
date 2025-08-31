# 📊 Telco Customer Churn Dashboard

## 📝 Project Overview  
This project provides an analysis of customer churn using the **Telco Customer Churn dataset** and interactive **Tableau dashboards**.  

The goal is to uncover churn patterns, understand demographic and service-related factors influencing churn, and quantify the financial impact to support business decision-making and retention strategies.  

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
│   └── Data_Cleaning.ipynb                    # Data preprocessing notebook
```
---

## 🎯 Objectives  
- Analyze churn rate and customer segments driving churn.  
- Identify demographic groups with higher churn risk.  
- Evaluate service usage and its relationship to churn.  
- Quantify financial losses due to churn.  
- Provide executive-level dashboards for decision-making.  

---

## 🛠️ Tech Stack  
- **Tableau** – Interactive dashboards and visual storytelling.  
- **MS Word / PDF** – Supporting executive report.
- **Python** – For Cleaning the dataset.
- **CSV (Cleaned dataset)** – Final dataset used for dashboarding.  

---

## 🔎 Key Analyses & Deliverables  

1. **Customer Churn Overview Dashboard**  
   - KPIs: Total Customers, Churn %, Avg. Tenure  
   - Churn by Contract type  
   - Average Monthly Charges by churn status  
   - Churn trend by Tenure  

2. **Demographics Dashboard**  
   - Churn by Gender  
   - Churn by Senior Citizen status  
   - Churn by Family Status (Partner/Dependents)  

3. **Services & Products Dashboard**  
   - Churn by Internet Service (DSL, Fiber, None)  
   - Churn by Add-On Services (Tech Support, Online Security, Streaming TV)  
   - Churn by Payment Method  

4. **Financial Impact Dashboard**  
   - Avg. Monthly Charges by churn status  
   - Revenue Loss Estimate (total $ and %)  
   - Total Charges distribution (Box Plot)  

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
