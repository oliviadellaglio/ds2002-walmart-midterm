# ds2002-walmart-midterm
by Emma, Anastacia, Liv, and Caroline

## Overview
This project explores Walmart data to identify sales trends through data cleaning, manipulation, and visualization. The goal is to transform raw data into meaningful information that can give companies insight into consumer purchasing behavior and lead them to making smarter business decisions. 

## Dataset Description
This project uses real Walmart reatail transaction information about products, categories, and sales. 

We used OpenMeteo open source API for real data about the weather

## Data Cleaning and Preparation
Several steps were taken to perpare the data to analyze and interpret such as:

Filtering missing values and inconsitencies;
Standardizing product names, categories, and SKUs;
Consolidating overlapping categories;
Organizing data by category and date;

## Data Analysis and Visualization
Python was used to manipuate and analuze the data. Visualizations were created to examine trends in daily sales and didenfy categoeies with higher purchasing activity. Thus, we were able to determine patterns and changes in consumer behavior

## Tools and Technologies
In order to accomplish the goal, we used:

Python;
Pandas (data cleaning/manipulation);
Matplotlib (data visualization);
Google CoLab;
GiHub;

## Key Findings
Data Cleaning and Preparation: We cleaned 25,562 raw transactions into 24,521 usable transactions across 12 Florida stores. We also standardized 45 SKUs into 20 products and removed 881 rows with missing timestamps.
Storm-Related Demand Surge: Sales began increasing around September 5, peaked on September 13–14, and returned to normal levels by September 18. During the surge week, average daily sales were approximately 2.2 times the baseline.
Highest-Demand Categories: Breakfast products, particularly Strawberry Pop-Tarts, experienced the largest increase in demand at 327%, reaching 9.5 times baseline sales on the peak day. Emergency supplies also experienced a significant increase of 149%.
Importance of SKU Consolidation: Four separate SKUs represented the same Strawberry Pop-Tarts product, hiding its actual demand. After consolidation, the product sold 5,005 units overall, averaging 167 units per day, 305 during the surge week, and 678 on its peak day. It ranked as the second-highest-selling product. Relying on fragmented SKU data could have underestimated peak demand by approximately 2.8 times.
Weather Correlations: Our analysis found no statistically convincing relationship between weather indicators and total store sales, and no useful weather-related lead time (|r| ≤ 0.27 in the lag analysis). Hurricane Helene's actual landfall on September 26 did not align with the simulated sales surge earlier in the month.
Geographic Sales Patterns: All 12 Florida stores experienced similar demand increases, ranging from approximately 2.0 to 2.4 times baseline sales. There was no clear geographic relationship between store location and surge intensity. Gainesville experienced the smallest and latest surge, while Tallahassee experienced the largest.
Board Game Demand: Board games showed a real but relatively modest increase in demand of approximately 2.1 times baseline, supported by two independent data sources. Inventory levels also declined during the surge. We recommend prioritizing emergency essentials while making a modest increase in board game inventory during future storms.
Importance of Data Processing and Analysis: Our findings demonstrate how data preparation and analytical choices affect business decisions. Using the calendar-based storm window produced an apparent 15% decline in sales, while analyzing the actual demand surge revealed a 117% increase. Similarly, SKU consolidation revealed that a seemingly average product was actually the second-highest-selling item. These findings highlight the importance of accurate data cleaning, appropriate comparison periods, and product standardization.
