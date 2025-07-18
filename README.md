# DSA-Amazon-Project-Review-Analysis
This is a project on Excel-based analysis of Amazon product reviews and customer engagement data

## Project Overview
This project analyzes Amazon product review data to generate insights for product improvement, marketing strategies, and customer engagement using Excel-based analytical tools.

## Dataset Description
- **Total Records**: 1,465 rows
- **Total Fields**: 16 columns
- **Data Source**: Amazon product pages (scraped data)
- **Analysis Period**: 2 weeks from start date

## Key Features
- Product details analysis (name, category, price, discount, ratings)
- Customer engagement metrics (reviews, titles, content)
- Comprehensive Excel dashboard with interactive visualizations

## Analysis Questions Addressed
1. Average discount percentage by product category
2. Product distribution across categories
3. Total reviews per category
4. Products with highest average ratings
5. Price comparison analysis (actual vs discounted)
6. Products with highest review counts
7. High discount products analysis (50%+ discount)
8. Rating distribution analysis
9. Revenue potential analysis
10. Price range segmentation
11. Discount vs rating correlation
12. Low-review products identification
13. Category-wise discount analysis
14. Top 5 products by combined rating and review metrics

## Tools Used
- Microsoft Excel
- Pivot Tables
- Excel Charts and Visualizations

## Project Structure
- `data/`: Raw and processed datasets
- `analysis/`: Excel workbooks with analysis
- `visualizations/`: Charts and dashboard screenshots
- `documentation/`: Supporting documentation
- `reports/`: Final analysis report

## Key Insights
Analyzed 1,465 Amazon products across multiple categories to identify key trends in pricing, customer engagement, and product performance. The analysis revealed significant insights for retail optimization and customer satisfaction strategies.

## Dashboard Features
- Interactive filters by rating
- Dynamic charts showing key metrics
- Summary statistics and KPIs
- Trend analysis visualizations

