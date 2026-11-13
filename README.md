# ds2002-walmart-midterm
by Emma, Anastacia, Liv, and Caroline

## Overview
This project explores Walmart data to identify sales trends through data cleaning, manipulation, and visualization. The goal is to transform raw data into meaningful information that can give companies insight into consumer purchasing behavior and lead them to making smarter business decisions. 

## Dataset Description
This project uses real Walmart retail transaction information about products, categories, and sales. 

We used OpenMeteo open source API for real data about the weather

## Data Cleaning and Preparation
Several steps were taken to prepare the data to analyze and interpret such as:

Filtering missing values and inconsitencies;
Standardizing product names, categories, and SKUs;
Consolidating overlapping categories;
Organizing data by category and date;

## Data Analysis and Visualization
Python was used to manipulate and analyze the data. Visualizations were created to examine trends in daily sales and identify categories with higher purchasing activity. Thus, we were able to determine patterns and changes in consumer behavior

## Tools and Technologies
In order to accomplish the goal, we used:

Python;
Pandas (data cleaning/manipulation);
Matplotlib (data visualization);
Google CoLab;
GitHub;
SQLite and sqlite3 (inventory and sales analysis);
Requests (weather API retrieval)

## Key Findings

1. **Data Cleaning and Preparation:** We cleaned 25,562 raw transactions into 24,521 usable transactions across 12 Florida stores.
2. **Storm-Related Demand Surge:** Sales began increasing around September 5, peaked on September 13–14, and returned to normal levels by September 18.
3. **Highest-Demand Categories:** Breakfast products experienced the largest increase in demand at 327%. Emergency supplies increased by 149%.
4. **Importance of SKU Consolidation:** Four separate SKUs represented the same Strawberry Pop-Tarts product, hiding its actual demand.
5. **Weather Correlations:** Our analysis found no statistically convincing relationship between weather indicators and total store sales.
6. **Geographic Sales Patterns:** All 12 Florida stores experienced similar demand increases, ranging from approximately 2.0 to 2.4 times baseline sales.
7. **Board Game Demand:** Board games showed a real but relatively modest increase in demand of approximately 2.1 times baseline.
8. **Importance of Data Processing and Analysis:** Our findings demonstrate how data preparation and analytical choices affect business decisions.

## Reflection 
## Project Reflection
Throughout this project, we learned how important data cleaning and analytical decisions are when interpreting sales patterns. One of our biggest challenges was determining the appropriate time period for analyzing hurricane-related purchasing behavior. At first, we focused on the seven days preceding Hurricane Helene's actual landfall on September 26. However, our data showed that the largest purchasing surge occurred nearly two weeks earlier. Comparing these different periods demonstrated how the same dataset could produce substantially different conclusions depending on the baseline and comparison windows selected.

Another challenge was consolidating inconsistent product SKUs. Strawberry Pop-Tarts looked like they were a relatively ordinary product because its sales were divided across four different identifiers. Once we standardized them, we found that it was actually the second-highest-selling product. This demonstrated how errors in data organization can affect real business decisions, particularly inventory planning.

We also learned the importance of questioning initial interpretations. Our analysis of board-game demand made us to distinguish between a real purchasing increase and possible data issues. We examined sales records, inventory levels, and SKU classifications, and we made a more evidence-based recommendation.

Overall, this project improved our ability to clean data, interpret visualizations, and turn findings into business recommendations. We also learned that accurate conclusions depend on the calculations, as well as the assumptions and decisions made throughout the analytical process.
