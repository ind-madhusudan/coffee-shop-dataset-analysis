# ☕ Coffee Shop Dataset Analysis

![](https://github.com/ind-madhusudan/coffee-shop-dataset-analysis/blob/main/excel_dashboard.png)

## 🎯 Project Objectives
The main objective of this project is to analyze retail sales data to gain actionable insights that will enhance the performance of the Coffee Shop.

## 📊 Dataset Used
- Link to the dataset: [Coffee Shop Data](https://github.com/ind-madhusudan/coffee-shop-dataset-analysis/blob/main/coffee_shop_sales_report.xlsx)

## ❓ Questions (KPIs)

1. [**How do sales vary by day of the week and hour of the day?**](#kpi-1)
2. [**Are there any peak times for sales activity?**](#kpi-2)
3. [**What is the total sales revenue for each month?**](#kpi-3)
4. [**How do sales vary across different store locations?**](#kpi-4)
5. [**What is the average price/order per person? Which products are the bestselling in terms of quantity and revenue?**](#kpi-5)
6. [**How do sales vary by product category and type?**](#kpi-6)

## 📈 KPI Analysis

### <a name="kpi-1"></a>1. **How do sales vary by day of the week and hour of the day?**  
   - **Morning Rush (8 AM - 10 AM):**  
     Coffee sales peak during the morning hours, especially between 8 AM and 10 AM, as people grab their coffee to start their day.
   - **Day Preferences (Monday, Thursday, Friday):**  
     Mondays, Thursdays, and Fridays see higher traffic, with people seeking a caffeine boost during the start and end of the week.
   
### <a name="kpi-2"></a>2. **Are there any peak times for sales activity?**  
   - **Peak Sales Time (10 AM on Fridays):**  
     Friday mornings around 10 AM mark the highest sales activity, driven by a combination of end-of-week routines and social gatherings.

### <a name="kpi-3"></a>3. **What is the total sales revenue for each month?**  
   - **Top Performing Month (June):**  
     June generates the highest revenue, possibly due to summer vacations and increased social activities.
   - **Other High-Performing Months (May and April):**  
     May and April follow closely, suggesting a steady sales momentum during late spring and early summer.

### <a name="kpi-4"></a>4. **How do sales vary across different store locations?**  
   - **Top-Performing Location (Hell's Kitchen):**  
     Hell's Kitchen leads in sales, likely due to high foot traffic and proximity to popular attractions.
   - **Second Lead (Astoria):**  
     Astoria shows strong performance, driven by a mix of regular customers and a residential appeal.

### <a name="kpi-5"></a>5. **What is the average price/order per person? Which products are the bestselling in terms of quantity and revenue?**  
   - **Average Price per Person ($4.69):**  
     The average spend is moderate, showing a balance between affordability and perceived value.
   - **Average Order Size (1.44):**  
     Most customers buy one product with occasional add-ons.
   - **Bestselling Product by Quantity (Brewed Chai Tea):**  
     Brewed Chai Tea dominates with approximately 26.25k units sold.
   - **Top Product by Revenue (Barista Espresso - $91.41k):**  
     Barista Espresso generates the most revenue, highlighting its premium pricing.

### <a name="kpi-6"></a>6. **How do sales vary by product category and type?**  
   - **Sales by Product Category (Coffee Products - 39%):**  
     Coffee products are the largest category, driving significant revenue.
   - **Top Product Type (Barista Espresso - 22%):**  
     Barista Espresso stands out as a top-selling product type, contributing 22% to overall sales.

### 7. Dashboard Link
- [Click here to view dashboard](https://github.com/ind-madhusudan/coffee-shop-dataset-analysis/blob/main/excel_dashboard.png)

## 📝 Process

### 🧹 Data Preparation
Here are the key steps involved in preparing the dataset for analysis:

1. **Import the Dataset**  
   - Load the dataset into your analysis environment (e.g., Python, R, Excel).
   - If using Python, use `pandas` to load CSV files with `pd.read_csv()`.

2. **Data Cleaning**  
   - **Handle Missing Data:**
     - Identify and fill or remove missing values using appropriate techniques (`fillna()`, `dropna()` in Python).
   - **Remove Duplicates:**
     - Check for duplicate rows and remove if necessary.
   - **Trim Spaces:**  
     - Remove leading or trailing spaces in text fields (e.g., `.strip()` method in Python or Excel's TRIM function).
   - **Find & Replace:**  
     - Standardize text entries (e.g., replace inconsistent values like "coffee" vs "Coffee").
   - **Verify Consistency:**  
     - Ensure column formats are correct, e.g., date columns should be of `datetime` type.

3. **Format Date and Time Columns**  
   - Convert columns related to date and time into the correct formats for analysis.
4. **Standardize Product Categories and Locations**  
   - Ensure that product categories and store locations are consistent (e.g., "espresso" vs. "Espresso").  

5. **Remove Outliers and Errors**  
   - Identify and handle outliers or incorrect data values (e.g., sales values that are negative or excessively high).

6. **Created New Variables**  
   - Derived new columns such as "Month", "Day of Week", or "Hour of Day" based on existing date and time information.

7. **Verify Data Consistency and Correctness**  
   - Run basic checks to ensure that the data looks correct and is ready for analysis.

### 🔍 Exploratory Data Analysis (EDA)
- **Descriptive statistics:** Generate statistics for sales, revenue, and orders.
- **Sales trends:** Visualize sales trends by time (daily, weekly, monthly).
- **Sales distribution:** Plot sales by location and product categories.
- **Peak times:** Use scatter plots or heatmaps to identify peak sales times.

### 📊 KPI-Specific Analysis
- **Sales by Day and Time:**  
  Group data by day of the week and hour to calculate total sales.
- **Peak Sales Times:**  
  Identify the highest sales volume times and days.
- **Monthly Sales Revenue:**  
  Aggregate monthly data to track revenue trends.
- **Sales Across Locations:**  
  Compare sales across different store locations.
- **Average Price Per Order:**  
  Calculate average sales per order.
- **Bestselling Products:**  
  Identify top-selling products by quantity and revenue.
- **Sales by Category/Type:**  
  Analyze sales performance by product category or type.

## 💻 Technologies for Dataset Analysis in Excel

- **Excel Software**
- **Formulas & Functions:**  
  SUM, AVERAGE, COUNTIF, VLOOKUP, INDEX-MATCH, IF, TEXT, DATE & TIME functions.
- **Pivot Tables:**  
  Summarize and analyze data dynamically.
- **Charts & Graphs:**  
  Visualize trends (bar, line, scatter).
- **Data Cleaning:**  
  Remove duplicates, trim spaces, find/replace, data validation, Power Query (optional).
- **Conditional Formatting:**  
  Highlight key data points.
- **Sorting & Filtering:**  
  Organize data for deeper insights.
- **Data Analysis Toolpak:**  
  Statistical analysis (regression, correlation).
- **What-If Analysis:**  
  Goal Seek, Data Tables for scenario modeling.

## 🤝 Contributing
- Feel free to fork the repository, submit issues, and send pull requests. Contributions are welcome!

## 📝 License
- This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
