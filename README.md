Food Delivery Business Performance Analysis 🍔🛵


Overview
This repository contains a data visualization portfolio created to analyze the performance of a simulated food delivery business. By leveraging Python data visualization libraries, this project explores a comprehensive dataset to uncover meaningful patterns regarding revenue, operational efficiency, and customer satisfaction.

This project was completed as part of the Food Delivery Data Visualization Portfolio (Day 14) assignment.

Dataset
The analysis is based on the Day14_Food_Delivery_Visualization_Dataset.csv dataset, which includes data on:

Order details (Batches, Channels, Dates)

Financial metrics (Revenue, Average Order Value, Marketing Spend, Discounts)

Operational metrics (Average Delivery Minutes, Weather conditions)

Customer metrics (Ratings, Repeat Customer Percentage)

Demographics (Cities, Cuisines)

Technologies Used
Python 3

Pandas: Data manipulation and aggregation

Matplotlib: Foundational plotting and trend visualization

Seaborn: Advanced statistical data visualization

Visualizations Included
To thoroughly investigate the business's performance, the following visualizations were created:

Line Plots: Trend analysis of Orders and Revenue over time.

Bar Charts: Comparisons of Average Revenue by City and Total Orders by Cuisine.

Scatter Plots: Correlation checks between Marketing Spend vs. Revenue, and Delivery Time vs. Customer Rating.

Histograms: Distribution of the Average Order Value.

Box Plots: Revenue distribution across different cities.

Violin Plots: Customer Rating distribution by Order Channel.

Count Plots & Bar Charts: Impact of weather conditions on order volume.

Correlation Heatmap: A macro-view of relationships between all numerical features.

Key Insights & Findings
Delivery Speed is Critical: Average delivery minutes have a strong negative correlation (-0.88) with customer rating. Slower deliveries severely hurt customer satisfaction and are negatively correlated with repeat customer percentages.

Location Trumps Cuisine: Average revenue varies by up to ~30% between top-performing cities (like Bengaluru) and lower-performing ones (like Kochi). Meanwhile, the variance in revenue across different cuisine types is much narrower.

Seasonality Exists: Orders and revenue show clear seasonal peaks around March-April, June, and December, rather than steady linear growth.

Marketing Spend is Not a Magic Bullet: Marketing spend has only a weak positive correlation (~0.20) with revenue, suggesting that increasing spend alone isn't enough to drive revenue without optimizing other operational factors.

Channel & Weather Impacts are Modest: The App channel slightly edges out Website and Partner Platforms in customer ratings, and Hot weather sees slightly more orders than Cloudy weather, though neither swings overall performance dramatically.

How to View
To view the analysis, simply click on the Food Delivery Business Performance.ipynb file above. GitHub will render the Jupyter Notebook natively, allowing you to view the code, charts, and interpretations.

