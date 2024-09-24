# Zomato-Restaurant-Analyss
Zomato Restaurant Expansion Analysis
Overview
This repository contains the data analysis conducted to support Zomato's strategy for restaurant expansion. The analysis covers data cleaning, exploration, and visualization to answer key questions related to Zomato's expansion opportunities, while providing actionable insights.

Table of Contents
Introduction
Objective Questions
Data Cleaning and Handling Missing Values
Number of Restaurants Opened in Each Country
Number of Restaurants Opened Each Year
Total Number of Restaurants in India with a Price Range of 4
Average Number of Voters for Restaurants in Each Country
Subjective Questions
Suggested Countries for New Restaurant Openings
Suitable States and Cities for Expansion
Current Quality Regarding Ratings
Current Expenditure on Food
Competitors and Poorly Rated Restaurants
Focus on Cuisines
Impact of Online Delivery and Table Booking
Correlation Between Rates and Ratings
Distribution of Restaurants by Price Range
Dashboard Overview
Conclusion
Analysis Details
Objective Questions
Data Cleaning and Handling Missing Values:

Ensured data consistency by handling missing country names using VLOOKUP.
Excel Formula: =VLOOKUP(C2, 'country description'!A:B, 2, FALSE)
Number of Restaurants Opened in Each Country:

Created a pivot table to display the number of restaurants by country, visualized with a bar chart.
Number of Restaurants Opened Each Year:

Extracted year from the Datekey_Opening field and visualized the trends using a line chart.
Total Number of Restaurants in India with a Price Range of 4:

Used COUNTIFS to calculate the number of restaurants in India with a price range of 4.
Excel Formula: =COUNTIFS(D:D, "India", Q:Q, 4)
Average Number of Voters for Restaurants in Each Country:

Calculated the average number of voters per country using a pivot table and presented it with a line chart.
Subjective Questions
Suggested Countries for New Restaurant Openings:

Suggested countries with fewer restaurants and higher average ratings. Countries like Canada, the Philippines, Indonesia, Qatar, and Sri Lanka were identified as potential opportunities.
Suitable States and Cities for Expansion:

Suggested states and cities within the recommended countries based on data analysis.
Current Quality Regarding Ratings:

Analyzed the average restaurant ratings in the suggested countries using a pivot table.
Current Expenditure on Food:

Examined the average cost for two in the suggested countries to help control financial expenditure.
Competitors and Poorly Rated Restaurants:

Identified key competitors with low ratings (1-3) in the suggested countries.
Focus on Cuisines:

Analyzed which cuisines should be focused on based on popularity and customer feedback. Calculated correlation between cuisine rates and ratings.
Impact of Online Delivery and Table Booking:

Explored how online delivery and table booking options affected customer ratings.
Correlation Between Rates and Ratings:

Calculated the correlation coefficient between price range and ratings, which was 0.46, indicating a moderate positive correlation.
Distribution of Restaurants by Price Range:

Visualized the distribution of restaurants by price range in various countries using a stacked bar chart.
Dashboard Overview
The dashboard provides interactive elements like slicers for Country Name and Date to explore various metrics such as:

Number of restaurants by country
Average expenditure on food
Restaurant distribution by price range
Conclusion
The analysis provides insights that can support Zomato in its decision-making regarding:

Expanding into countries with lower competition and high ratings
Identifying suitable locations for new restaurant openings
Focusing on popular cuisines and improving services like online delivery and table booking to boost customer satisfaction.
Excel Functions & Techniques Used
VLOOKUP
COUNTIFS
Pivot Tables
Correlation Calculations
Data Visualization (Bar Charts, Line Charts, Stacked Bar Charts)
