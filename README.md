# DSA-Project
This is a well explained project on Amazon product reviews, discounts and pricing using Excel-based analytics. This project was done during my time at the DSA Incubator hub. This project gives insights on product performance,category trends and customer engagements.

## 📖 Project Topic: Amazon Products Sales Analysis
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## Project Context
Client Name: RetailTech Insights
Industry: E-commerce Analytics
Role: Junior Data Analyst
Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, Cards)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📑 Dataset Summary
- Total Records: 1,465
- Columns: 16
- Source: Web-scraped Amazon product review data
- Each row represents: A unique product
- Fields included:
  - Product name
  - Category
  - Actual price & Discounted price
  - Discount %
  - Rating
  - Number of Ratings (Rating Count)
  - Review content (aggregated in some columns)
  - Revenue potential fields (derived)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📑 Analytical Tasks
| Task Description | Logic Used |
| ---------------- | ---------- |
| What is the average discount % by product category? | Pivot Table + Average Formula |
| How many products are listed under each category? | Pivot Table + Count |
| What is the total number of reviews per category? | SUM of Rating Count by category |
| Which products have the highest average ratings? | Sorting based on calculated Average Rating |
| What is the actual vs discounted price by category? | pie chart + pivot summary |
| Which products have the highest number of reviews? | Top-N Analysis using Sorting + Pivot Table |
| How many products have ≥ 50% discount? | Filter logic on Discount column |
| What is the distribution of product ratings (e.g., 3.0, 4.0, etc.)? | Grouped histogram with Pivot Count |
| Total potential revenue (actual_price × rating_count) per category? | New Calculated Column + Pivot Table SUM |
| Unique product count per price range bucket (<₹200, ₹200–₹500, >₹500)? | IF formulas + Donut Chart |
| Relationship between rating and discount level? | Scatter Line Chart (2 y-axes) |
| How many products have fewer than 1,000 reviews? | COUNTIF Formula + Bar Chart |
| Categories with highest average discount? | Sorted Pivot Table by Discount% |
| Top 5 products by combined review count and rating | Ranking logic using SUM(Rating × ReviewCount) |
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🎥 Analysed File
[Amazon Case study report](https://github.com/debbyadeshola1/DSA-Documentation/blob/main/Amazon%20case%20study%20report.xlsx)
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### ⛓️ Highlights
- Discount vs Rating: Discounted products don’t always have higher ratings. There’s a complex relationship.
- Price Range Bucket: Most products fall under the affordable to moderately expensive range.
- Revenue Potential: Categories like Home Kitchen and Electronics dominate in potential revenue.
- Category-wise Review Count: Electronics and accessories lead in user engagement.
- Top 5 Products: Based on high review count and strong ratings (e.g., AmazonsBasics FI, Realme X, etc.)
- Discount Percentage by Category: Health and home products offered the most generous discounts.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🧰 Tools Used
- Microsoft Excel
   - Pivot Tables
   - Data Visualizations (Bar, Line, Donut, Cards)
   - Slicers & Filters
   - Conditional Formatting
   - Named Ranges & Table References
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🧠 Analysis From Dashboard
- Discount vs Rating: Discounted products don’t always have higher ratings. There’s a complex relationship.
- Price Range Bucket: Most products fall under the affordable to moderately expensive range.
- Revenue Potential: Categories like Home Kitchen and Electronics dominate in potential revenue.
- Category-wise Review Count: Electronics and accessories lead in user engagement.
- Top 5 Products: Based on high review count and strong ratings (e.g., AmazonsBasics FI, Realme X, etc.)
- Discount Percentage by Category: Health and home products offered the most generous discounts.
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🧠 Skills Used
| Skills | How it was Used |
|------- | --------------- |
| Data Cleaning |	Removed nulls, corrected inconsistent formats, trimmed text (category column) |
| Data Aggregation | Used pivot tables and grouping to summarize key insights |
| Excel Formulas | IF, COUNTIF, AVERAGEIFS, PROPER, calculated columns |
| Visualization	| Designed intuitive charts (bar, pie, line, donut charts) |
| Slicers & Cards |	Enabled dynamic filtering |
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Insights & Conclusion
- Some discounted items still received poor ratings, This means that Price cuts alone won’t ensure customer satisfaction
- Electronics had the most reviews but also a wide range in satisfaction.
- Products who had high rating counts can be further promoted to drive traffic
------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
