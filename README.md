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

Cleaned Excel dataset
Dynamic dashboard with slicers for:
Pickup Point
Status
Time of Day (Morning, Afternoon, Evening, Night)
Visuals: Bar chart, Line chart, Pie chart

 File: `EXCEL_DASHBOARD.zip`

SQL Insights

- Identified peak request hours
- Compared completed, cancelled, and "No Cars Available" statuses
- Filtered pickup points by time to highlight demand gaps

File: uber_sql

Python EDA Summary

Performed in Jupyter Notebook using Pandas, Seaborn, and Matplotlib:

- Loaded cleaned data
- Handled missing values and removed duplicates
- Created new column for Time of Day
- Visualized:
  - Trip Status distribution
  - Pickup point comparison
  - Demand patterns by time

File:-uber_python

Key Insights

Morning and Evening had the highest demand, but supply was low.
"No Cars Available" was the leading reason for incomplete requests during peak hours.
Airport had more cancellations; City had more completed rides.
  
 Conclusion

This project helped me apply end-to-end data analytics techniques.  
From data cleaning to dashboard creation, SQL querying, and Python visualizations—every step was hands-on and insightful.

 I learned that even when cleaning data in Excel, validating again using Python can catch hidden issues like duplicates and missing entries.


About Me

I'm Sharadha S R, an aspiring data analyst passionate about using data to solve real-world problems.  
This project reflects my learning journey and skills in Excel, SQL, and Python.

📌 Connect with me on [LinkedIn](https://www.linkedin.com/in/sharadha).
