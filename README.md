# ✈️ JetBlue Route Profitability and Optimization Analysis

## ⚙️ Problem Statement

This project simulates a scenario where an airline, aiming to enter the U.S. domestic market, seeks to identify and invest in the most profitable round-trip routes. Given the airline’s motto, “On time, for you,” maintaining punctuality and maximizing profitability are crucial. Using real-world data from Q1 2019, our goal is to recommend five optimal round-trip routes between medium and large U.S. airports.

## 🎯 Project Objectives

1. **Identify the 10 busiest round-trip routes** in terms of flight volume.
2. **Calculate the 10 most profitable routes** based on revenue and operational costs.
3. **Recommend the top 5 routes** for investment based on profitability, customer demand, and operational factors.
4. **Perform breakeven analysis** for each selected route, considering the upfront cost of $90 million per airplane.
5. **Define KPIs** for ongoing performance tracking to ensure long-term profitability and alignment with brand values.

## 📊 Data Overview

This project leverages three datasets:

- **Flights Dataset**: Provides route-specific data, including occupancy rates and delays.
- **Tickets Dataset**: Contains sample ticket price information for round trips.
- **Airport Codes Dataset**: Classifies airports as medium or large for route selection criteria.

## 🔍 Methodology

1. **Data Cleaning & Quality Checks**: Identified and addressed key data issues such as outliers, missing values, and inconsistencies to ensure accurate analysis.
2. **Data Integration**: Joined datasets using customized functions to create a unified dataset, combining route, cost, and occupancy information.
3. **Profitability Analysis**:
    - Calculated revenue from ticket sales and baggage fees.
    - Assessed operational costs including fuel, maintenance, delays, and airport fees.
    - Conducted breakeven analysis to evaluate the minimum flights required to cover airplane acquisition costs.

## 🔎 Key Analysis & Results

- **Top 10 Busiest Routes**: Identified based on flight volume, providing insights into high-demand travel routes.
- **Most Profitable Route*s**: Analyzed net profitability by excluding upfront airplane costs, considering total revenue, operating expenses, and additional costs like delay fees.
- **Investment Recommendations**: Selected five routes based on factors such as profitability, demand, and alignment with the airline’s punctuality standards.

  ![Chart of data trends](images/screenshot.png)


## 📈 Business Insights & KPIs

- **Ticket Pricing Strategy**: Increasing ticket prices for certain customer segments improves margins without significantly reducing demand.
- **Cost Optimization**: Strategic adjustments to baggage fees and operational efficiencies on high-demand routes support profitability.
- **KPIs for Future Tracking**:
  - Customer Acquisition Cost (CAC)
  - Customer Lifetime Value (CLV)
  - On-Time Performance Rate
  - Revenue per Available Seat Mile (RASM)

## 💻 Technical Skills Demonstrated

- **Python**: Utilized for data manipulation (Pandas), visualization (Matplotlib), and regression modeling.
- **Data Analysis**: Conducted cost and profitability modeling to support investment recommendations.
- **Visualization**: Created charts to illustrate route performance and cost-benefit analysis, supporting data-driven decision-making.

## 🖍️ Next Steps

Future enhancements could include integrating customer demographic data and refining the model with machine learning for more accurate revenue predictions. Incorporating seasonal trends could further improve route selection strategies.
