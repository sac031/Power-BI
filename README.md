# Power BI Dashboard Report

## Introduction

This analysis is for leading e-commerce marketplace in Portugal, connecting small businesses to customers via a single, streamlined platform. This report analyzes the commercial data from given data, providing insights into various aspects of the business operations.
Dashboard Analysis
Each question/task outlined in the Power BI Project is addressed in this section. For each question, the following details are provided:
Question/Task, Visualization, Explanation, Key Insights, Summary
Question 1: Identify the rating distribution in the ShopNest dataset, showcasing ratings categorized as Excellent, Very Good, Good, Bad, and Very Bad, along with corresponding orders.
Visualization:
Explanation:
The provided dataset contains ratings for orders from the ShopNest Store, categorized into five distinct levels: Excellent, Very Good, Good, Bad, and Very Bad. The table below summarizes the count of orders for each rating category:
Review Category	Orders Count
Bad	3196
Excellent	57000
Good	8203
Very Bad	11712
Very Good	19062

Key Insights:
Excellent: The highest number of orders, with a total count of 57,000, falls under the 'Excellent' category. This indicates a strong positive customer feedback for a significant portion of the orders.
Very Good: The second-highest rating, 'Very Good', has 19,062 orders, reflecting a generally favourable customer experience.
Good: The 'Good' category has 8,203 orders, suggesting that while the majority of customers were satisfied, there is room for improvement.
Bad: The 'Bad' category contains 3,196 orders, indicating a smaller but notable portion of dissatisfied customers.
Very Bad: The 'Very Bad' category has 11,712 orders, showing a significant number of highly dissatisfied customers.
Visual Analysis:
The pie chart clearly demonstrates the distribution of ratings across the five categories. The 'Excellent' category dominates the distribution, followed by 'Very Good' and 'Very Bad'. This distribution highlights areas of success as well as areas needing attention and improvement.
Summary:
The rating distribution analysis reveals that while the majority of customers are highly satisfied with their purchases, there is a noticeable segment of orders that received negative feedback. Addressing the concerns of the 'Bad' and 'Very Bad' categories could further enhance customer satisfaction and overall business performance.
Question 2: What are the top 10 and bottom 18 most popular product categories in the ShopNest dataset? Please list them based on the number of orders.
Visualization:
Explanation:
The dataset provides the count of orders for various product categories in the ShopNest Store. Below are the top 10 and bottom 18 product categories based on the number of orders:
Key Insights:
1.	Top Category: The most popular product category is 'Bed, Bath & Table' with 9,311 orders, indicating a high demand for these items.
2.	High Demand Categories: Categories like 'Health & Beauty', 'Sports & Leisure', and 'Computers & Accessories' also show significant order counts, highlighting their popularity among customers.
3.	Least Popular: The least popular category is 'Security and Services' with only 2 orders, suggesting very low demand.
4.	Niche Categories: Several categories such as 'Gaming PC', 'La Cuisine', and 'Portable Kitchen and Food Processors' have very few orders, indicating niche markets.
Visual Analysis:
The table visual provides a clear representation of the order counts for each product category. The top 10 categories dominate the chart, showcasing the products that are in high demand, while the bottom 18 categories have significantly lower order counts.
Summary:
The analysis of product categories by order count helps in identifying the most and least popular products in the ShopNest Store. This information is crucial for inventory management, marketing strategies, and understanding customer preferences. Focusing on high-demand categories while exploring ways to boost the popularity of less popular categories could enhance overall business performance.

Question 3: List the total number of active sellers by yearly and monthly.
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dataset provided lists the total number of active sellers by year and month. Below is the summarized data:
Year	Month	TotalActiveSellers
2018	August	1395
2018	July	1193
2018	May	1151
2018	June	1116
2018	April	1098
2018	March	1001
2018	February	938
2018	January	935
2017	December	928
2017	November	918
2017	October	772
2017	September	724
2017	August	687
2017	July	590
2017	May	587
2017	June	549
2017	April	476
2017	March	472
2017	February	410
2017	January	177
2016	October	141
2018	September	55
2016	September	2
2016	December	1
2020	February	1
2020	April	1

