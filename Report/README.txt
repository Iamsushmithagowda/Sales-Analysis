Sales Data Analysis and Reporting for a Retail Chain

📘 PROJECT OVERVIEW
This project focuses on analyzing and reporting sales data for a retail chain.
It involves cleaning raw data, generating tabular reports, and visualizing trends to extract meaningful business insights.

PROJECT WORKFLOW
1️⃣ Data Cleaning (1_data_cleaning.ipynb)
 -Reads raw retail data from multiple CSV files.
 -Cleans missing values, removes duplicates, and formats dates.
 -Adds derived columns like Month, Year, and Transaction Amount.
 -Exports the cleaned dataset to:
→ Cleaned_Retail_Data.csv
Generated Visuals:
 -Before_Cleaning.png
 -After_Cleaning.png

2️⃣ Tabular Reports (2_tabular_reports.ipynb)
 -Generates monthly, yearly, and category-wise sales summaries.
 -Aggregates transaction data for performance insights.
 -Exports formatted Excel reports for management review.
 -Generated Reports:
 -Monthly_Sales_Report.xlsx
 -Summary_Reports.xlsx
 -Dasboard.xlsx

3️⃣ Visual Reports (3_visual_reports.ipynb)
-Creates different types of charts to visualize patterns and trends in sales data.
Generated Visuals:
 -BarChart_Yearly_Sales.png – Yearly sales comparison
 -LineChart_Monthly_Sales.png – Monthly sales trend
 -PieChart_Response.png – Customer response distribution
 -Heatmap_Sales.png – Correlation heatmap between sales metrics
 -Histogram_Transactions.png – Distribution of transaction amounts
 -Monthly_Sales_Trend.png – Trend of monthly aggregated sales

 FLODER STRUCTURE
 SALES_DATA_ANALYSIS_AND_REPORT/
│
├── .venv/                         # Virtual environment
├── Report/                        # Visuals, Excel reports, and presentations
│   ├── *.png, *.xlsx, *.pptx
│
├── 1_data_cleaning.ipynb          # Data cleaning process
├── 2_tabular_reports.ipynb        # Aggregated report generation
├── 3_visual_reports.ipynb         # Visual analytics and charts
│
├── Cleaned_Retail_Data.csv        # Processed data file
├── Retail_Data_Transactions.csv   # Raw transaction data
├── Retail_Data_Response.csv       # Raw response data
├── Data_cleaning__Preparation__lyst3753.ipynb # Backup notebook
└── README.txt                     # Project documentation

🛠️ TOOLS & LIBRARIES USED
-Python
-Pandas
-Matplotlib
-Seaborn
-Jupyter Notebook
-Excel / PowerPoint (for reporting)

DELIVERABLES
-Visual and tabular reports in the Report/ folder.
-Presentation file: Sales_Analysis_Presentation.pptx
-Cleaned data and summary Excel files.

👩‍💻 AUTHOR
Sushmitha Gowda S
-Sales Data Analysis and Reporting Project