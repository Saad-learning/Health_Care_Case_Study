#  Healthcare BI Case Study – Full Execution Plan

##  Objective
To analyze hospital operations data across multiple branches to improve patient satisfaction, reduce operational inefficiencies, and enhance decision-making using Business Intelligence techniques.

---

##  Phase 1 – Data Foundation & Setup

### 🔹 Task 1: Synthetic Dataset Generation
- Generate a dataset `Hospital_Operations.csv` (1,500 records) simulating real hospital data.
- Columns: Patient_ID, Admission_Date, Discharge_Date, Department, Doctor, Diagnosis, Treatment_Type, Cost, Insurance, Wait_Time, Satisfaction_Score, etc.
- Ensure realistic value ranges (e.g., satisfaction 1–10, wait times 5–180 minutes).

**Deliverables:**
- `Hospital_Operations.csv`
- Data dictionary (column descriptions + units)

---

### 🔹 Task 2: Data Import & Quality Review (Excel)
- Load dataset into Excel.
- Perform initial data profiling:
  - Check for missing values, duplicates, incorrect dates, outliers.
  - Validate date difference between Admission and Discharge.
- Add helper columns:
  - `Length_of_Stay = Discharge_Date - Admission_Date`
  - `Profit = Total_Revenue - Treatment_Cost`

**Deliverables:**
- Cleaned Excel file  
- Summary sheet of basic statistics per column  

---

## Phase 2 – Data Cleaning & Transformation (SQL + Excel)

### 🔹 Task 3: Load Data into SQL Server
- Create a new database: `Healthcare_CaseStudy`
- Import the cleaned Excel file into table `Hospital_Operations`
- Define appropriate datatypes (DATE, VARCHAR, FLOAT, etc.)

**Deliverables:**
- SQL table `Hospital_Operations`  
- SQL import script  

---

### 🔹 Task 4: Data Cleaning using SQL
- Handle NULLs or inconsistent entries:
  - Replace missing values logically (e.g., satisfaction = avg per department)
  - Remove impossible durations (negative stay length)
- Standardize categorical data (e.g., Insurance Type, Department names)

**Deliverables:**
- Cleaned SQL table ready for analysis  
- SQL script for all transformations  

---

### 🔹 Task 5: Create Derived Metrics in SQL
- Create calculated fields:
  - `Length_of_Stay`
  - `Bed_Occupancy_Rate`
  - `Avg_Wait_Time_Department`
  - `Revenue_Per_Patient`
  - `Readmission_Rate_Department`
- Use **Window Functions** to calculate KPIs by Department, Doctor, Region.

**Deliverables:**
- SQL queries producing key metrics  
- KPI summary table  

---

##  Phase 3 – Data Analysis (SQL + Python)

### 🔹 Task 6: Descriptive & Diagnostic Analysis (SQL)
Perform analytical queries to answer stakeholder questions:
- Which departments have the longest average stays?
- Which region has the highest readmission rate?
- Which insurance type contributes the most to revenue?
- What is the correlation between wait time and satisfaction?

**Deliverables:**
- SQL script of insights queries  
- Summary of findings in Markdown  

---

### 🔹 Task 7: Advanced Analytics (Python + SQL)
- Connect Python to SQL Server using `pyodbc`.
- Retrieve cleaned dataset directly into Pandas.
- Perform statistical and predictive analysis:
  - Correlation heatmap for all numeric features.
  - Forecast patient admissions per department using Time Series.

**Deliverables:**
- Jupyter Notebook (SQL + Python workflow)
- Visualizations (matplotlib/seaborn)
- Predictive model output  

---

##  Phase 4 – Business Intelligence Visualization (Power BI)

### 🔹 Task 8: Connect SQL Server to Power BI
- Import the SQL table `Hospital_Operations`
- Create relationships if additional dimension tables are added (Departments, Doctors, etc.)

**Deliverables:**
- Power BI dataset connection setup  

---

### 🔹 Task 9: Create BI Dashboard
**Core Visuals:**
1. **KPI Cards:**  
   - Total Revenue  
   - Average Length of Stay (ALOS)  
   - Readmission Rate (%)  
   - Average Satisfaction Score  

2. **Charts:**  
   - Bar Chart → Revenue & Profit by Department  
   - Donut Chart → Insurance Type Revenue Share  
   - Line Chart → Monthly Admissions Trend  
   - Stacked Bar → Wait Time vs. Satisfaction by Region  
   - Heatmap → Readmission % by Department & Diagnosis  

3. **Interactive Filters:**  
   - Year, Region, Department, Doctor, Insurance Type  

4. **Forecast Visuals (Advanced):**  
   - Predicted Admissions (next month)  
   - Expected Satisfaction improvement if wait time reduces by X%

**Deliverables:**
- Power BI Dashboard (`Healthcare_BI_Report.pbix`)
- Screenshots of main visuals for portfolio  

---

##  Phase 5 – Business Insights & Reporting

### 🔹 Task 10: Generate Executive Insights Report
Summarize key takeaways from the BI dashboard:
- Root causes of low satisfaction (e.g., long wait times, short doctor experience)
- Profitability insights by insurance type or treatment
- High readmission departments (actionable areas)
- Forecast results (expected trends for 2025)
- Recommendations for hospital management

**Deliverables:**
- Markdown / PDF report titled `Healthcare_BI_Insights_Report`
- Visual summary of KPIs  

---

##  Phase 6 – Portfolio Presentation

### 🔹 Task 11: Prepare Portfolio Artifacts
- Jupyter Notebook (SQL + Python combined workflow)
- Power BI dashboard screenshots
- Markdown summary for GitHub & LinkedIn
- Visual cover page in dark sleek style (for your book-style post)

**Deliverables:**
- `/Case Studies/Healthcare_BI_CaseStudy/` folder structure  
- GitHub-ready README.md with visuals and results  
- LinkedIn post template  

---

##  Summary of Workflow

| **Tool** | **Purpose** | **Output** |
|-----------|--------------|-------------|
| **Excel** | Initial cleaning, exploration | Clean dataset |
| **SQL Server** | Data storage, transformation, KPI generation | Structured tables |
| **Python** | Predictive analysis & visual exploration | Insights notebook |
| **Power BI** | Dashboard visualization & storytelling | Executive report |
| **Markdown / PDF** | Final documentation | Case study report |

---

##  Final Outcome

- **Dataset:** Realistic hospital operations data (1,500 records)
- **BI Dashboard:** Interactive Power BI report
- **Analytics Notebook:** SQL + Python workflow
- **Case Study Report:** Business findings and recommendations
- **Portfolio Integration:** Ready-to-show project for Data Analyst / BI Analyst roles