## Exploratory Data Analysis/Analysis Questions Answered
[Amazon case study.xlsx](https://github.com/user-attachments/files/21320466/Amazon.case.study.xlsx)

### Visualizations
1. Charts
- Rating vs Discount Level Correlation
<img width="1366" height="506" alt="Rating vs Discount Level Correlation" src="https://github.com/user-attachments/assets/ba0df14f-35c7-4901-b5a9-10db7fb74dfb" />


- Product Rating Distribution
<img width="1366" height="487" alt="Product Rating Distribution" src="https://github.com/user-attachments/assets/8a073208-e4e6-4dbc-a28d-5dd16b90d228" />


- Number of Unique Product Per Price Range Bucket
<img width="1355" height="514" alt="Number of Unique Products Per Price Range Bucket" src="https://github.com/user-attachments/assets/36a882c4-be11-4db0-8784-94c1d690ec0e" />


- Products with the Highest Average Rating
<img width="1366" height="515" alt="Products with the Highest Average Rating" src="https://github.com/user-attachments/assets/2fa8501a-e4ec-417f-a595-c965a5724703" />


- Products with the Highest Number of Reviews
<img width="1358" height="516" alt="Products with the Highest Number of Reviews" src="https://github.com/user-attachments/assets/16a1888e-baf8-41a7-9064-287d6ca88cac" />



- Product Category with the Highest Discount
<img width="1366" height="516" alt="Product Category with the Highest Discount" src="https://github.com/user-attachments/assets/030112f5-a98a-446b-9db5-61bf76ee2bcc" />



- Top 5 Products in Trems of Rating and Reviews Combined
<img width="1023" height="509" alt="Top 5 Products in Trems of Rating and Reviews Combined" src="https://github.com/user-attachments/assets/3ecc91ba-cc8a-44f8-bc01-63ef667839b8" />



2. Dashboard Screenshot
- Excel Dashboard
 <img width="1294" height="519" alt="Excel_Dashboard" src="https://github.com/user-attachments/assets/ff826f81-510f-4334-83ee-add294548738" />



## Amazon Analysis Report

Based on the dashboard data, the following are key findings:

**1.	Rating vs Discount Correlation**

Key Findings:

Products with ratings between 4.0-4.3 show the highest discount levels (8,000-11,000+ products), indicating this is the sweet spot where discounts drive volume without compromising perceived quality. Also, very low ratings (2.0-3.0) have minimal discount activity, suggesting these products are either removed from market or don't warrant promotional investment. Products with perfect 5.0 ratings show lower discount frequency, indicating strong brand equity that doesn't require heavy discounting.

**2.	Product rating Distribution**

Key Insights:

Products clustered (230) around 4.3-4.4 ratings with sharp decline toward perfect ratings. The concentration around 4.0+ ratings (over 1,000 products) indicate generally high customer satisfaction. However, very few products below 3.0 rating, suggesting effective quality management or removal of poor performers.

**3.	Top Product Analysis (Product with the Highest Number of Reviews)**

Fire-Boltt Ninja Call Pro Plus Smart Watch Dominance:

This smartwatch has the highest number of reviews, indicating strong market penetration and it happens to be that wearable technology/smartwatches appear to generate high customer engagement. Therefore, Fire-Boltt has achieved significant market presence in the competitive wearables space.

**4.	Top 5 Products Combined Score (Rating and Review Number)**

Performance Insights:

All top 5 products maintain ratings of 3-5, with most at 4-5 range. Combined scores of 13.2-21 indicate balanced performance between quality and customer engagement making these products represent the gold standard for rating-review balance.

**5.	Price Distribution Analysis (Number of Unique Products Per Price Range Bucket)**

Market Segmentation:

-	Budget Dominance: 1,245 products under $200 (83% of market) indicates price-sensitive customer base.
-	Premium Niche: Only 37 products in $200-500 range and 183 products >$500 suggest limited premium market appetite.
-	Volume Strategy: Success heavily dependent on competitive pricing in sub-$200 category.

**6.	Product Categories with Highest Discounts**

Electronics|HomeTheater,TV&Video|Televisions|SmartTelevisions shows $1,564,932 in discounted value, and heavy discounting in electronics suggests mature, competitive market. We can deduce that customers expect significant discounts on high-ticket electronic items.

## **Strategic Business Insights**

With the above findings, there are few insights that can guide product improvement, marketing strategies, and customer engagement. The following are deduced insights:
Market Positioning:

1.	Price-Quality Balance: Success requires maintaining 4.0+ ratings while competing aggressively on price in the sub-$200 segment.
2.	Volume Over Margin: Business model favors high-volume, lower-margin products rather than premium positioning.
3.	Customer Expectations: Customers in this market segment expect both quality 4.0+ ratings, and value heavy discounts.

**Operational Insights:**
1.	Inventory Focus: 83% of products should be positioned under $200 to match market demand
2.	Quality Threshold: Products below 3.5 rating should be prioritized for improvement or discontinuation
3.	Discount Strategy: Electronics categories require substantial discount budgets to remain competitive
Growth Opportunities:
1.	Premium Gap: Limited competition in >$500 category might represent untapped opportunity for differentiated products
2.	Review Generation: Learning from Fire-Boltt's success in generating reviews could improve engagement across portfolio
3.	Category Expansion: Success in electronics suggests potential for expansion into related high-discount categories

**Risk Factors:**
1.	Margin Pressure: Heavy reliance on discounting in primary categories threatens profitability
2.	Market Saturation: 1,245 products under $200 indicates intense competition in core market segment
3.	Quality Maintenance: Need to maintain 4.0+ ratings while competing on price creates operational challenges
This data reveals a highly competitive, price-sensitive market where success depends on balancing quality maintenance with aggressive pricing strategies, particularly in the electronics category.




## Contact
[Gideon Taiwo Otolorin] - [otoloringideon@gmail.com]
Project Link: https://github.com/Gideon1436/amazon-product-review-analysis
