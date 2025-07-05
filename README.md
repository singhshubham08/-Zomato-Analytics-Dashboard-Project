
[Uploading 
      <svg
        width="854"
        height="190"
        xmlns="http://www.w3.org/2000/svg"
        xmlns:xlink="http://www.w3.org/1999/xlink"
        style="z-index:1;position:relative"
        viewBox="0 0 854 190"
      >
        <style>
      .text {   font-size: 50px;   font-weight: 700;   font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji;  } .desc {   font-size: 20px;   font-weight: 500;   font-family: -apple-system,BlinkMacSystemFont,Segoe UI,Helvetica,Arial,sans-serif,Apple Color Emoji,Segoe UI Emoji;  } 
      .text, .desc {   animation: twinkling 4s ease-in-out infinite;  } @keyframes twinkling {   40% {     opacity: 1;   }   50% {     opacity: 0.5;   }   60% {     opacity: 1;   }   70% {     opacity: 0.5;   }   80% {     opacity: 1;   }  } 
    </style>
        <defs>
              <linearGradient id="linear" x1="0%" y1="0%" x2="100%" y2="0%">
                <stop offset="0%" stop-color="#00FFFF"/><stop offset="100%" stop-color="#8A2BE2"/>
              </linearGradient>
            </defs>
        
      <g transform="translate(427, 95) scale(1, 1) translate(-427, -95)">
        <path d="" fill="url(#linear)" opacity="0.4" >
          <animate
              attributeName="d"
              dur="20s"
              repeatCount="indefinite"
              keyTimes="0;0.333;0.667;1"
              calcmod="spline"
              keySplines="0.2 0 0.2 1;0.2 0 0.2 1;0.2 0 0.2 1"
              begin="0s"
              values="M0 0L 0 110Q 213.5 150 427 120T 854 145L 854 0 Z;M0 0L 0 135Q 213.5 150 427 130T 854 120L 854 0 Z;M0 0L 0 155Q 213.5 125 427 155T 854 120L 854 0 Z;M0 0L 0 110Q 213.5 150 427 120T 854 145L 854 0 Z">
          </animate>
        </path>
        <path d="" fill="url(#linear)" opacity="0.4" >
          <animate
            attributeName="d"
            dur="20s"
            repeatCount="indefinite"
            keyTimes="0;0.333;0.667;1"
            calcmod="spline"
            keySplines="0.2 0 0.2 1;0.2 0 0.2 1;0.2 0 0.2 1"
            begin="-10s"
            values="M0 0L 0 125Q 213.5 170 427 140T 854 150L 854 0 Z;M0 0L 0 140Q 213.5 110 427 110T 854 130L 854 0 Z;M0 0L 0 135Q 213.5 115 427 140T 854 155L 854 0 Z;M0 0L 0 125Q 213.5 170 427 140T 854 150L 854 0 Z">
          </animate>
        </path>
      </g>
         <text text-anchor="middle" alignment-baseline="middle" x="50%" y="36%" class="text" style="fill:#ffffff;" stroke="#none" stroke-width="1" >🍽️Zomato Analytics Project</text>
        
      </svg>
    68747470733a2f2f63617073756c652d72656e6465722e76657263656c2e6170702f6170693f747970653d776176696e6726636f6c6f723d303a3030464646462c3130303a384132424532266865696768743d3139302673656374696f6e3d68656164657226746578743df09f8dbdefb88f5a6f6d61746f253230416e616c79746…]()



 
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
