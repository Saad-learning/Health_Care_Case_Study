# 🏥 Healthcare BI Insights Report  
**Project:** MedCare Group – Hospital Operations & Patient Satisfaction Analysis  
**Prepared by:** Saad Attia  
**Tools Used:** Excel | SQL Server | Python (Pandas, Matplotlib) | Power BI  
**Date:** October 2025  

---

## **1. Executive Summary**

MedCare Group, a network of five regional hospitals, faced declining patient satisfaction (–12%) and increased operational costs.  
To address this, a Business Intelligence solution was developed to unify patient, financial, and operational data.  

The analysis identified critical efficiency gaps, root causes of patient dissatisfaction, and profitability patterns across departments.  
The project culminated in an interactive Power BI dashboard providing real-time insights and predictive trends.

---

## **2. Key KPIs Overview**

| **Metric** | **Definition** | **Result (2024)** | **Interpretation** |
|-------------|----------------|-------------------|--------------------|
| **Average Length of Stay (ALOS)** | Average days between admission & discharge | 4.2 days | Within industry benchmark |
| **Average Satisfaction Score** | Mean patient-reported score (1–10) | 7.8 | Slightly below target (8.5) |
| **Readmission Rate (30 Days)** | % of patients readmitted within 30 days | 9.5% | Higher than desired threshold (≤7%) |
| **Total Revenue** | Cumulative billed amount | \$28.4M | Strong top-line growth |
| **Profit Margin** | (Revenue – Cost) / Revenue | 18% | Healthy but varies by department |

---

## **3. Operational Insights**

### 🏨 **Department Performance**
- **Cardiology** and **Orthopedics** show **above-average length of stay (ALOS)** — 5.6 and 5.3 days respectively.  
- **Pediatrics** has the **shortest stays** but also **highest satisfaction** (avg. 8.9).  
- Departments with **longer wait times** correlate with **lower satisfaction** (r = –0.63).

### 🌍 **Regional Trends**
- **North Region** had the **highest readmission rate (12%)**, driven by recurring chronic cases.  
- **East Region** achieved the **highest satisfaction (8.4)** due to lower wait times and better staffing balance.

### 👩‍⚕️ **Doctor Workload Analysis**
- Doctors handling **>20 patients/month** had an **average satisfaction score drop of 0.8 points**, suggesting burnout or time constraints.  
- Doctors with **10–15 years of experience** achieved the **best satisfaction outcomes**.

---

## **4. Financial & Efficiency Insights**

### 💰 **Profitability**
- **Private insurance patients** contributed **62% of total revenue**, with a **24% margin**.  
- **Public insurance** cases were less profitable (margin 8%), mostly due to longer treatment durations and lower reimbursement rates.  

### 🛏️ **Resource Utilization**
- **Average Bed Occupancy Rate:** 78% (Optimal: 80–85%)  
- **Surgery & ICU wards** occasionally exceeded capacity (>90%), leading to delayed admissions.  

### ⏱️ **Wait Time & Satisfaction Correlation**
- Each **10-minute increase in wait time** leads to a **0.15-point drop in satisfaction**.  
- Departments reducing wait time by 20% saw a measurable satisfaction increase (+0.9).

---

## **5. Diagnostic Findings**

| **Issue** | **Impact** | **Root Cause** |
|------------|-------------|----------------|
| Long Wait Times | ↓ Satisfaction | Staff shortages & poor scheduling |
| High Readmission (Cardiology, North Region) | ↑ Costs | Lack of post-discharge monitoring |
| Variable Profit Margins | Uneven resource allocation | Overutilized vs. underutilized departments |
| Declining Satisfaction | Brand reputation risk | Doctor workload imbalance, long waits |

---

## **6. Predictive Insights (2025 Forecast)**

| **Forecast Metric** | **Predicted Value** | **Insight** |
|----------------------|---------------------|--------------|
| **Monthly Admissions (avg)** | +6% growth | Seasonal surge expected in Q1–Q2 |
| **Expected Satisfaction (avg)** | 8.3 (+0.5) | If wait time reduced by 15% |
| **Projected Revenue Growth** | +8.5% | Driven by improved throughput and private cases |

*Forecasting performed using Python (Time Series and Regression models).*

---

## **7. Recommendations for Executives**

### 🩺 **Operational Improvements**
- Implement **dynamic staffing** in high-demand departments (Cardiology, Orthopedics).  
- Introduce **automated scheduling** to balance workload and reduce wait times.  
- Develop **post-discharge follow-up programs** to lower readmissions.

### 💵 **Financial Strategy**
- Reevaluate **insurance mix** to prioritize profitable treatment plans.  
- Standardize **cost controls** for long-stay cases.

### 😊 **Satisfaction Enhancement**
- Launch **patient feedback loop** for real-time service rating.  
- Offer **wellness & efficiency training** for high-workload doctors.  
- Target **wait time <30 minutes** hospital-wide.

---

## **8. Conclusion**

The BI solution transformed scattered data into actionable intelligence, enabling MedCare to make **data-driven operational and financial decisions**.  
By focusing on wait time optimization, workload balancing, and post-care monitoring, MedCare can expect to improve patient satisfaction and reduce inefficiencies significantly in 2025.  

---
