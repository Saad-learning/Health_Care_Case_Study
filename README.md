# 🏥 Healthcare BI Case Study – MedCare Group  
**End-to-End Business Intelligence & Data Analytics Project**  
*By Saad Attia | SQL | Python | Power BI | Excel*

---

## 📘 Project Overview

This case study analyzes hospital operations across **five regional branches** of **MedCare Group**, aiming to identify performance gaps, improve **patient satisfaction**, and optimize **financial efficiency**.  

The project demonstrates a **full BI workflow** — from data cleaning in Excel, transformation in SQL Server, advanced analytics in Python, and visualization in Power BI — culminating in a final executive report and predictive insights for 2025.

---

## 🎯 Business Objective

MedCare’s leadership wanted to understand:

- Why is **patient satisfaction** declining?  
- Which departments or regions are causing the drop?  
- How can we reduce **readmission rates** and **wait times**?  
- Which **insurance types** and **treatments** drive profitability?  
- What operational changes can improve outcomes in 2025?

The goal was to build a **centralized BI Dashboard** and **forecasting model** to support data-driven decision-making across all hospital branches.

---

## 🗂️ Dataset Information

**Dataset Name:** `Hospital_Operations.csv`  
**Records:** 1,500 rows  
**Period:** Jan 2024 – Dec 2024  

| **Column** | **Description** | **Example** |
|-------------|----------------|-------------|
| Patient_ID | Unique patient identifier | P10023 |
| Admission_Date | Date of admission | 2024-02-12 |
| Discharge_Date | Date of discharge | 2024-02-16 |
| Department | Medical department | Cardiology |
| Doctor_Name | Attending doctor | Dr. Ahmed Khalil |
| Diagnosis | Primary condition | Hypertension |
| Treatment_Cost | Total treatment cost | 1450.50 |
| Insurance_Type | Type of insurance | Private |
| Satisfaction_Score | Feedback rating (1–10) | 8 |
| Readmission_30Days | Readmitted within 30 days (Y/N) | N |
| Region | Hospital region | East |
| Wait_Time_Minutes | Wait time before first treatment | 45 |
| Doctor_Experience_Years | Doctor’s experience in years | 12 |
| Total_Revenue | Total billed amount | 1850.75 |

---

## 🧩 Project Phases

| **Phase** | **Description** | **Tools Used** |
|------------|-----------------|----------------|
| **Phase 1 – Data Foundation** | Synthetic dataset generation & Excel profiling | Excel |
| **Phase 2 – Data Cleaning & Transformation** | SQL-based data cleaning, type corrections, and KPI creation | SQL Server |
| **Phase 3 – Data Analysis** | Statistical & predictive analysis (correlation, regression, forecasting) | Python (Pandas, Matplotlib, PyODBC) |
| **Phase 4 – Dashboard Visualization** | Power BI interactive report creation | Power BI |
| **Phase 5 – Business Insights & Reporting** | Executive summary & recommendations | Markdown / PDF |
| **Phase 6 – Portfolio Presentation** | GitHub + LinkedIn publishing | Markdown / Figma |

---

## ⚙️ Tools & Technologies

| **Tool** | **Purpose** |
|-----------|-------------|
| **Excel** | Data profiling and initial cleaning |
| **SQL Server** | Data storage, transformation, and KPI calculations |
| **Python (Pandas, Matplotlib)** | Statistical analysis and forecasting |
| **Power BI** | Dashboard visualization and storytelling |
| **Markdown / GitHub** | Documentation and presentation |

---

## 📊 Key KPIs

| **KPI** | **Definition** |
|----------|----------------|
| **Average Length of Stay (ALOS)** | Average duration between admission and discharge |
| **Readmission Rate (30 Days)** | % of patients readmitted within 30 days |
| **Average Satisfaction Score** | Average patient feedback score (1–10) |
| **Total Revenue & Profit Margin** | Hospital financial performance |
| **Bed Occupancy Rate** | Resource utilization rate by department |

---

## 🧠 Analytical Insights

### **Operational**
- **Cardiology & Orthopedics** → Longest patient stays (5.6 days avg)  
- **Pediatrics** → Highest satisfaction (8.9/10) with shortest stays  
- **Wait Time vs Satisfaction correlation** → r = **–0.63**

### **Regional**
- **North Region** → Highest readmission (12%)  
- **East Region** → Highest satisfaction (8.4/10) and lowest wait times

### **Financial**
- **Private Insurance** → 62% of revenue, 24% margin  
- **Public Insurance** → 8% margin, longer stay duration  

### **Predictive**
- **Admissions forecast** → +6% growth expected in 2025  
- **Satisfaction forecast** → +0.5 points increase if wait time reduced by 15%  
- **Revenue forecast** → +8.5% YoY growth

---

## 📈 Power BI Dashboard Highlights

### **KPI Cards**
- Total Revenue  
- Average Length of Stay (ALOS)  
- Readmission Rate (%)  
- Average Satisfaction Score  

### **Charts**
- Bar Chart → Revenue & Profit by Department  
- Donut Chart → Insurance Type Revenue Share  
- Line Chart → Monthly Admissions Trend  
- Stacked Bar → Wait Time vs Satisfaction by Region  
- Heatmap → Readmission % by Department & Diagnosis  

### **Filters**
- Year | Region | Department | Doctor | Insurance Type

---

## 🧾 Folder Structure
