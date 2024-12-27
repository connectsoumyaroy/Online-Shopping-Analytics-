# 🛒 **Online Shopping Analytics Project** 📊

## **Project Overview**  
In an era dominated by online commerce, understanding customer behavior is crucial for businesses. This project explores customer shopping behavior using the **Online Shopping Dataset** sourced from Kaggle. The dataset includes customer demographics, transaction details, product descriptions, and more, providing insights into various aspects of online shopping.

**Dataset Source**:  
'🛒 Online Shopping Dataset 📊📉📈' from Kaggle.

---

## **Project Objectives**  
The primary goal of the Online Shopping Analytics project is to extract actionable insights about customer behavior, transactional patterns, and product preferences. Key objectives include:

- Understanding customer demographics and how different genders and locations utilize the platform.
- Identifying popular products or product categories.
- Analyzing spending patterns throughout the year and the role of discounts and coupons.
- Recognizing the highest spending customers and understanding their preferences.

---

## **Exploration Questions**  
The project addresses key questions related to online shopping behavior:

- What are the demographics of online shoppers, and how do platform usage patterns vary by gender and location?
- Which products or product categories are most popular among customers?
- How do spending patterns fluctuate throughout the year, and what impact do discounts and coupons have?
- Who are the highest spending customers, and what are their preferences?

---

## **Tools and Technologies**  
The project leverages several tools and technologies for data analysis and visualization:

- **SQL (Structured Query Language)**: Used for data manipulation, exploration, and analysis.
- **SQL Server Management Studio (SSMS)**: For creating the relational database, parsing data, and initial exploration.
- **Tableau**: For creating interactive visualizations and dashboards based on SQL query findings.
- **Excel**: The dataset was initially in Excel format for easy exploration before being transitioned to SQL and Tableau.

These tools combined allowed for a comprehensive approach from database creation to insightful visualizations.

---

## **Approach**  
The process of completing the project involved several steps:

1. **Dataset Acquisition**: The online shopping dataset was sourced from Kaggle in Excel format.
2. **Database Creation**: A relational database was built in SQL Server Management Studio (SSMS), with tables for Customers, Products, and Transactions.
3. **Data Import & Parsing**: The dataset was imported into SSMS, and SQL queries were used to parse data into respective tables.
4. **Data Cleaning**: Ensured data consistency and quality by addressing missing or inconsistent values.
5. **Exploration & Analysis**: SQL queries were employed to explore key attributes, uncover patterns, and identify insights into customer behavior, product popularity, and spending.
6. **Visualization with Tableau**: The database was imported into Tableau to create a series of visualizations based on the SQL analysis. Interactive dashboards were created to display insights.

---

## **Data Visualizations**  
The visualizations in Tableau were designed to uncover trends, patterns, and relationships within the dataset. Notable visualizations include:

- **Bar Graphs**: For analyzing customer demographics, total sales by product category, and the highest spending consumers.
- **Area and Bar Graphs**: For comparing average discount percentages versus total sales throughout the year.
- **Packed Bubble Chart**: Showcasing total spending distribution across various locations.
- **Treemaps**: For visualizing product categories by total sales.

### **Dashboards**  
The visualizations were grouped into the following five dashboards:

1. **Customer Demographics Dashboard**: Analyzes gender distribution by location.
2. **Sales Analysis Dashboard**: Explores total sales by product category and customer distribution.
3. **Location Analysis Dashboard**: Examines total spending across locations and product categories.
4. **Consumer Spending Dashboard**: Identifies the highest spending consumers and their product breakdown.
5. **Coupon Engagement Dashboard**: Analyzes coupon usage trends over the year.

After receiving feedback, the five dashboards were consolidated into a **comprehensive Online Shopping Insights Hub**, providing a holistic view of the analysis.

---

## **Files Included**  
- **Individual Visualizations**: Individual charts and graphs created in Tableau.
- **Dashboards**: Images of interactive dashboards created in Tableau.
- **README.md**: This file provides an overview of the project.
- **create_database.sql**: Raw SQL query for constructing the relational database.
- **analyze_data.sql**: SQL query for extensive dataset exploration.
- **er-diagram.png**: ER diagram depicting the relational database structure.
- **online_shopping_analytics.twbx**: Tableau file containing all data visualizations and interactive dashboards.

---

## **Conclusion**  

### **Customer Demographics**  
The Customer Demographics Dashboard reveals a notable gender skew, with females dominating the platform across all locations. Additionally, female customers tend to stay longer on the platform than males. Further exploration of gender-based product preferences is recommended.

### **Sales Analysis**  
The Sales Analysis Dashboard shows that office items constitute 37% of total sales. Interestingly, offline sales (in-store) still contribute significantly to overall customer expenditure. Discounts do not correlate strongly with total sales or customer spending, contrary to assumptions.

### **Location Analysis**  
The Location Analysis Dashboard indicates that Chicago and California perform better than New York, New Jersey, and Washington D.C. Interestingly, apparel items are the top-selling category in Chicago and California, even though office items are more frequently purchased.

### **Consumer Spending**  
The Consumer Spending Dashboard highlights that the highest spending customers invest in apparel, office supplies, Nest products, and drinkware, consistent with the product category findings from other dashboards.

### **Coupon Engagement**  
Coupon usage remains steady throughout the year, though the number of coupon clicks peaks in August. This suggests that current coupon offers may not be compelling enough to significantly impact customer purchase behavior.
