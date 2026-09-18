---

layout: default
title: Instacart Grocery Basket Analysis
description: Python analysis of Instacart customer and purchasing data to identify shopping patterns, customer demographics, and opportunities for targeted marketing.
order: 4
--------

**Tools:** Python · Jupyter Notebook · Pandas

**Skills:** Data Wrangling · Data Subsetting · Data Merging · Variable Derivation · Grouping & Aggregation · Data Visualization · Customer Analysis · Demographic Analysis

## Project Overview

Instacart is an online grocery shopping platform with a large and diverse customer base.

The goal of this project was to analyze customer purchasing behavior and demographics to identify shopping patterns and develop recommendations for targeted marketing and customer engagement.

The analysis examined when customers shop, which departments perform best, how purchasing behavior varies by region, and how customer demographics are distributed across the customer base.

## Business Questions

The analysis focused on several key questions:

1. What are the busiest days and hours for Instacart orders?
2. Which departments are most popular across different regions?
3. What does the customer base look like across age and income groups?
4. How do customer demographics vary across regions?
5. How can these findings support more targeted marketing and operational decisions?

## Data

The analysis combined several categories of Instacart data:

* Customer demographics
* Order history
* Product information
* Departments and product categories

The datasets provided information about customer characteristics, purchasing activity, products, and departments.

The project used the publicly available Instacart Online Grocery Shopping Dataset 2017 along with customer demographic data used for the analysis. The original Instacart dataset contains anonymized grocery-order information from more than 200,000 users and more than 3 million orders.

## Tools & Methods

Python was used to clean, transform, explore, and visualize the data.

The analysis included:

* Data wrangling and subsetting
* Merging datasets
* Deriving new variables
* Grouping and aggregation
* Exploratory data analysis
* Data visualization

Jupyter Notebook was used as the primary analysis environment, with Pandas used for data manipulation and analysis.

## Analysis

### Shopping Patterns

The analysis found that **Sunday and Saturday were the busiest shopping days**, while **Tuesday and Wednesday were the least busy**.

Most orders were placed between **10 AM and 3 PM**.

These patterns provide useful information about when customers are most active and help identify opportunities for marketing campaigns outside the busiest ordering periods.

### Department Performance

**Produce, dairy/eggs, and beverages** were the three highest-performing departments.

The **West and South regions had the highest number of purchases**, while produce had the highest sales among the departments analyzed.

These findings indicate that regional purchasing patterns should be considered when planning inventory and promotional strategies.

### Customer Demographics

Customers **under the age of 35 represented the largest age group overall**.

Most customers in this age group fell into either the **under $60K** or **$60K–$94K** income categories.

Customers between **ages 35 and 50** showed a more even distribution across income groups.

Examining age and income together provided a more detailed view of the customer base than looking at either demographic independently.

## Key Findings

The analysis identified several important patterns:

* Saturday and Sunday were the busiest shopping days.
* Tuesday and Wednesday were the least busy shopping days.
* Most orders occurred between 10 AM and 3 PM.
* Produce, dairy/eggs, and beverages were the top-performing departments.
* The West and South regions had the highest number of purchases.
* Produce had the highest sales among the departments analyzed.
* Customers under 35 represented the largest age group.
* Customers ages 35–50 were more evenly distributed across income groups.

## Recommendations

### 1. Adjust Advertising Around Customer Activity

The analysis recommended running advertisements on **Tuesday and Wednesday**, particularly during:

* 6 AM–8 AM
* 5 PM–10 PM

The analysis identified **5 PM and 7 PM** as particularly important times, with **12 PM** representing a secondary opportunity.

Targeting lower-volume shopping periods could provide opportunities to increase engagement when customers are less active on the platform.

### 2. Prioritize Inventory in High-Demand Regions

The **West and South regions** should maintain strong inventory levels for:

* Produce
* Dairy/eggs
* Beverages
* Snacks

Maintaining availability in these categories could help support regions with higher purchasing activity.

### 3. Target High-Income Senior Customers

Marketing campaigns should include **high-income senior customers** across regions.

The demographic analysis suggests that this customer segment represents an opportunity for more targeted marketing rather than relying on a single strategy for the entire customer base.

### 4. Consider Family-Oriented Promotions

Family-oriented promotions, such as **bulk deals**, could be considered in the **South and West regions**.

This approach would align promotional strategies with both customer demographics and regional purchasing behavior.

## Data Limitations

The analysis should be interpreted within the limitations of the available data.

The underlying Instacart dataset is a historical 2017 dataset and represents a sample of Instacart orders rather than a random sample of all customers or purchases. As a result, the findings describe patterns within the analyzed data and should not necessarily be treated as representative of Instacart's current customer base.

The demographic analysis also depends on the customer information available in the project datasets.

## Conclusion

The Instacart analysis demonstrates how customer demographics, purchasing behavior, product categories, and regional patterns can be combined to support targeted marketing and operational decisions.

The results show that customer activity varies by **day, time, region, and demographic group**. Using these patterns to guide advertising, inventory planning, and promotions can provide a more targeted approach to customer engagement.

## Lessons Learned

This project strengthened my ability to use Python for data analysis.

In particular, I gained experience with:

* Wrangling data with Python
* Merging datasets
* Deriving variables
* Grouping and aggregating data
* Using visualizations to communicate analytical findings

The project also reinforced the importance of combining multiple datasets and examining customer behavior from several perspectives rather than relying on a single metric.

## Project Repository

The complete Python analysis and Jupyter Notebook are available in my GitHub repository.

[View the Instacart Grocery Basket Analysis on GitHub](https://github.com/Ninja-Librarian/Python_InstacartGrocery_Analysis)

