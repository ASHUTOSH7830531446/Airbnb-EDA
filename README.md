1. Introduction

This report presents an Exploratory Data Analysis (EDA) of an Airbnb dataset. The objective is to clean the dataset, analyze key variables, and extract meaningful insights related to pricing, room types, and neighborhood distribution.

2. Dataset Overview

The dataset contains Airbnb listings with the following key features:

Price
Service Fee
Room Type
Neighborhood Group
Reviews and Ratings
Host Information

The dataset includes both numerical and categorical variables, making it suitable for statistical and visual analysis.

3. Data Cleaning & Preprocessing

The following steps were performed:

Converted 'last review' column to datetime format
Handled missing values:
reviews per month → filled with 0
last review → filled with minimum date
Removed rows with missing:
NAME
host name
Dropped unnecessary columns:
license, house_rules
Cleaned monetary columns:
Removed $ and , from price and service fee
Converted to numeric format
Removed duplicate records
4. Exploratory Data Analysis
4.1 Price Distribution
The price distribution is right-skewed
Most listings are in the lower price range
Few listings are extremely expensive (outliers)
4.2 Room Type Distribution
Certain room types dominate the dataset
Indicates imbalance in listing categories
4.3 Neighborhood Analysis
Listings are concentrated in specific neighborhoods
Some areas show significantly higher density
4.4 Price vs Room Type
Different room types have distinct price ranges
Some room types are consistently more expensive
5. Key Insights
Majority of listings are affordable or mid-range
Dataset contains price outliers
Room type is a major factor affecting price
Neighborhood impacts listing availability and density
Dataset shows categorical imbalance
6. Conclusion & Next Steps

The EDA revealed important patterns in pricing and listing distribution.

Next Steps:
Feature Engineering
Outlier Treatment
Predictive Modeling (Price / Demand)
Advanced Correlation Analysis
7. Final Insight

EDA is not just about visualization—it is about understanding the data deeply and extracting actionable insights for decision-making.
