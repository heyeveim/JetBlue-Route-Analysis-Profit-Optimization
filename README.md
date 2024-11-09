# ✈️ JetBlue Route Optimization and Profitability Analysis

## ⚙️ Project Overview

This project analyzes JetBlue's domestic round-trip routes to identify the most profitable routes and optimize ticket pricing. Using data-driven analysis, we aimed to develop insights that can enhance revenue through strategic route management and cost optimization.

## 📊 Data

The dataset includes key operational and financial information for flights, such as route details, passenger counts, ticket prices, baggage fees, and various operational costs (e.g., maintenance and delay penalties). This structured data provides a solid foundation to analyze factors impacting route profitability.

## 🔎 Key Analysis

- Top Routes by Traffic – Identified the 10 busiest round-trip routes based on passenger volume.
- Most Profitable Routes – Excluding upfront airplane costs, we calculated net profitability for each route by analyzing total revenue (ticket price, baggage fees) against total costs (maintenance, operation, delays).
- Breakeven Analysis – Performed breakeven analysis on ticket pricing strategies, considering different price levels and class-specific price sensitivity.

## 💼 Predictive Modeling

For profitability predictions, I employed Python to analyze profitability across various factors, using techniques such as:

- Data Aggregation: Summed and compared revenue and costs by route, airport type, and delay penalties.
- Profit Optimization: Adjusted ticket prices and baggage fees to determine breakeven points and maximize profitability.

## 📈 Business Insights

Ticket Price Adjustment – Increasing ticket prices within certain customer segments can drive higher margins without impacting demand significantly.
Baggage Fee Strategy – Doubling baggage fees on high-demand routes approaches breakeven more efficiently than ticket sales increases alone.
Top Performing Routes – Focused recommendations for routes with the greatest traffic and potential for price adjustment to maximize revenue.

## 🛠️ Skills Demonstrated

- Python Data Analysis – Employed Pandas, Matplotlib, and other libraries for data manipulation, visualization, and profitability analysis.
- Decision Modeling – Developed cost and revenue models to support strategic decisions.
- Business Insight Generation – Provided actionable recommendations based on statistical analysis and breakeven modeling.

## 🖍️ Next Steps

Future work could include incorporating additional variables, such as ticket price elasticity, customer demographics, and seasonal factors, to refine the model further. Additionally, deploying machine learning models could enhance predictive accuracy for revenue projections and route performance.
