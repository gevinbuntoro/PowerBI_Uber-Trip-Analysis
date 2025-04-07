# PowerBI_Uber-Trip-Analysis

## Project Overview

**Project Title**: Uber Trip Analysis

This Power BI dashboard project analyzes Uber trip data to uncover booking trends, revenue insights, and trip efficiency. By exploring ride demand across various time intervals, the dashboard supports data-driven decisions to optimize operations, pricing, and driver allocation. Additionally, a dedicated Grid Tab with drill-through functionality allows users to access detailed records, offering deeper insights and flexible data exploration.

## Objectives

1. Analyze Uber trip data for data-driven decision-making to uncover key booking trends, revenue, and trip efficiency trends.

2. Identify ride demand patterns across time intervals to support pricing strategies, driver allocation, and operational planning.

3. Visualize key performance indicators (KPIs) with interactive dashboards, dynamic measure selectors, and slicers for in-depth analysis.

4. Enable users to explore detailed trip records through a Grid Tab with drill-through functionality and bookmarks for full data views.

5. Enhance usability with features like dynamic titles, clear filter/reset buttons, and raw data export for flexible reporting.

## Dashboard

1. **Overview Analysis**: Analyse Uber trip data using Power BI to gain insights into booking trends, revenue, and trip efficiency, helping stakeholders make data-driven decisions.

   A. KPI: 

      a. Total Bookings – How many trips were booked over a given period?

      b. Total Booking Value – What is the total revenue generated from all bookings?

      c. Average Booking Value – What is the average revenue per booking?

      d. Total Trip Distance – What is the total distance covered by all trips?

      e. Average Trip Distance – How far are customers traveling on average per trip?

      f. Average Trip Time – What is the average duration of trips?


   B. Expected Outcomes:

      a. Identify trends in ride bookings and revenue generation.

      b. Analyse trip efficiency in terms of distance and duration.

      c. Compare booking values and trip patterns across different time periods.

      d. Provide insights to optimize pricing models and improve customer satisfaction.

2. **Time Analysis**: To understand trip patterns based on time, Uber needs to analyze ride demand and trends across different time intervals. This dashboard will help in optimizing operations, pricing, and driver availability.

   A. Global Dynamic Measure (Filters All Charts)

      a. Total Bookings

      b. Total Booking Value

      c. Total Trip Distance

      Note: This dynamic measure will update all visuals based on user selection.


   B. Visualizations:

      a. By Pickup Time (10-Minute Intervals) - Area Chart
         Group trip bookings into 10-minute intervals throughout the day.
         Helps in identifying peak and off-peak demand periods.

      b. By Day Name - Line Chart
         Shows booking trends across Monday to Sunday.
         Useful for analyzing weekday vs. weekend demand.

      c. By Hour and Time - Heatmap (Matrix Grid)
         Rows: Hours of the Day (0–23)
         Columns: Days of the Week (Mon-Sun)
         Values: Selected Dynamic Measure (e.g., Total Bookings)
         Highlights peak booking hours across different days.

3. **Details**: provide in-depth insights and allow users to explore granular data, a Grid Tab will be created. This tab will enable drill-through functionality, allowing users to access detailed records based on selections made in other dashboards.

      Features of the Grid Tab:
      
      a. Grid Table with Key Fields: Displays essential trip details
      
      b. Drill-Through Functionality: Users can right-click on a data point from other visuals (e.g., charts, heatmaps) and drill through to this Grid Tab. Displays detailed records related to the selected data point.
      
      c. Bookmark for Full Data View: A "View Full Data" bookmark to toggle between filtered drill-through data and the complete dataset. Allows users to reset filters and see all records easily.

## Findings

1. Based on the trip type (Day/Night), Uber needs to differ its focus based on the pickup location. On a day trip, it can be seen that the top 5 volumes of pickup location differ compared to the data on a night trip. Therefore, considering the trip type, Uber can shift their focus when positioning drivers to find the best spot to increase their total bookings.

2. Uber should consider increasing incentives at certain times of the day. For example, during peak hours (6:00–9:00 AM and 3:00–6:00 PM) to ensure enough drivers are available and reduce customer wait times. This is to ensure that customer satisfaction remains high.

3. UberX dominates with 38,744 bookings, over twice as many as any other type, showing it's the most preferred option. Despite different tiers, the average booking value is consistently $15, suggesting balanced pricing. Uber Green, while least booked, still generated $216,181, showing potential for growth in eco-friendly services.
   
## Conclusions

This project serves as a good training using Power BI for data analysts, covering database setup, exploratory data analysis, and visualization using many different charts. The findings from this project can help Uber to make a better decision to allocate drivers which leads to an increase in total booking volume by customer behavior looking at the location and timing as well as product performance.
   
## How to use

1. Open the Power BI file (.pbix) in Power BI Desktop to access the full interactive dashboard.

2. Navigate through tabs: Explore the three main tabs — Overview Analysis, Time Analysis, and Details (Grid Tab) — each offering specific insights.

3. Use slicers and filters: Adjust filters like date, vehicle type, or payment method to customize your analysis and view targeted insights.

4. Select a dynamic measure (in Time Analysis tab) such as Total Bookings, Total Booking Value, or Total Trip Distance to update all charts accordingly.

5. Drill-through to view detailed data: Right-click any data point in a chart (e.g., heatmap or area chart) and choose Drill through → Details to see trip-level data in the Grid Tab.

   
## Acknowledgement 

Special thanks to Swapnjeet S for his Power BI tutorial and guidance. The project was inspired by his insights shared on https://topmate.io/data_tutorials/1481559
