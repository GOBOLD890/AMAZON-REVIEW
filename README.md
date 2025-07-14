🛒 Amazon Product Data Analysis 📊 Project Overview As a Junior Data Analyst at RetailTech Insights, I was tasked with analyzing Amazon product data to uncover insights that can help improve product offerings, marketing strategies, and customer engagement.

This analysis uses Excel tools such as Pivot Tables, Calculated Columns, and Dashboards to answer key business questions related to product pricing, reviews, ratings, and categories.

📁 Dataset Description The dataset contains Amazon product data scraped from online listings. It includes:

Product Name

Category

Actual Price

Discounted Price

Discount Percentage

Rating

Rating Count (Number of Reviews)

📌 Business Questions & Answers Below are the key questions answered using Excel tools:

📉 Average Discount Percentage by Category Method: Used a Pivot Table with Category in rows and average of discount_percentage in values.
Insight: Highlights which categories offer the biggest discounts.

📦 Number of Products per Category Method: Pivot Table counting product names under each category.
Insight: Shows product listing density by category.

🗣️ Total Number of Reviews per Category Method: Sum of rating_count by category using Pivot Table.
Insight: Reflects customer engagement per category.

⭐ Products with Highest Average Ratings Method: Sort by rating column in descending order.
Insight: Identifies most highly rated products.

💰 Average Actual vs Discounted Price by Category Method: Pivot Table with both actual_price and discounted_price averaged.
Insight: Compares pricing structures per category.

🔝 Products with Highest Number of Reviews Method: Sort rating_count in descending order.
Insight: Reveals best-selling or most-discussed items.

🔻 Number of Products with ≥50% Discount Method: Filtered discount_percentage ≥ 50% and counted entries.
Insight: Highlights deep discount offerings.

🏷️ Distribution of Product Ratings Method: Grouped rating column in buckets (e.g., 3.0, 4.0) and counted.
Insight: Visualizes customer satisfaction distribution.

📈 Total Potential Revenue by Category Formula Used: actual_price × rating_count (added as a calculated column).
Method: Pivot Table to sum by category.

Insight: Estimates revenue potential from highly rated products.

🪙 Unique Products per Price Range Bucket Method: Created buckets: <₹200, ₹200–₹500, >₹500 using a helper column.
Insight: Shows how products are distributed across price segments.

📊 Relationship Between Rating and Discount Method: Scatter plot of rating vs discount_percentage.
Insight: Explores if better deals attract better ratings.

👁️ Products with Fewer Than 1,000 Reviews Method: Filter where rating_count < 1000 and count.
Insight: Identifies products with lower visibility or newer entries.

🏆 Categories with the Highest Discounts Method: Sort average discount_percentage by category in descending order.
Insight: Spotlights heavily discounted segments.

🥇 Top 5 Products by Rating + Reviews Formula Used: rating × rating_count as a combined score.
Method: Sort this score and pick top 5.

Insight: Best performers in quality and popularity.

📊 Final Task: Excel Dashboard A dynamic and interactive dashboard was built using:

Slicers for category filtering

Bar charts for reviews and ratings

Pie chart for product rating distribution

KPI cards for revenue and discount summaries

The dashboard provides a clear snapshot of product performance and market trends.

📎 Tools Used Microsoft Excel

Pivot Tables

Calculated Columns

Data Filters

Charts & Visuals

Dashboard Design

📁 File Structure bash Copy Edit 📂 Amazon-Product-Analysis/ ├── 📄 README.md ├── 📊 Amazon case study (1).xlsx └── 📈 Dashboard Screenshot (optional).png 🧠 Insights Summary Products in [Top Category] offered the biggest discounts.

[Top Product] had the highest combined rating and review score.

Only X% of products received over 1,000 reviews.

[Category Name] had the highest potential revenue.

🚀 How to Use Open the Excel file. Navigate through Pivot Table sheets to explore answers.
![20250714_194344](https://github.com/user-attachments/assets/9298cf7c-e7d7-418f-a3be-932ae96d2e31)
