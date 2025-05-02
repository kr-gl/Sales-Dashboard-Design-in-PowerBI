# Sales-Dashboard-Design-in-PowerBI 

## 📝 Objective
Design an interactive dashboard using Power BI to visualize sales performance by product category, region, and time (monthly trend).

### 🧰 Tools Used
- Power BI Desktop
- Dataset: `Sample - Superstore.xls`

### 🗺️ Steps Followed
1. **Data Import**  
   Imported `Sample - Superstore.xls` into Power BI.
2. **Date Transformation**  
   Created a custom column to display order dates in `"MMM YYYY"` format using:
   ```
   MonthYear = FORMAT('Orders'[Order Date], "MMM YYYY")
````
3. **Dashboard Visuals**
   * 📈 **Line Chart** – Monthly Sales trend using `MonthYear`
   * 📊 **Bar Chart** – Total Sales by `Region`
   * 🍩 **Donut Chart** – Total Sales by `Category`
4. **Slicer**
   Added slicers for **Region** and **Category** to filter all visuals dynamically.
5. **Conditional Formatting**
   Highlighted top-performing sales areas using color gradients in charts.

### 💡 **Key Insights**
1. 📍 The **West** region recorded the highest total sales.
2. 💼 **Technology** products had the best sales performance across regions.
3. 🗓️ **December** showed the peak in monthly sales volume.
4. 🧾 The **Office Supplies** category had relatively lower profit margins.

### 📁 **Project Files**
* `Sample - Superstore.xls` – Source dataset
* `Sales_Dashboard.pbix` – Power BI project file

### ✅ **Outcome**
Successfully created a clean, interactive sales dashboard that helps business users analyze regional and categorical sales trends over time.
