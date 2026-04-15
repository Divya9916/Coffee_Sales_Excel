# Coffee-Shop-Sales
Coffee-Shop-Sales-Analysis-Project
Analyzed retail sales data for a coffee shop chain to explore transaction patterns, peak operating hours, and product performance. Performed data cleaning, transformation, and dashboarding in Excel to uncover insights on store footfall, category distribution, and revenue drivers.

## Project Overview
The dataset contains transaction-level information including date, time, location, product category, size, and unit price.
This project focuses on transforming raw transactional logs into a high-level executive dashboard to identify operational efficiencies and customer purchasing habits across different store locations.

## Objectives
Clean and prepare the coffee shop transactional dataset.
Standardize time-based data to identify hourly and daily sales trends.
Analyze sales distribution across categories (Coffee, Tea, Bakery, etc.).
Compare performance across three key locations: Astoria, Hell’s Kitchen, and Lower Manhattan.
Create an interactive Excel-based dashboard for real-time KPI tracking.

## Skills & Techniques Used
Data Cleaning: Standardizing date/time formats and handling inconsistent entries.
Feature Engineering: Creating helper columns for Hour, Day Name, and Month for time-series analysis.
Pivot Table Analysis: Aggregating large datasets to find top-performing products and peak footfall.
Dashboard Design: Implementing a cohesive color palette and UI/UX principles for data clarity.
Slicer Integration: Allowing dynamic filtering by Month and Day of the week.

## Data Cleaning & Transformation
Performed systematic cleaning using Excel tools:
Time Formatting: Extracted "Hour" from transaction time to visualize the morning rush.
Date Normalization: Converted dates into "Month Name" and "Day Name" for seasonal and weekly reporting.
Calculated Metrics: Developed formulas to calculate "Total Sales" and "Average Bill per Person."
Data Consistency: Ensured product categories and sizes (Small, Regular, Large) were mapped correctly for accurate pie chart distribution.

## Excel Functions Used
Key Excel formulas applied in the project include:
HOUR & TEXT: To categorize transaction times and name days of the week.
SUM / COUNT: To calculate total revenue ($698,812) and total transactions (149,116).
AVERAGE: To determine the average spending per transaction.
Pivot Tables: Used as the backend engine for all dashboard visualizations.

## Exploratory Data Analysis (Excel)
The analysis includes:
Hourly Sales Trend: Identifying the 8:00 AM – 10:00 AM window as the highest revenue period.
Category Distribution: Confirming that Coffee (39%) and Tea (28%) comprise the majority of sales.
Location Comparison: Evaluating footfall vs. sales to see which location has the highest "Avg Bill."
Size Analysis: Comparing order volume across Small, Regular, and Large options.
Product Rankings: Identifying "Barista Espresso" and "Brewed Chai Tea" as top revenue generators.

## File Structure
<img width="363" height="190" alt="image" src="https://github.com/user-attachments/assets/619adea3-4468-42c7-ba71-323c1750a6c5" />

## Dashboard
<img width="1232" height="618" alt="Screenshot 2026-03-26 195349" src="https://github.com/user-attachments/assets/5798eece-983f-4e54-b9b6-35f3e7ecf7cb" />


## Conclusion
The Coffee Shop Sales Dashboard provides a clear roadmap for inventory and staffing optimization. By identifying that peak footfall occurs in the morning and that Coffee/Tea drive over 60% of revenue, management can make data-driven decisions on promotional timing and stock levels.

## Future Enhancements
Incorporate Power Query for automated data refreshing.
Add Trend Lines to forecast future sales based on monthly growth.
Integrate customer loyalty data to track repeat vs. new visitors.

## Author
Divya Sharma Email: divya649sharma99@gmail.com
GitHub: github.com/Divya9916
LinkedIn: linkedin.com/in/divya9916

## License
This project is licensed under the MIT License.
