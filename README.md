# The Teacup Haven Café (Interactive dashbaord using MS EXCEL)
## Project Objective
The Teacup Haven Café wants to create an annual sales report to review its performance over the past year. This analysis is designed to help the café identify key trends, monitor its growth, and make informed business decisions going forward.

##Dataset used
- <a href="https://github.com/Rachy143/CAFE-SALES-DATA-ANALYSIS-USING-EXCEL/blob/main/CAFE%20SALES.xlsx">Dataset</a>

##Questions (KPIs)
-	What was the total revenue and total number of transactions during the year?
-	Which product was the best seller?
-	Which months recorded the highest sales?
-	Do customers prefer dining in or taking their orders to go?
-	Which payment methods were most popular among customers?
-	Are there any noticeable sales trends across different days of the week?
-	Which items generate the highest total revenue (not just quantity)?

- Dashbord interaction <a href="https://github.com/Rachy143/CAFE-SALES-DATA-ANALYSIS-USING-EXCEL/blob/main/CAFE%20DASHBOARD.png">View Dashboard<a/>

## Process
##Data Collection
I started with a raw dataset containing sales transactions from The Teacup Haven Café. The data included details such as items purchased, quantity, price per unit, total spent, payment method, location (in-store or takeaway), and transaction dates.
## Data Cleaning
Before starting the cleaning process, I took time to carefully understand the entire dataset, including the columns, data types, and the meaning of each field. This helped me identify possible errors, inconsistencies, and missing values.
The original dataset contained several issues such as missing item names, incorrect or missing quantities, wrong totals, and inconsistent categorical entries (e.g., "UNKNOWN" in payment methods or locations).
To fix these issues:
- Validated and corrected totals: Recalculated the Total Spent column using Quantity × Price Per Unit to ensure accuracy.
- Standardized categorical values: Replaced "UNKNOWN" and inconsistent entries in the Payment Method and Location columns with meaningful labels or marked them as "NaN".
- Filled missing quantities: Used an IFS formula to assign default quantities based on the item type. For example, Coffee was assigned 2, Cake 3, and so on.
- Recovered missing item names: Converted item codes into grouped categories using another IFS formula (e.g., "Coffee or Tea"). I then filtered these rows and split them equally between the possible items (e.g., 60 for Coffee, 60 for Tea) to distribute them fairly and maintain realistic proportions.
- Converted data types: Ensured numeric columns and dates were properly formatted for accurate analysis.
- Checked for duplicates: Reviewed Transaction IDs to avoid duplicate records and ensure each transaction was unique.
Through these steps, I transformed the raw, inconsistent dataset into a clean and reliable version, ready for analysis and visualization.

## Dashboard
<img width="1895" height="844" alt="CAFE DASHBOARD" src="https://github.com/user-attachments/assets/94f19b5e-88e2-4542-b185-7210d92b665a" />

## Conclusion
This project turned a messy sales dataset into a clean, reliable source of insights for The Teacup Haven Café. The final analysis and dashboard highlight key trends, top-selling items, and customer preferences, helping the café make smarter, data-driven decisions.