Key Insights:
1.	2018 Peak: The highest number of active sellers was recorded in August 2018, with a total of 1,395 active sellers. This indicates a peak in seller activity during this month.
2.	Growth Trend: There is a clear upward trend in the number of active sellers from 2016 to 2018, showing significant growth in seller participation over these years.
3.	2017 Increase: The year 2017 shows a gradual increase in active sellers, with noticeable growth starting from January (177) and reaching a peak in December (928).
4.	Early Activity: Initial activity in 2016 was minimal, with only a few active sellers in September (2), December (1), and October (141).
5.	Sparse Data in 2020: There are very few entries for the year 2020, with only 1 active seller in both February and April as there was pandemic hit during this period.
Visual Analysis:
The line chart illustrates the fluctuation and growth in the number of active sellers over the given months and years. The sharp increase in 2017 and the peak in 2018 highlight significant growth periods.
Summary:
The data on active sellers by year and month provides valuable insights into the growth trajectory of seller participation on the ShopNest platform. The peak in 2018 suggests a period of high engagement, which could be analysed further to understand the factors contributing to this increase. Sparse data in 2020 indicates a potential need for more recent data to analyse current trends.
Question 4: Which payment methods are most commonly used by ShopNest customers?
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dataset lists the payment methods used by ShopNest customers along with the count of orders for each payment type. Below is the summary of the data:
Payment Type	Orders Count
boleto	19784
credit_card	75387
debit_card	1527
not_defined	3
voucher	2739

Key Insights:
1.	Credit Card: The most commonly used payment method is the credit card, with a total of 75,387 orders. This indicates a strong preference for credit card transactions among ShopNest customers.
2.	Boleto: The second most popular payment method is 'boleto' with 19,784 orders. This shows that a significant portion of customers prefer this method.
3.	Voucher: 'Voucher' is used for 2,739 orders, making it the third most common payment method.
4.	Debit Card: With 1,527 orders, debit cards are less popular compared to credit cards and boletos.
5.	Not Defined: There are only 3 orders with an undefined payment method, which is negligible in the overall data.
Visual Analysis:
The pie chart provides a clear representation of the distribution of payment methods used by customers. The visual highlights the dominance of credit card transactions, followed by boleto and voucher payments.
Summary:
The analysis of payment methods used by ShopNest customers reveals that credit cards are the preferred method, followed by boleto and voucher. Understanding these preferences can help ShopNest in optimizing payment options and improving customer experience.
Question 5: Identify the product category-wise profit margin using the formula.
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dataset provides the profit margins for various product categories in the ShopNest Store. Below is the summary of the data:
Key Insights:
1.	High Profit Margins: Categories like 'CDs & DVDs Musicals', 'Fashion Children's Clothes', 'Flowers', 'Home Comfort 2', and 'Security and Services' have the highest profit margins at 100%, indicating maximum profitability in these areas.
2.	Moderate Profit Margins: Categories such as 'Home Appliances 2', 'Electronics', and 'Luggage & Accessories' have moderate profit margins, indicating steady profitability.
3.	Lower Profit Margins: 'Watches & Gifts', 'Health & Beauty', and 'Sports & Leisure' have comparatively lower profit margins, suggesting lower profitability in these categories.
Visual Analysis:
The area graph provides a clear representation of the profit margins for each product category. The visual highlights the categories with the highest and lowest profit margins.
Summary:
The analysis of product categories by profit margin helps in identifying the most and least profitable products in the ShopNest Store. This information is crucial for strategic decision-making, inventory management, and maximizing profitability. Focusing on high-profit margin categories while exploring ways to improve the profitability of lower-margin categories could enhance overall business performance.

Question 6: Determine the monthly payments made by customers using credit cards.
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dataset provides the monthly payments made by customers using credit cards in the ShopNest Store. Below is the summary of the data:
MonthYear	Payments Made
Nov-17	933280.86
Apr-18	928553.64
Mar-18	926947.63
May-18	922229.46
Jan-18	862281.62
Jun-18	799542.68
Jul-18	795467.43
Aug-18	790953.57
Feb-18	773534.96
Dec-17	674643.44
Oct-17	607283.75
Sep-17	567625.78
Aug-17	513636.52
Jul-17	450486.71
May-17	437278.41
Jun-17	385355.84
Mar-17	352533.4
Apr-17	315481.33
Feb-17	224636.69
Jan-17	108644.64
Oct-16	48112.12
Sep-16	252.24
Dec-16	19.62

