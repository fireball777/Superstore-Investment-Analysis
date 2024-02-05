# Superstore Investment Analysis


### Project Overview

Strategic Assessment and Investment Feasibility: An In-depth Revenue Analysis of Superstore for Potential Investment 

![Dashboard Superstore](https://github.com/fireball777/Superstore-Investment-Analysis/assets/147949298/d8e0291d-9abd-4593-be05-b7c800d92275)


### Problem Statement

Superstore is a retail store with an increasingly growing profit rate, Superstore focuses on products such as phones, chairs, tables, binders, accessories and the like. Superstore has sales of approximately 2.3 million and a profit of 286,000. Moreover, Walmart is a retail store interested in investing in Superstore, to move with this venture, a consultant team was formed to conduct a revenue analysis on Superstore. The revenue analysis consists of a correlation analysis between profit and discount, sales in subcategories, correlation between sales and years, and average delivery days by shipping mode. The consultant team is to determine whether Superstore is a good investment opportunity and provide insights into the company's revenue analysis as concerns to the performance of Superstore.
This report accrues the findings of the consultancy firm, the report will focus on interpreting the results of the dashboard created using Power BI and the Superstore Excel sheet including its various variables. It will use the SWOT theoretical framework to create an academic foundation and strong basis for the report. The SWOT analysis will provide an internal strength and weakness and external opportunities and threats analysis to ascertain and determine the viability of investing in Superstore (Gurl, 2017).

### Data Source

Data was sourced from a data repository from Kaggle: [click here](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)

### Tools Utilised 

- Excel - Data cleaning
- SQL Server - Data Analysis
- PowerBI - Data Visualisation 

### Data Cleaning/Preparation

In the initial data preparation stage the following actions were performed:

1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.

### Exploratory Data Analysis

EDA involves manipulating the data to answer important questions such as:

- What is the correlation between profit and discount and how does it affect overall business 
- What is the quantity Sold per year and what year has the most sales
- When is the average delivery days by shipping mode
- Why is sales and profit low or high by year
- What causes the percentage profit by certain states

### Data Analysis

To include some fun features/code I worked with 

```sql
SELECT * FROM table1
WHERE cond = 2;
```

### Results / Findings

1. Higher discounts lead to short-term sale spikes but are detrimental to long-term profit
2. It is observed that there is a gradual upward turn in sales as the years go by
3. Potential challenges related to product availability on the shelves

### Recommendations

Recommendations for Superstore include optimisation of pricing strategies based on the observed correlation between discount and profit. Use data-driven insights to enhance product performance, particularly in high-performing categories like phones and chairs. Also, Superstore could streamline the supply chain and inventory management based on delivery days analysis. The store can Implement dynamic delivery solutions, emphasising same-day delivery for top-selling categories. Then again, Superstore can tailor marketing initiatives to capitalise on strengths identified in the top subcategory sales and explore phased geographic expansion strategies targeting regions with growth potential. Finally, the store can establish a continuous monitoring framework with agile adaptation strategies whilst developing a robust investor communication plan with Walmart. Walmart is advised to consider a phased investment approach while strengthening Superstore’s business processes.

### Limitations 

I removed all zero values to reduce errors in analysis, however, there were still a few outliers detected

### Reference

Gurl, E., 2017. SWOT analysis: A theoretical review. Available at: https://demo.dspacedirect.org/handle/10673/792 Accessed [11 Nov 2023]
Eckerson, W.W., 2010. Performance dashboards: measuring, monitoring, and managing your business. John Wiley & Sons. Available at: https://books.google.com/books?hl=en&lr=&id=5nuYDwAAQBAJ&oi=fnd&pg=PR9&dq=Eckerson,+Wayne+W.+(2006),+Performance+dashboards:+measuring,+monitoring,+and+managing+your+business,+John+Wiley+&+Sons,+New+Jersey.&ots=AKI9xRPrnz&sig=UGd0GdZAIhSuPjxC_72rtQ_TZGs Accessed [12 Nov 2023]

:🤗🤗🤗
