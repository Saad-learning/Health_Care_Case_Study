# 🏥 Healthcare Case Study – Business Intelligence & Data Analysis

##  Stakeholder Background & Meeting Transcript

##  Project Background

The project is initiated by **MedCare Group**, a network of 5 regional hospitals operating across the country.  
Over the last year, the organization faced **declining patient satisfaction** and **rising operational costs**.  
Leadership decided to invest in **Business Intelligence** to gain actionable insights and improve overall hospital performance.

The goal was to design a **centralized BI solution** that integrates patient, financial, and operational data — enabling real-time decision-making and improving healthcare outcomes.

---

##  Stakeholder Meeting Transcript – Kickoff Session

**Date:** 10 February 2024  
**Location:** MedCare HQ, Executive Conference Room  
**Attendees:**  
- **Dr. Sarah Williams** (Chief Medical Officer)  
- **Mark Thompson** (Head of Operations)  
- **Lisa Rodriguez** (BI & Analytics Manager – *Your Role*)  
- **IT Department Representative**

---

### **Opening**

> **Dr. Sarah:**  
> “Our hospitals are under strain. Patient satisfaction has dropped 12% this quarter. We’re also seeing inconsistent bed utilization — some departments are overbooked while others have idle capacity.”

> **Mark:**  
> “We need data-backed decisions. I want to know *which regions and departments* are struggling the most. For example, how long are patients waiting before treatment? Are we overstaffed or understaffed during certain shifts?”

> **Lisa (You):**  
> “I propose we develop a BI dashboard that integrates data from all five hospitals. It’ll highlight KPIs like patient flow, bed occupancy, treatment costs, and readmission rates. We can also include satisfaction trends and predictive forecasts.”

> **Dr. Sarah:**  
> “Excellent. And please ensure it’s easy for department heads to filter by *region, doctor, or diagnosis*. We want clarity, not complexity.”

> **Mark:**  
> “Agreed. I also want a focus on operational efficiency — linking *costs, staffing, and patient outcomes*. Let’s be able to see if a higher doctor workload impacts satisfaction.”

> **Saad (Me):**  
> “Understood. We’ll start with a historical dataset of 12 months — admissions, treatments, satisfaction, costs, and insurance data — then move to trend and predictive modeling.”

> **Dr. Sarah:**  
> “That’s a solid plan. Let’s make sure the insights help us improve patient care while maintaining financial balance.”

---

##  Business Objectives Defined

1. Identify the **root causes of patient dissatisfaction**  
2. Analyze **bed utilization** and **department efficiency**  
3. Monitor **readmission rates** and related diagnoses  
4. Evaluate **doctor workload vs. satisfaction impact**  
5. Understand **treatment cost vs. revenue performance**  
6. Build an **executive BI dashboard** with KPIs for all hospital branches  
7. Develop a **forecast model** for patient inflow and resource needs  

---

##  Data Scope

- Historical records from **Jan 2024 – Dec 2024**
- Data integrated from 5 regional hospitals
- Sources: Electronic Medical Records (EMR), Financial Systems, Patient Feedback Surveys
- Output: Clean, analytical dataset ready for BI and ML

##  Business Requirements

| **Category** | **Requirement** | **Description** |
|---------------|-----------------|-----------------|
| **1. Patient Flow** | Analyze patient admissions, discharges, and average length of stay | Identify peak admission days and average stay durations by department |
| **2. Department Efficiency** | Evaluate each department’s workload and performance | Compare patient volume, treatment success, and satisfaction per department |
| **3. Financial Performance** | Track hospital revenue, costs, and profit per service | Analyze cost per treatment and profitability trends |
| **4. Resource Utilization** | Monitor doctor workload and bed occupancy | Understand how staffing and occupancy affect wait times |
| **5. Readmission Analysis** | Identify high-risk conditions causing readmissions | Support preventive care programs |
| **6. Patient Satisfaction** | Measure satisfaction by treatment type, department, and doctor | Link satisfaction trends with operational factors |
| **7. Predictive Insight (Advanced)** | Forecast patient volume and resource needs | Use historical trends for proactive decision-making |
| **8. Executive KPIs** | Create unified KPIs dashboard | Include: ALOS, Bed Occupancy Rate, Readmission %, Satisfaction Score, Cost per Patient |

---

##  Dataset Initialization

**Dataset Name:** `Hospital_Operations`

| **Column Name** | **Description** | **Example** |
|------------------|-----------------|--------------|
| `Patient_ID` | Unique patient identifier | P10023 |
| `Admission_Date` | Date patient was admitted | 2024-02-12 |
| `Discharge_Date` | Date patient was discharged | 2024-02-16 |
| `Department` | Department handling treatment | Cardiology |
| `Doctor_ID` | Attending doctor ID | D045 |
| `Doctor_Name` | Name of the doctor | Dr. Ahmed Khalil |
| `Diagnosis` | Primary condition | Hypertension |
| `Treatment_Type` | Type of treatment performed | Inpatient |
| `Treatment_Cost` | Total treatment cost | 1450.50 |
| `Insurance_Type` | Type of insurance coverage | Private |
| `Satisfaction_Score` | Patient feedback (1–10) | 8 |
| `Readmission_30Days` | Whether readmitted within 30 days (Y/N) | N |
| `Bed_ID` | Bed assigned during stay | B12 |
| `Region` | Hospital branch region | East |
| `Wait_Time_Minutes` | Time before first treatment | 45 |
| `Doctor_Experience_Years` | Doctor’s experience | 12 |
| `Age` | Patient’s age | 54 |
| `Gender` | Patient gender | F |
| `Total_Revenue` | Derived: total billed amount | 1850.75 |

---

##  Analysis & Insights Plan

###  1. Descriptive Analysis (Excel / SQL)
- Calculate **Average Length of Stay (ALOS)**
- Total Revenue & Average Treatment Cost per Department
- Patient Volume by Region and Department
- Bed Occupancy Trends
- Doctor Performance Summary (Patients handled, Avg Satisfaction)

###  2. Diagnostic Analysis (SQL / Python)
- Correlation between Wait Time and Satisfaction
- Root cause analysis for high readmission departments
- Cost vs. Revenue comparison by Insurance Type

###  3. Predictive Analysis (Python)
- Forecast next month’s patient volume
- Predict expected occupancy rate
- Identify satisfaction drivers using regression analysis

###  4. Prescriptive Insights (Power BI)
- Department Performance Overview
- Regional Comparison Dashboard
- Readmission Risk Matrix
- Executive KPIs
- Forecasting Cards and Trends

---

##  Execution Plan

| **Step** | **Tool** | **Description** | **Output** |
|-----------|-----------|-----------------|-------------|
| **1. Data Preparation** | Excel | Initial cleaning (missing values, date parsing, cost corrections) | Clean CSV file |
| **2. Data Storage** | SQL Server | Load dataset into table `Hospital_Operations` | Centralized data repository |
| **3. Data Transformation** | SQL | Aggregations, joins, and window functions | Analytical tables |
| **4. Advanced Analysis** | Python + SQL | Correlation, regression, forecasting | Jupyter Notebook |
| **5. Visualization & Reporting** | Power BI | Build KPI dashboard and predictive visuals | Interactive BI report |
| **6. Business Presentation** | Markdown / PDF | Summarize findings and business recommendations | Final Case Study Document |

---