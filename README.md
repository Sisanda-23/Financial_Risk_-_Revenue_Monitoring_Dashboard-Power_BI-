# Financial Risk & Revenue Monitoring Dashboard (Power BI)

## Business Problem

Senior management in financial services organisations require a **single, consolidated dashboard** to monitor:

- Revenue performance  
- Customer attrition / financial risk  
- Profitability by customer segment  
- Early warning signals to support proactive decision-making  

This project simulates a **financial services BI use case**, where customer churn is reframed as **attrition risk**, similar to default or account closure risk in banking and investment firms.

**Objective:**  
Design a **management-ready Power BI dashboard** that connects analytics directly to business decisions.

---

## Data Used

The project uses a **customer behaviour dataset** (commonly applied to churn analysis), reframed to reflect a **financial risk context**.

### Key Reframing

| Original Term        | Financial Context              |
|----------------------|--------------------------------|
| Churn                | High Risk Flag                 |
| Monthly Charges      | Monthly Revenue                |
| Tenure               | Customer Lifetime (Months)     |
| Contract Type        | Product Type                   |

### Additional Transformations

- Revenue-based customer segmentation *(Low / Mid / High Value)*  
- Tenure grouping to support early risk detection  

 **Note:** Monthly revenue was used as the primary financial metric to ensure consistency and reliability across the dashboard.

---

##  Data Preparation & Modelling

All data preparation was performed directly in **Power BI using Power Query**, simulating a real-world BI workflow:

- Cleaning missing and inconsistent values  
- Standardising revenue fields and data types  
- Business-focused column renaming  
- Creation of tenure bands for risk analysis  
- Derivation of revenue-based customer segments  

---

##  Key Measures (DAX)

The dashboard uses **simple, interpretable DAX measures** aligned with executive reporting needs:

- **Total Revenue**  
- **Customer Count**  
- **Average Revenue per Customer**  
- **Risk Rate (%)**  
- **High-Risk Customer Count**  
- **Revenue at Risk**  

The focus is on **clarity and decision support**, rather than complex modelling.

---

##  Dashboard Design

The Power BI report consists of **three pages**, each designed for a specific management purpose.

### Page 1 — Executive Overview

**Contents:**
- High-level KPIs:  
  - Total Revenue  
  - Customer Count  
  - Risk Rate  
  - Revenue at Risk  
- Revenue and risk trends over time  
- Risk distribution across the customer base  

**Purpose:**  
Rapid executive-level monitoring and early warning.

---

###  Page 2 — Risk Analysis

**Contents:**
- Risk rate by product type  
- Risk rate by tenure group  
- Revenue at risk by customer segment  
- Matrix view highlighting key risk drivers  

**Purpose:**  
Identify **where** and **why** risk is occurring.

---

###  Page 3 — Customer & Product Insights

**Contents:**
- Revenue contribution by customer segment  
- Risk vs value analysis to identify high-value, high-risk customers  
- Revenue at risk by product type  
- Actionable customer-level view for targeted interventions  

**Purpose:**  
Support **commercial decision-making and prioritisation**.

---

##  Key Insights

- Short-tenure customers consistently exhibit **higher attrition risk**  
- Month-to-month product types contribute **disproportionately to revenue at risk**  
- High-value customers, while fewer in number, represent a **significant share of potential revenue loss**  
- Longer-tenure customers generate **more stable revenue with lower risk exposure**

---

##  Business Recommendations

- Prioritise retention strategies for **high-value, high-risk customers**  
- Introduce incentives or contract migration strategies for **short-term product users**  
- Monitor **tenure-based risk** as an early warning signal for future revenue exposure  
- Use **revenue-at-risk metrics** to guide targeted customer engagement efforts  

---

##  Tools Used

- **Power BI** — Data modelling, DAX measures, dashboard design  
- **Power Query** — Data cleaning and transformation  

---

##  Project Outcome

This project demonstrates the ability to:

- Translate raw data into **business-relevant insights**  
- Design dashboards for **executive decision-making**  
- Apply **risk and revenue thinking** in a financial services context  
- Communicate insights **clearly and concisely**
