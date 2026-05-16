📱 Mobile Sales Insights Dashboard
An interactive Power BI Dashboard that provides a comprehensive analysis of mobile phone sales data — covering revenue, customer behavior, product performance, and geographic trends.

📊 Dashboard Overview
This single-page Power BI report (Mobile-Sales-Insights-Dashboard.pbix) visualizes key sales metrics for a mobile retail business. It is designed to help stakeholders quickly identify trends, top-performing products, and customer preferences.

🧩 Visuals & Components
Visual TypeDescriptionKPI CardsTotal Sales, Average Sales, Total Quantity Sold, Total Transactions
MapTotal Sales by City — geographic distribution of revenueLine
ChartTotal Quantity over Month and Day — time-series trend analysis
Clustered Bar ChartTotal Sales by Mobile Model — best-selling models
Pie ChartTransactions by Payment Method — preferred payment modes
Funnel ChartCustomer Ratings distribution
Area ChartTotal Sales by Day Name — weekly sales pattern 
Table  Brand-level breakdown: Total Sales, Quantity, Transactions
Slicers Filter by Mobile Model and Payment Method
Date SlicerFilter data by Month

📁 Dataset Fields
The dashboard is built on a sales_data table with the following key columns:

City — Location of sale
Mobile Model — Name/model of the mobile phone
Brand — Mobile brand
Total Sales — Revenue generated
Total Quantity — Number of units sold
Transactions — Number of transactions
Average — Average sales value
Payment Method — Mode of payment (e.g., Cash, Card, UPI)
Customer Ratings — Customer satisfaction ratings
Day Name — Day of the week
Date — Date of transaction (with Month hierarchy)


🛠️ Tools Used

Microsoft Power BI Desktop
Power Query — for data transformation
DAX — for calculated measures (Total Sales, Avg, Quantity, Transactions)


🚀 How to Use

Download and install Power BI Desktop
Clone or download this repository
Open Mobile-Sales-Insights-Dashboard.pbix in Power BI Desktop
Explore the dashboard using slicers to filter by Mobile Model, Payment Method, and Date


📌 Use Cases

Sales performance monitoring
Regional sales comparison
Customer payment behavior analysis
Product (mobile model/brand) performance tracking
Day-wise and month-wise trend analysis
