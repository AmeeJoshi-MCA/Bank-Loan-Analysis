# 🏦 Bank Loan Report - SQL, Python, Excel , Tableau, Power BI

This capstone project showcases a full data analysis lifecycle, from raw data processing and SQL querying to advanced dynamic visualization using a comprehensive set of industry-standard tools. The project focuses on creating an interactive Bank Loan Report dashboard for financial performance monitoring and risk assessment.
This project was executed using both advanced BI tools (Power BI, Tableau) and foundational analysis techniques in Microsoft Excel to demonstrate versatility across different platforms.

## ✨ Key Features & Deliverables
* **KPI Dashboard:** A high-level summary dashboard focusing on critical metrics like Total Loan Applications, Total Funded Amount, and key Bad Loan indicators.
*  **Comparative Period Metrics:** Calculation and visualization of Month-to-Date (MTD) performance compared to Month-over-Month (MOM) growth for all major financial KPIs (Interest Rate, DTI, Applications, Funded Amount, Received Amount).
 * **Dynamic Overview:** An interactive dashboard allowing users to dynamically switch between different financial measures (e.g., Total Amount Received, Funded Amount) to instantly change chart views and analyze trends by state, term length, purpose, and home ownership.
 * **Granular Data View:** A detailed, paginated grid view in the dashboard to inspect individual loan records, their status, interest rates, and payment history.
 * **Risk Analysis:** Clear segmentation of the loan portfolio into "Good Loans" (Fully Paid, Current) and "Bad Loans" (Charged Off, Default).
 * **Full Pipeline Implementation:** Demonstrating proficiency across the entire data stack, from initial data loading to final dashboard deployment.

## Data Source
* The project is based on a comprehensive [dataset](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/data/financial_loan.csv) stored in SQL Server, encompassing various aspects of bank loans, including loan amounts, issue dates, interest rates, DTI ratios, and loan statuses.

## Tools and Technologies Used
* **SQL Management Server:** Used for database management, querying, and data analysis. SQL queries were crucial in extracting key metrics and insights from the loan dataset.

* **Excel:** Utilized for data cleaning, processing, and conducting preliminary analyses. Excel provided a platform for validating data integrity and performing initial calculations.

* **Power BI:** Employed for data visualization and dashboard creation. Power BI enabled the creation of interactive dashboards that visualize loan portfolio performance and trends.
 
* **Tableau:** Utilized for advanced data visualization and building interactive dashboards. Tableau's capabilities were leveraged to explore complex data relationships and provide deeper insights into loan analytics.

## Principal Visualizations
### Summary 
<img width="1549" height="871" alt="image" src="https://github.com/user-attachments/assets/bff2a05b-dba4-400f-bb7a-e2de2a965bd0" />

### Overview
<img width="1326" height="752" alt="image" src="https://github.com/user-attachments/assets/a194b86c-f08f-4279-8232-0a3992d58d16" />

### Details
<img width="1320" height="760" alt="image" src="https://github.com/user-attachments/assets/aa9fa9c9-ce7e-4c22-b7f2-2ec7efceba2f" />


## 🛠️ Installation & Setup
* **1 Clone the repo:**   
     git clone https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis.git

* **2 Set up the database / SQL:**
  * Import the [loan dataset](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/data/financial_loan.csv) to the create database.
  * Use the provided [SQL script](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/sql/loan_queries.sql) to set up the database in SQL Management Server. 

* **3 Python Setup:**
   Open the provided [python file](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/python/Bank%20loan%20analysis%20.ipynb) to review analyses
   and data processing.

* **4 Excel Setup:**
   Open the provided Excel file to review preliminary analyses and data processing steps.

* **5 Power BI Setup:**
          Open the provided [Power BI file](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/powerBi/Bank_loan_report.pbit).
          Connect the BI file to your SQL Server database.

* **6 Tableau Setup:**
  Open the provided [Tableau workbook](https://github.com/AmeeJoshi-MCA/Bank-Loan-Analysis/blob/main/tableau/BankLoanAnalysis.twb).
  Connect the Tableau workbook to your SQL Server database.

 ## ✅ Conclusion
 * This project demonstrates the end-to-end process of building a Bank Loan Analytics System using SQL, Python, Tableau, and Power BI.

* SQL queries were used to extract, clean, and aggregate loan data.

* KPIs such as loan applications, funded amounts, collections, interest rate, and DTI provide a clear view of overall performance.

* Segmentation into Good vs Bad Loans enables risk assessment and credit quality monitoring.

* Breakdowns by month, state, term, purpose, and home ownership highlight trends and patterns across different borrower segments.

* Dashboards in Tableau and Power BI bring the analysis to life, offering interactive exploration and business-ready insights.

By combining technical tools with business metrics, this project shows how data-driven decisions can improve loan portfolio management, risk detection, and strategy planning.

🚀 Future work could involve automating pipelines, integrating real-time data, and applying machine learning models for default prediction and customer segmentation.
    
