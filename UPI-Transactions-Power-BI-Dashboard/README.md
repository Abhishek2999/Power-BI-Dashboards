# Power BI Dashboard - UPI Transactions Analysis
## 📌 Project Overview
This Power BI project analyzes UPI (Unified Payments Interface) transaction data. The goal is to transform raw transaction data into meaningful insights using Power BI's data visualization and reporting capabilities.

### 📊 Dataset Description 
The dataset consists of UPI transaction details extracted from an Excel workbook. The key columns in the dataset include:
-	Transaction Details: Transaction ID (unique identifier), Date & Time (timestamp), Amount (value), Status (Success/Failed), Remaining Balance (post-transaction), Currency type 
-	Participant Information: Bank Names (Sender & Receiver), Customer Gender & Age, Customer & Merchant Account Numbers (text format) 
-	Transaction Characteristics: Transaction Type (Transfer, Payment), Purpose (Bill Payment, Shopping, Travel, Food, Others), Payment Mode (Instant/Scheduled) 
-	Method & Location: Payment Method (Phone Number, QR Code, UPI ID), City, Device Type (Laptop, Mobile, Tablet) 
-	Merchant Data: Merchant Name (e.g., Amazon, Flipkart, Swiggy, Zomato, IRCTC)

  ## 📊 Dataset Used
  -  <a href="https://github.com/Abhishek2999/Power-BI-Dashboards/blob/main/UPI-Transactions-Power-BI-Dashboard/UPI%2BTransactions.xlsx">Dataset</a>
  

### 🔄 Data Cleaning & Transformation
The following transformations were applied using Power Query Editor
-	Renamed Sheet1 to 'UPI Transactions' for better clarity.
-	Converted Account Numbers to Text format to prevent errors in numerical representation.
-	Extracted Transaction Time by splitting the date-time column and removing the unwanted date component.
-	Checked for Data Type Consistency across all columns to ensure proper data representation.
-	Performed Data Profiling to check for null values, blanks, or errors in the dataset.
-	Applied Conditional Formatting to enhance visualization.
-	Synced Slicers across different report pages for consistent filtering.
-	I created a DAX Column for age grouping to categorize customers based on age.

### 📈 Power BI Visualizations
Key visualizations included in the dashboard:
-	Total Transaction Volume & Value: Aggregate view of UPI transactions.
-	Success vs. Failed Transactions: Insights into transaction success rates.
-	Transaction Type Distribution: Comparison between Transfers and Payments.
-	Top Merchants & Categories: Identifying popular merchants and transaction purposes.
-	Device & Payment Method Analysis: Understanding user preferences in transaction execution.
-	Demographic Trends: Insights based on gender, age, and location.
-	Monthly Trends Visualization: Displayed via a Line Chart and a Column Chart (switchable using bookmarks).
-	Matrix Visualization: Used to compare transaction values across different dimensions (Cities, Currencies, and Time).

## Dashboard

![GIF Description](https://github.com/Abhishek2999/Power-BI-Dashboards/blob/main/UPI-Transactions-Power-BI-Dashboard/UPI%20Transactions%20Dashboard.gif)


### 🏆 Key Learnings
-	Data cleaning and transformation using Power Query.
-	Efficient data modelling for better visualization.
-	Dashboard design and storytelling using Power BI.
-	Identifying key business insights from financial transaction data.
-	Using Bookmarks to switch between different charts.
-	Syncing slicers for seamless filtering across multiple pages.
-	Conditional formatting to highlight trends in the dataset.

### 📢 Conclusion
This project demonstrates the power of Power BI in analysing financial transactions and deriving actionable insights. The dashboard effectively presents UPI transaction trends, customer behaviour, and merchant performance, making it valuable for businesses and analysts.


