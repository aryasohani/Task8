# 📊 Sales Performance Dashboard – Power BI  

## 🎯 Objective  
This project is part of a Data Analyst Internship task. The goal is to design a simple interactive dashboard in **Power BI** that shows sales performance by **Month-Year**, **Region**, and **Category**, and to summarize key insights.  

## 📂 Dataset  
- **Source:** Superstore Sales dataset (provided in `.xls` format)  
- **Columns Used:**  
  - `Order Date`  
  - `Region`  
  - `Category`  
  - `Sales`  
  - `Profit`  

## 🛠 Tools  
- Power BI Desktop  
- DAX (for calculated fields)  

## 📌 Steps Performed  
1. **Imported Dataset** into Power BI from Excel file.  
2. **Data Cleaning**:  
   - Verified data types (Date, Text, Decimal).  
   - Created a **Month-Year** column using DAX:  
     ```DAX
     MonthYear = FORMAT('Sheet1'[Order Date], "MMM-YYYY")
      
3. **Dashboard Design**:  
   - **Line Chart** → Sales trend over Month-Year  
   - **Bar Chart** → Sales by Region  
   - **Donut Chart** → Sales by Category  
   - **Slicer** → Region filter  
4. **Styling & Layout**:  
   - Applied consistent colors  
   - Added a clear title: *Sales Performance Dashboard*  

## 📸 Dashboard Preview  
*(Attach screenshot or exported PDF of your Power BI dashboard here)*  

## 🔍 Key Insights  
1. The **West region** recorded the highest overall sales.  
2. The **Technology category** generated the largest revenue share.  
3. Sales consistently **peaked in December** across regions.  
4. **Furniture sales** performed poorly in the South region.  
