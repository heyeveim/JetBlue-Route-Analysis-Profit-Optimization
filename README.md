# ✈️ JetBlue Route Profitability and Optimization Analysis

## Executive Summary
In this project, I simulated a strategic expansion scenario for JetBlue Airways by identifying the top five most profitable U.S. domestic round-trip routes. Using Q1 2019 real-world data, I performed profitability modeling, breakeven analysis, and KPI design to support investment decisions aligned with JetBlue's operational values, particularly punctuality and customer satisfaction.

This project showcases how data-driven insights can support multi-departmental business decisions, with applications in finance, operations, and marketing.


## Project Objectives

- Identify the 10 busiest round-trip routes in terms of flight volume
- Calculate the 10 most profitable round-trip routes based on revenue and cost modeling
- Recommend 5 high-potential routes for investment
- Perform breakeven analysis considering a $90M aircraft acquisition cost
- Define KPIs to monitor long-term route performance and profitability


## Data Overview

This project leverages three datasets:

- **Flights Dataset**: Includes route-specific details, occupancy rates, and delays
- **Tickets Dataset**: Contains round-trip ticket prices and baggage fee info
- **Airport Codes Dataset**: Classifies airports as medium or large


## Methodology

1. **Data Cleaning & Integrations**:
    - Removed outliers and handled missing values to ensure data quality
    - Merged flight, ticket, and airport data to create a comprehensive route-level dataset
   
2. **Profitability Modeling**:
    - Estimated revenue from ticket sales and baggage fees
    - Modeled operational costs (fuel, maintenance, delay penalties, airport fees)
    - Calculated net profit and breakeven point per route
  
3. **Route Evaluation**:
    - Ranked routes by both flight volume and profitability
    - Prioritized routes that aligned with JetBlue’s motto: “On time, for you”


## Key Analysis & Recommendations

- **Top 10 Busiest Routes**:
    - Identified using aggregated flight volume across Q1 2019. These routes represent high-demand corridors for potential investment.
- **Most Profitable Route*s**:
    - Net profitability calculated by subtracting modeled operating costs from expected revenue.
    - Note: Aircraft purchase costs excluded in profit calc, but considered separately in breakeven analysis.
 


--> See the chart below for a visual summary of route profitability:

<img width="1512" height="918" alt="Image" src="https://github.com/user-attachments/assets/a5794e08-0f63-488e-9ad3-96169a470821" />


- **Recommended Top 5 Routes**:
    Chosen based on:
    - High revenue margins
    - Strong customer demand
    - Low average delay rates (aligned with JetBlue’s punctuality standard)


<p align="center">
  <img src="https://i.imgur.com/qQEdDBd.png" width="500" />
  <br />
</p>
<p align="center">
  <img src="https://i.imgur.com/NTn0wR1.png" width="500" />
  <br />
</p>



## Business Insights & KPIs

**Insights**
- Increasing ticket prices on peak-demand routes improves margins with minimal demand loss
- Adjusting baggage fee strategies can optimize auxiliary revenue
- Routes with consistent occupancy and lower delays offer highest long-term ROI

**KPIs Designed for Post-Launch Tracking**
| KPI                                        | Purpose                                                     |
| ------------------------------------------ | ----------------------------------------------------------- |
| **Customer Acquisition Cost (CAC)**        | Assess cost efficiency in acquiring new customers per route |
| **Customer Lifetime Value (CLV)**          | Forecast revenue potential per passenger                    |
| **On-Time Performance Rate**               | Measure punctuality, a JetBlue brand promise                |
| **Revenue per Available Seat Mile (RASM)** | Evaluate operational profitability per distance             |

    
<p align="center">
  <img src="https://i.imgur.com/uir6q3e.png" />
  <br />
</p> 


**Business Thinking Demonstrated**
This project mimics a real-world consulting case or internal analytics request.

It supports:
- Finance → Investment justification based on ROI and breakeven
- Marketing → Pricing strategy and demand segmentation
- Operations → Route efficiency and delay reduction


## Technical Skills Applied

| Category          | Tools / Techniques                                    |
| ----------------- | ----------------------------------------------------- |
| Programming       | Python (Pandas, NumPy), SQL                           |
| Analysis          | Cost modeling, breakeven analysis, revenue prediction |
| Visualization     | Matplotlib, Seaborn                                   |
| Data Handling     | Data cleaning, merging, custom join functions         |
| Business Concepts | KPI design, market sizing, customer behavior insights |



## Future Enhancements

- Add customer demographic segmentation (e.g., business vs. leisure travelers)
- Use machine learning for revenue prediction and delay pattern detection
- Incorporate seasonal demand shifts and event-based demand spikes
- Build an interactive dashboard (e.g., Tableau) to visualize route performance



## Reflections
This project allowed me to approach business problems from multiple perspectives, including finance, operations, and marketing. Rather than simply analyzing numbers, I focused on generating insights that align with strategic objectives such as maximizing route profitability while maintaining on-time performance.
Working with real-world data required me to clean, integrate, and model information across different sources. More importantly, it challenged me to turn those findings into clear, actionable recommendations that could support cross-functional decision-making.

It reinforced my belief that strong analytics is not just about technical accuracy, but about communicating insights in a way that drives business impact. I look forward to applying this mindset in future roles where data is used to inform investment, optimize performance, and enhance the customer experience.







