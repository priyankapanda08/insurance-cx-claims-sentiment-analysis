# 🚀 Insurance CX: Claims & Sentiment Analysis

End-to-End Data Analytics Project leveraging SQL Server and Power BI to analyze insurance claims, customer behavior, and customer sentiment, delivering actionable business insights.

---

## 📌 Project Overview

This project focuses on analyzing structured insurance data along with unstructured customer feedback to gain a comprehensive understanding of business performance and customer experience.

By integrating claims data with sentiment analysis, the project provides a 360-degree view of:
- Policy performance  
- Claim trends  
- Customer satisfaction  
- Operational inefficiencies  

---

## 🎯 Objectives

- Analyze insurance claims and policy performance  
- Identify high-risk customers and claim patterns  
- Evaluate premium vs claim payout trends  
- Perform sentiment analysis on customer feedback  
- Identify key drivers of customer satisfaction and dissatisfaction  

---

## 📊 Dataset Description

### 🔹 Insurance Dataset
- 10,000+ records  
- Includes customer demographics, policy details, and claims data  
- Features: Age, Gender, Policy Type, Premium Amount, Coverage Amount, Claim Status, Claim Amount  

### 🔹 Customer Feedback Dataset
- Text-based customer reviews  
- Used for sentiment and customer experience analysis  

---

## ⚙️ Tools & Technologies

- **SQL Server** – Data storage and querying  
- **Power BI** – Data visualization and dashboard development  
- **DAX** – KPI calculations and measures  
- **Excel / CSV** – Data sources  

---

## 🧹 Data Cleaning & Transformation

- Converted date columns into proper datetime format  
- Handled missing values in `ClaimDate` (treated as no-claim cases)  
- Identified zero `ClaimAmount` as no-claim or rejected cases  
- Checked and handled duplicate records  
- Created age groups for better segmentation  

---

## 🧠 Feature Engineering

Customer feedback was transformed into structured insights using the following features:

- **Sentiment Category** → Positive / Neutral / Negative  
- **Sentiment Score** → Numerical representation of sentiment  
- **Satisfaction Score** → Quantified customer satisfaction  
- **Urgency Level** → Low / Medium / High priority issues  
- **Issue Flag** → 0 (No Issue) / 1 (Issue Identified)  
- **Feedback Categories** → Claims, Customer Service, Pricing, Website/App, Policy Understanding  

---

## 📈 Dashboard & Analysis

### 🔹 Insurance Analytics
- Total Premium vs Total Claim Amount  
- Policy-wise performance analysis  
- Claim status distribution (Approved, Pending, Rejected)  
- Age group vs claim behavior  

### 🔹 Customer Experience Analytics
- Sentiment distribution  
- Satisfaction score analysis  
- Issue vs No Issue tracking  
- Urgency level insights  
- Sentiment vs Satisfaction correlation  

---

## 💡 Key Insights

- Claim payouts are significantly high compared to premium collected, indicating potential profitability concerns  
- Certain policy types contribute disproportionately to claim frequency  
- ~20% of customers reported issues, highlighting service gaps  
- Customer service delays and claim processing inefficiencies are major pain points  
- Strong positive correlation between sentiment scores and satisfaction levels validates the sentiment model  

---

## 🚀 Business Impact

- Enables identification of high-risk customers and policies  
- Helps improve customer experience through issue detection  
- Supports pricing and policy optimization strategies  
- Allows proactive resolution of high-priority customer concerns  
- Provides data-driven decision-making support  

---

## 🔗 Project Workflow

1. Data Collection (Insurance + Customer Feedback)  
2. Data Cleaning & Validation (SQL Server / Power BI)  
3. Data Transformation  
4. Feature Engineering (Sentiment & CX Metrics)  
5. Dashboard Development (Power BI)  
6. Insight Generation  
7. Deployment (Power BI Service)  

---

## 📸 Dashboard Preview

<img width="1391" height="807" alt="image" src="https://github.com/user-attachments/assets/6bddfdea-296f-42d4-ac9c-a552ab5fb13b" />

<img width="1348" height="787" alt="image" src="https://github.com/user-attachments/assets/9c148770-9d76-4882-9e3f-af039126c898" />

<img width="1381" height="795" alt="image" src="https://github.com/user-attachments/assets/0f14fb9f-5279-40fa-9ca6-83ebfc7a06c6" />



---

## 📌 Conclusion

This project demonstrates how combining structured insurance data with unstructured customer feedback can unlock deeper insights into both operational performance and customer experience.

It highlights the importance of data-driven strategies in improving business efficiency, reducing risk, and enhancing customer satisfaction.

---

## 👤 Author

**Priyanka Panda**

* LinkedIn: [https://www.linkedin.com/in/priyanka-panda-analyst/](https://www.linkedin.com/in/priyanka-panda-analyst/)
* GitHub: [https://github.com/priyankapanda08](https://github.com/priyankapanda08)
