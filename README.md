
# 📊 Data Cleaning & Analysis with Excel PivotTables

## 📖 Overview
This project demonstrates the full workflow of **data cleaning** and **data analysis** using **Excel PivotTables**. and ** VLOOKUP** 
The goal is to transform raw, messy datasets into clean, structured data and then extract meaningful insights using PivotTables and VLOOKUP.

---

## 🛠️ Tools & Technologies
- **Microsoft Excel** – PivotTables, PivotCharts, Power Query

---

## 🔄 Data Cleaning Process
1. **Handle Missing Values**  
   - Impute with mean/median or mark as "Unknown".
2. **Remove Duplicates**  
   - Ensure unique records for accurate analysis.
3. **Standardize Formats**  
   - Dates converted to `YYYY-MM-DD`, text trimmed and normalized.
4. **Outlier Detection**  
   - Identify extreme values using IQR or Z-score.
5. **Consistency Checks**  
   - Ensure data types are correct (numeric, categorical, date).

---

## 📊 Data Analysis with Excel PivotTables
1. **Import Cleaned Data** into Excel.
2. **Create PivotTable** to summarize:
   - Sales by Region
   - Average Purchase Amount by Age Group
   - Monthly Trends
   - Top Customers
3. **Add PivotCharts** for visualization:
   - Bar charts for regional sales
   - Line charts for monthly trends
   - Pie charts for customer segments
4. **Use Slicers & Filters** for interactive exploration.

---

## 🔍 Using VLOOKUP for Data Cleaning & Analysis

**VLOOKUP** is an Excel function that searches for a value in the first column of a range and returns a value in the same row from another column. It is especially useful for **data cleaning, validation, and combining datasets**.

### 📌 Syntax
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])


- **lookup_value** → The value you want to search for.  
- **table_array** → The range of cells containing the data.  
- **col_index_num** → The column number in the table from which to retrieve the value.  
- **range_lookup** → TRUE (approximate match) or FALSE (exact match).  

---

### 💡 Practical Uses in Data Cleaning
1. **Fill Missing Values**  
   - Use VLOOKUP to pull missing customer details (like age or region) from a master dataset.  

2. **Standardize Data Across Sheets**  
   - Match product IDs in one sheet with product names in another.  

3. **Detect Inconsistencies**  
   - Compare two datasets (e.g., sales vs inventory) to find mismatches.  

4. **Merge Datasets Without Duplicates**  
   - Combine customer info from multiple sources into one clean table.  

---



## 🚀 How to Run
1. Open `cleaned_sales.csv` in Excel.  
2. Insert a PivotTable → Drag fields into Rows, Columns, Values, Filters.  
3. Add PivotCharts for visualization.  
4. Explore insights interactively using slicers.  

---

## ✅ Conclusion
This project highlights the importance of **data cleaning** as the foundation of reliable **data analysis**.  
 **Excel PivotTables**, analysts can deliver accurate insights and professional dashboards.

---


## 📂 Project Structure