Key Insights:
1.	Highest Payments: The highest monthly payment value was recorded in November 2017, with a total of 933280.86.
2.	Increasing Trend: From January 2017 to November 2017, there was a steady increase in monthly payments, indicating growing customer activity and possibly an increasing customer base.
3.	Seasonal Variations: There are noticeable peaks in certain months, which could indicate seasonal shopping trends. For example, November and December 2017 saw significant payment values, likely due to holiday shopping.
4.	Initial Growth: In the initial months (from September 2016 to January 2017), the payment values were relatively low, but there was a rapid increase thereafter, suggesting a growth phase for the ShopNest Store.
Visual Analysis:
The column chartprovides a clear representation of the monthly payments made using credit cards. The visual highlights the increasing trend over time and the significant peaks during certain months.
Summary:
The analysis of monthly payments made by customers using credit cards helps in understanding the spending patterns and seasonal trends in the ShopNest Store. This information is crucial for financial planning, marketing strategies, and inventory management. Focusing on high-payment months and preparing for seasonal peaks could enhance overall business performance.
Question 7: Identify sellers categorized by city, excluding cities starting with the letters S and B.
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dataset provides the count of sellers in various cities. The cities starting with the letters S and B have been excluded from the analysis. Below is a summary of the data for the included cities:
Key Insights:
1.	Top Cities with Highest Seller Count:
o	Curitiba leads the chart with 127 sellers, significantly higher than the other cities. This indicates a strong seller presence, possibly due to favourable business conditions or a larger population.
o	Rio de Janeiro follows with 96 sellers, showing its importance as a major commercial hub.
o	Ribeirao Preto and Guarulhos have 52 and 50 sellers, respectively, also indicating a substantial seller base.
2.	Mid-Range Cities:
o	Cities like Ibitinga (49), Campinas (41), and Maringa (40) have a moderate number of sellers, reflecting their balanced economic activity.
o	Osasco (32), Porto Alegre (28), and Londrina (26) also have a considerable number of sellers, showing a strong regional presence.
3.	Cities with Emerging Seller Base:
o	Goiania (23), Joinville (22), and Franca (20) represent cities with emerging seller bases, possibly growing markets or regional centers.
o	Caxias do Sul and Florianopolis each have 18 sellers, indicating a developing market presence.
4.	Smaller Seller Presence:
o	Cities like Limeira (17), Marilia (15), and Mogi das Cruzes (15) show a smaller but notable seller presence.
o	Cascavel and Jundiai both have 14 sellers, indicating localized business activities.
5.	Minimal Seller Presence:
o	A large number of cities have seller counts ranging from 4 to 13. These include Maua (13), Contagem (12), Piracicaba (12), and many others with counts around 10.
o	These cities might be smaller markets or areas where business activities are just starting to pick up.
Summary:
The data shows a clear concentration of sellers in larger, more economically active cities like Curitiba and Rio de Janeiro. Mid-sized cities also have a healthy number of sellers, while smaller cities and emerging markets show a growing presence. This distribution could be influenced by factors such as population density, economic opportunities, infrastructure, and regional economic policies.

Question 8: Create a Dynamic Visual that Compares the Number of Delayed Orders to the Number of Orders Received Earlier for Each Month
Visualization:
Include an image of the corresponding visualization(s) in the dashboard here.
Explanation:
The dynamic visual above illustrates the comparison between the number of delayed orders and the number of on-time orders for each month. The line chart effectively displays trends over time, allowing for a clear comparison of order statuses across different months.

Key Insights:
•	Peak On-Time Deliveries: January 2018 had the highest number of on-time deliveries with 6,805 orders.
•	Fluctuations: There are noticeable fluctuations in the number of on-time orders from month to month. For example, a significant drop in on-time orders can be observed in February 2017 (1,727 orders), followed by a rise in subsequent months.
•	Delayed Orders: The highest number of delayed orders occurred in March 2018 with 1,496 orders. Other months with relatively high delayed orders include February 2018 (1,049 orders) and November 2017 (1,043 orders).
•	Recent Trends: More recent months, such as September and October 2018, show a significant decline in both on-time and delayed orders.
Drill-Through Analysis:
Using the drill-through cross-report feature, users can click on a specific month to view a detailed breakdown of the delayed and on-time deliveries. This feature provides deeper insights into factors affecting delivery performance in specific periods. For example, drilling through to March 2018 reveals the reasons behind the spike in delayed orders.
Summary:
The visual aids in understanding delivery performance over time, highlighting both successful on-time deliveries and areas needing improvement due to delays. This information is crucial for operational adjustments and improving overall customer satisfaction.

