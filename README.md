# 🚗 Auto Insurance Claims & Policyholder Risk Analysis – Power BI Dashboard

## 📌 Project Overview
This project focuses on **Auto Insurance Claims and Policyholder Risk Analysis using Power BI**. The dashboard is designed to help insurers understand **claim frequency, claim severity, regional risk patterns, premium behavior, and customer demographics**, enabling better **underwriting and risk management decisions**.

The solution simulates a **real-world enterprise BI workflow**, where data is sourced from a database, cleaned, exported as CSV, and analyzed in Power BI.
<img width="1315" height="728" alt="image" src="https://github.com/user-attachments/assets/2d9e263a-6f1e-4f0a-9248-80fc4e4a83b9" />


---

## 🎯 Goal of the Project
The primary goals of this project are to:

- Analyze **auto insurance claim patterns and claim severity**
- Identify **high-risk customer segments and regions**
- Study the relationship between **premium amount and claim frequency**
- Support **data-driven underwriting and pricing strategies**

---

## 🗄️ Data Source & Ingestion

### 🔹 Primary Source *(Simulated Production Setup)*
- Data assumed to originate from an **enterprise insurance database** *(e.g., MSSQL / data warehouse)*
- Tables include:
  - Policyholder details  
  - Premium information  
  - Claims data  
  - Risk attributes  

### 🔹 Attached Dataset
- **synthetic_insurance_data.csv**

This file represents a **cleaned and extracted dataset**, similar to what would be downloaded from a production system for:
- Analysis  
- Validation  
- Offline dashboard development  

### 🔹 Power BI File
- **Auto_insurance.pbix** – Contains the Power BI data model, DAX measures, and dashboard visuals

---

## 📂 Project Files
- **Auto_insurance.pbix** – Power BI report  
- **synthetic_insurance_data.csv** – Cleaned insurance dataset  
- **Dashboard Image** – Visual snapshot of the dashboard  

---

## 🔄 Procedure / Methodology

### 1. Data Extraction
- Data sourced from an insurance dataset representing **policyholders, premiums, and claims**

### 2. Data Cleaning & Preparation
- Handled missing values  
- Standardized:
  - Claim severity levels  
  - Age bins  
  - Regions  
  - Policy attributes  

### 3. Data Import into Power BI
- Imported cleaned CSV into Power BI using **Import mode**

### 4. Data Modeling
- Created relationships between tables
- Built calculated **DAX measures** for:
  - Claim counts  
  - Claim severity  
  - Averages and totals  

### 5. Dashboard Design
- Designed:
  - KPI cards  
  - Bar charts  
  - Donut charts  
  - Scatter plots with trendlines  
  - Stacked visuals  
  - Interactive slicers  

### 6. Insight Generation
- Interpreted visuals to identify **risk patterns and business insights**

---

## 📊 Dashboard Highlights

### KPI Cards
- **Total Claims**
- **Average Claims per Policy**
- **Total Claim Adjustment**
- **Average Claim Amount**

### Analytical Views
- Claim severity distribution *(Low, Medium, High)*
- Regional distribution of claims *(Urban, Suburban, Rural)*
- Claim frequency vs **Premium Amount** *(scatter plot with trendline)*
- Age-based claim severity analysis
- Region-wise claim severity comparison

### Filters & Interactivity
- Source of Lead  
- Policy Type  
- Marital Status  

---

## 📈 Visualization-Based Insights

### 1️⃣ Overall Claims Summary
- **Total Claims:** 4,972  
- **Average Claims:** 0.50  
- **Total Claim Adjustment:** 368K  
- **Average Claim Amount:** 73.97  

**Insight:**  
Claim volume is moderate, but adjustment costs highlight the importance of **effective claim control mechanisms**.

---

### 2️⃣ Claim Severity Distribution
- Low severity claims dominate the portfolio
- Medium severity claims form a significant portion
- High severity claims are fewer but carry higher financial risk

**Insight:**  
High-severity claims, despite low frequency, contribute **disproportionately to risk exposure**.

---

### 3️⃣ Regional Risk Analysis
- **Urban regions** contribute the highest claim count
- **Suburban regions** show moderate claim levels
- **Rural regions** have the lowest claim frequency

**Insight:**  
Urban driving environments pose higher claim risk, requiring **differentiated pricing and underwriting models**.

---

### 4️⃣ Premium vs Claim Frequency
- Positive correlation between **premium amount and claim frequency**
- Higher premiums are associated with higher claim counts

**Insight:**  
Premium pricing effectively reflects underlying risk, validating **existing pricing strategies**.

---

### 5️⃣ Age-Based Claim Severity
- Majority of claims originate from **mid-age groups**
- Claim frequency reduces significantly at higher ages

**Insight:**  
Certain age bands represent higher exposure and should be **closely monitored**.

---

### 6️⃣ Claim Severity by Region
- Urban regions show higher low and medium severity claims
- Rural regions show fewer high severity claims

**Insight:**  
Region-specific risk profiles can guide **regional underwriting and policy design**.

---

## ⭐ Key Business Insights
- Claims are concentrated in **Urban regions**
- Low severity claims dominate volume, but high severity claims drive risk
- Premium amount and claim frequency show **positive correlation**
- **Age and geography** are key risk differentiators

---

## 🧠 Business Recommendations
1. Apply **risk-based pricing** for Urban and high-risk regions  
2. Introduce targeted **risk mitigation programs** for high-frequency age groups  
3. Monitor **high-severity claims** closely despite lower frequency  
4. Refine premium models using **claim frequency and severity trends**  

---

## 🚀 Next Steps
- Connect Power BI directly to a **live database** using DirectQuery
- Add **predictive risk scoring** and fraud indicators
- Perform **claim severity forecasting**
- Enhance analysis with **policy tenure and vehicle type segmentation**

---

## 👤 Author
**Tejeshwar R**  
Data Analyst | Power BI | SQL | Excel | Python | Statistics
