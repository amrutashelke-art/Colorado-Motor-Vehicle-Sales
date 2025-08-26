# Colorado Motor Vehicle Sales Analysis

## 📌 Project Overview
This project analyzes motor vehicle sales across different counties in Colorado from 2008 to 2015. 
The objective is to identify trends, regional disparities, and seasonal variations in sales performance. 
By examining this dataset, we can better understand the economic recovery following the 2008 financial crisis and 
how different counties contributed to overall vehicle sales.

## 📊 Dataset Description
- **File:** colorado_motor_vehicle_sales.csv  
- **Rows:** 501  
- **Columns:** 4 (`year`, `quarter`, `county`, `sales`)  
- **Years Covered:** 2008–2015  
- **Counties:** 17 (e.g., Adams, Denver, Arapahoe, Jefferson, etc.)  
- **Sales Range:** $6.2 million – $916.9 million per quarter  

The dataset records **quarterly sales values** for each county. It is well-structured with no major missing values.  

## 🔎 Analysis Performed
1. **Data Cleaning & Preprocessing** – Ensured consistency, verified data types, and checked for missing values.  
2. **Exploratory Data Analysis (EDA)** – Descriptive statistics, year-wise and county-wise breakdowns.  
3. **Trends Across Years** – Analysis of post-2008 crisis decline and recovery from 2010 onwards.  
4. **Quarterly Variations** – Identified seasonality, with stronger sales in Q2 and Q3.  
5. **County-Level Insights** – Compared urban vs. rural counties, highlighting disparities.  

## 📈 Key Findings
- Sales dropped significantly after the **2008 financial crisis**, followed by recovery from 2010 onwards.  
- **Urban counties** like Denver, Arapahoe, and Jefferson consistently outperformed rural counties.  
- **Quarterly patterns** showed peaks in Q2 and Q3 due to consumer demand, promotions, and favorable conditions.  
- Sales variation across counties was large, reflecting differences in population, income, and employment.  

## 📂 Project Structure
```
├── colorado_motor_vehicle_sales.csv   # Dataset
├── UMA colorado_motor_vehicle_sales.ipynb   # Jupyter Notebook with analysis
├── Colorado_Motor_Vehicle_Sales_Report.docx # Detailed 10-page project report
├── README.md                           # Project documentation
```

## 🚀 How to Run the Notebook
1. Clone the repository or download the project files.  
2. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook "UMA colorado_motor_vehicle_sales.ipynb"
   ```
3. Install required dependencies (if any).  
4. Run the cells sequentially to reproduce the analysis.  

## 🔮 Future Work
- Add **predictive modeling** to forecast future vehicle sales.  
- Integrate additional features like fuel prices, demographics, and loan interest rates.  
- Conduct a more granular study of **vehicle categories** (SUVs, trucks, electric cars).  

---  
📌 **Author:** Amruta Shelke  
