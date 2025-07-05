
     
 
An end-to-end data analytics project that transforms raw Zomato food delivery data into meaningful insights using Excel, MySQL, and Power BI. This interactive dashboard helps stakeholders track operational metrics, customer satisfaction, discount usage, and regional trends for smarter business decisions.
____________________________________________________________________________________________________________
🎯 Project Objective
The goal of this project is to analyze Zomato's food delivery data to:

Understand customer behavior and preferences
Monitor restaurant performance and delivery trends
Measure discount utilization
Provide data-driven insights through a Power BI dashboard
____________________________________________________________________________________________________________
🧩 Tools & Technologies Used
Excel (CSV) – for raw data input
MySQL – for data cleaning, transformation, and structuring
Power BI – for data modeling, DAX calculations, and interactive dashboard creation
DAX – for creating custom KPIs like Discount Utilization %
____________________________________________________________________________________________________________
⚙️ Project Workflow
Data Collection

Started with an Excel CSV file containing Zomato order data (orders, delivery time, ratings, discounts, etc.)
Data Cleaning in MySQL

Imported raw data into MySQL Workbench
Converted date formats, removed irrelevant columns (e.g., review text)
Created a new column to track whether a discount was applied
Final table prepared with clean, relevant fields for reporting
Power BI Integration

Connected Power BI to MySQL to import cleaned data
Created a data model and calculated custom KPIs using DAX
Built interactive visuals including charts, KPIs, filters, and slicers
Dashboard Design

Designed visuals for:
Total Orders & Revenue
Avg. Delivery Time
Discount Utilization Rate
Ratings Breakdown
Cuisine & Regional Trends
Time-based Order Trends
Enabled filters by date, region, rating, cuisine, and discount usage
___________________________________________________________________________________________________________
📊 Key Metrics & Insights
Total Orders: 10,000
Discounted Orders: 4,991
Discount Utilization: 49.91%
Average Delivery Time: 65 minutes
Average Rating: 3.0
Insights:

Nearly half the customers used discounts
Certain regions had longer delivery times
Indian cuisine was most frequently ordered
Weekends and holidays saw higher order volumes
____________________________________________________________________________________________________________
🧪 Validation
Results from Power BI were manually validated using Excel and SQL queries. The key metrics matched, confirming the accuracy of the data pipeline and DAX calculations.
____________________________________________________________________________________________________________
👥 Stakeholders Benefiting
Business Analysts – to drive decisions using performance metrics
Operations Team – to optimize delivery efficiency
Marketing Team – to evaluate discount campaigns and customer behavior
Restaurant Owners – to monitor restaurant-level sales and satisfaction
____________________________________________________________________________________________________________
📌 Non-Functional Highlights
Performance: Dashboard loads quickly even with large datasets
Scalability: Designed to handle up to 1 million rows
Usability: Clean, user-friendly interface with intuitive filters
