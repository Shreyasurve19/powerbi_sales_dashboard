# powerbi_sales_dashboard
Interactive Power BI dashboard analyzing sales performance across regions, categories, and time using DAX measures.

#📊 Sales Performance Dashboard | Power BI

📌 Project Overview
This project is a professional Power BI dashboard designed to analyze sales performance across different regions, categories, and time periods.
The dashboard focuses on clarity, interactivity, and actionable business insights, using clean visuals and well-defined metrics.

🛠️ Tools & Technologies
Power BI Desktop
DAX (Data Analysis Expressions)
Data modeling and interactive visual design

📂 Dataset
Sales dataset containing order-level transactional data
Key fields include:
Order Date
Region
Category
Sales
Order ID

📐 Dashboard Features
Card visuals for key metrics:
Total Sales
Total Orders (Distinct Count)
Average Sales

Interactive slicers for:
Category
Region
Order Date

Visual analysis using:
Bar charts (Region & Category performance)
Line chart (Year-wise sales trend)
Clean layout with consistent formatting and borders

📊 Key DAX Measures
Total Sales = SUM(superstore[Sales])
Total Orders = DISTINCTCOUNT(superstore[Order.ID])
Average Sales = AVERAGE(superstore[Sales])

🔍 Key Business Insights
Total sales reached approximately 13M, indicating strong overall performance
Technology emerged as the top-performing category in terms of revenue
Central and South regions contributed the highest share of total sales
Sales demonstrated a steady year-on-year growth trend, peaking in later years
Category and regional slicers revealed performance variations across different segments

🎯 Objective & Outcome
The goal of this project was to:
Convert raw sales data into meaningful insights
Build an intuitive and interactive dashboard
Apply best practices in Power BI visual design and DAX calculations
The outcome is a user-friendly dashboard that supports quick decision-making and high-level performance analysis.

🖼️ Dashboard Preview


📌 How to Use
Download the .pbix file
Open using Power BI Desktop
Use slicers to explore insights dynamically

👤 Author
Shreya Surve
Aspiring Data Analyst | Power BI Enthusiast
