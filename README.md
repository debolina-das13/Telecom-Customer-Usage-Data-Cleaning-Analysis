# Telco Customer Churn EDA

**Project Type:** Data Cleaning & Exploratory Data Analysis (EDA)  
**Dataset:** [Telco Customer Churn – Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) 
**Google Colab Notebook:** [Open in Colab](https://colab.research.google.com/drive/1_GDd8h6W58B4h3MkAVMG-jN-aS6DcPId?usp=sharing)  


---

##  Project Overview

This project focuses on **cleaning, preprocessing, and exploring** the Telco Customer Churn dataset. The dataset contains **7,043 customer records** and **21 features**, including demographic information, service details, billing data, and churn status.  

The goal of this project is to:  
1. Clean messy real-world data  
2. Explore patterns in customer behavior  
3. Generate insights that help understand factors affecting customer churn  

---

## 🛠️ What I Did

### 1️ Data Cleaning
- Converted `TotalCharges` to numeric and handled missing values  
- Standardized categorical columns (lowercase, trimmed spaces)  
- Removed duplicate records  

### 2️ Exploratory Data Analysis (EDA)
- Visualized **churn distribution**  
- Explored **monthly charges and tenure**  
- Counted **internet service types and contract plans**  
- Calculated **average monthly charges by churn**  
- Calculated **churn rate percentage**  

### 3️ Insights
- Customers with **higher monthly charges** are more likely to churn  
- Most customers use **Fiber optic** or **DSL** internet service  
- **Month-to-month contracts** show higher churn compared to long-term contracts  

---

##  Skills Demonstrated

- Python, Pandas, NumPy  
- Data Cleaning & Preprocessing  
- Exploratory Data Analysis (EDA)  
- Data Visualization (Matplotlib & Seaborn)  

---

## Files in This Repository

- `Telco_Churn_EDA.ipynb` – Jupyter/Colab notebook with **full cleaning, visualization, and analysis**  
- `cleaned_telco_data.csv` – Cleaned dataset ready for further analysis  

---

##  How to Run

1. Clone the repository:  
```bash
git clone <your-repo-link>

