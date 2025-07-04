# DSA-Documentation
This is a well explained project on Amazon product reviews, discounts and pricing using Excel-based analytics. This project was done during my time at the DSA Incubator hub. This project gives insights on product performance,category trends and customer engagements.
## Project Topic: Amazon Products Sales Analysis

## Project Context
Client Name: RetailTech Insights
Industry: E-commerce Analytics
Role: Junior Data Analyst
Tools Used: Microsoft Excel (Pivot Tables, Charts, Conditional Formatting, Slicers, Cards)

## Dataset Summary
- Total Records: 1,465
- Columns: 16
- Source: Web-scraped Amazon product review data
- Each row represents: A unique product
- Fields included:
1. Product name
2. Category
3. Actual price & Discounted price
4. Discount %
5. Rating
6. Number of Ratings (Rating Count)
7. Review content (aggregated in some columns)
8. Revenue potential fields (derived)

## Analytical Tasks
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

### Analysed File

