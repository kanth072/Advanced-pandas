PROJECT TITLE:
Customer Sales Analysis using Pandas

DESCRIPTION:
This project performs an end-to-end analysis of customer sales data using Python and Pandas.
The goal is to extract meaningful business insights such as total revenue, customer count,
average order value, and top-performing customers using aggregations and pivot tables.

FILES IN THE PROJECT:
1. customer_analysis:
   - Main Jupyter Notebook containing the complete analysis
   - Data loading, merging, aggregations, and pivot table operations
   - Generates the final Customer Sales Analysis Report

2. sales_data.csv:
   - Contains sales transaction data
   - Includes product, region, customer, and sales details

3. customer_data.csv:
   - Contains customer-level information
   - Used for merging with sales data to identify customer insights

4. analysis_report.pdf:
   - Final documented report of the analysis
   - Includes objectives, methodology, findings, and conclusion

5. requirements.txt:
   - Lists required Python libraries to run the project

TOOLS & TECHNOLOGIES USED:
- Python
- Pandas
- Jupyter Notebook

KEY ANALYSIS PERFORMED:
- Data merging using pandas merge()
- Aggregations:
  - Total Revenue
  - Total Customers
  - Average Order Value
  - Top Customer by Sales
- Pivot table analysis for region-wise and product-wise sales summary

HOW TO RUN THE PROJECT:
1. Install required libraries:
   pip install -r requirements.txt

2. Open the Jupyter Notebook:
   customer_analysis.ipynb

3. Run all cells to generate the analysis report

SAMPLE OUTPUT:
CUSTOMER SALES ANALYSIS REPORT
Total Revenue: $12,365,048
Total Customers: 100
Average Order Value: $123,650
Top Customer: CUST016 - $373,932

CONCLUSION:
This project demonstrates how Pandas can be effectively used for data manipulation,
aggregation, and summarization to support data-driven business decision-making.
