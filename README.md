Uber Supply-Demand Gap Analysis:-
A complete data analytics project using Excel, SQL, and Python to analyze gaps between ride demand and availability in Uber data.

Problem Statement:-
Uber faces an imbalance between supply and demand—especially during peak hours. The goal of this project is to:
- Understand when and where the demand exceeds the supply
- Identify the major causes of failed requests
- Provide clear, visual insights to solve these issues

Tools Used:-
Excel – Data cleaning, dashboard creation, slicers, charts  
SQL – Query-based insights (peak hours, cancellations, etc.)  
Python (Pandas, Seaborn, Matplotlib) – EDA and visual storytelling

Data Cleaning Note
Initially, I cleaned the dataset in Excel by handling formatting, blanks, and standardizing columns.  
However, I missed duplicate entries and a few missing Driver IDs, which I later identified and cleaned during the Python EDA process using Pandas.

Excel Dashboard Highlights
1.Cleaned Excel dataset
2.Dynamic dashboard with slicers for:
3.Pickup Point Status
4.Time of Day (Morning, Afternoon, Evening, Night)
5.Visuals: Bar chart, Line chart, Pie chart
File: `EXCEL_DASHBOARD.zip`

SQL Insights
1.Identified peak request hours
2.Compared completed, cancelled, and "No Cars Available" statuses
3.Filtered pickup points by time to highlight demand gaps
File: uber_sql.zip

Python EDA Summary:-
Performed in Jupyter Notebook using Pandas, Seaborn, and Matplotlib:
1.Loaded the cleaned dataset
2.Initially, I had missed handling duplicate values in Excel, but I discovered and removed them during Python analysis
3.Handled missing values (like NA in driver IDs)
4.Created a new column to classify requests by Time of Day (Morning, Afternoon, Evening, Night, etc.)
Visualized key metrics:
Trip status distribution
Pickup point comparison
Demand patterns by hour and time category
File: uber_python.zip

Key Insights
Morning and Evening had the highest demand, but supply was low.
"No Cars Available" was the main reason for incomplete requests during peak hours.
Airport faced more cancellations, while the City had more completed trips.

 Conclusion
This project helped me apply end-to-end data analytics techniques.
From cleaning and preparing the data to building dashboards, writing SQL queries, and performing Python visualizations—every step was hands-on and insightful.
I initially cleaned the dataset in Excel, but Python EDA revealed hidden issues like duplicate rows and missing values, which I later handled using code. 
This reinforced the importance of validating data at every stage.

About Me
I'm Sharadha S R, an aspiring data analyst passionate about turning raw data into meaningful insights that solve real-world problems.
This project reflects my practical skills and growth in Excel, SQL, and Python.
📌 Connect with me on [LinkedIn](https://www.linkedin.com/in/sharadha).
