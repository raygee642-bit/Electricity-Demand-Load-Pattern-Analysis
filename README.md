# Electricity Demand & Load Pattern Analysis

## Project Overview
This project provides a consolidated analysis of electricity demand across **12 distinct regions** (including PJME, AEP, and COMED) to solve the challenge of fluctuating consumption patterns influenced by seasonality and regional characteristics. By leveraging historical hourly load data, this analysis supports **data-driven decision-making** for electricity generation and distribution planning.

### The Core Challenge
*   **Problem:** The utility company lacks a consolidated, data-driven view of electricity demand, making it difficult to manage highly inconsistent consumption patterns across different regions and timeframes.
*   **Business Impact:** This lack of visibility leads to inefficient power generation schedules and inaccurate forecasting, which risks grid instability and increased operational costs.

## Executive Summary (KPIs)
The following key metrics represent the system's status compared to the previous year:
*   **Total Load (MW):** 791M (▲ 0.2% YoY).
*   **Maximum/Peak Load:** 59K (▲ 0.2% YoY).
*   **Average Load:** 9.42K (▼ 4.6% YoY).
*   **System Load Factor:** 15.94% (▼ 4.8% YoY).
*   **Annual Growth Rate:** 1.29% (▼ 76.6% YoY).

## Key Focus Areas & Business Impact
1.  **Regional Load Distribution**
    *   **Insight:** Regional imbalances exist; for example, **PJME** contributes the highest load at **35.1% (278M MW)**, while others like EKPC contribute significantly less.
    *   **Impact:** Identifying these gaps allows for targeted infrastructure investment and stabilized regional energy availability.
2.  **Temporal Consumption Patterns**
    *   **Insight:** Electricity demand fluctuates significantly by hour and season, with distinct morning and evening peaks.
    *   **Impact:** Enables optimized generation scheduling and the use of **dynamic pricing** to shift demand away from peak hours.
3.  **System Efficiency (Load Factor)**
    *   **Insight:** The load factor analysis shows system underutilization during off-peak hours.
    *   **Impact:** Highlights opportunities to reduce waste and improve the efficiency of power generation.
4.  **Forecasting & Predictive Trends**
    *   **Insight:** Current forecasting accuracy needs improvement, especially during high-demand periods.
    *   **Impact:** Enhanced forecasting models mitigate the risk of power outages and over-generation.

## Methodology (Power BI)
As a Data Analyst, I followed this structured workflow to develop the dashboard:
1.  **Data Transformation:** Cleaned and consolidated multiple regional hourly datasets into a unified model using Power Query.
2.  **Time Intelligence:** Created a dedicated Date Table to track Hourly Load Trends, Seasonal Variations (Q1–Q4), and "Hour vs. Day" load intensity.
3.  **DAX Calculations:** Developed measures for Total/Avg Load, YoY Growth, and **Load Factor** (Average Load / Peak Load) to measure grid efficiency.
4.  **Visualization:**
    *   **Heatmaps:** To visualize load intensity by hour and day of the week.
    *   **Treemaps:** To show the % Load Contribution by Region.
    *   **Line Charts:** To track seasonal variations across the four quarters.

## Insights & Strategic Recommendations
*   **Smart Grid Investment:** Invest in energy storage and smart grid infrastructure to stabilize demand in high-peak regions like PJME.
*   **Demand Side Management:** Implement dynamic pricing strategies to balance the system load.
*   **Advanced Analytics:** Integrate advanced time-series or machine learning approaches into Power BI for more accurate short-term forecasting.
*   **Continuous Monitoring:** Use the developed dashboard for real-time anomaly detection and operational cost optimization.

## Future Enhancements (Gap Analysis)
To further improve this analysis, future iterations should include:
*   **Weather Correlation:** Integrating temperature and humidity data to better understand weather-driven demand spikes.
*   **Financial Layer:** Adding cost-per-MW and revenue data to provide a full Financial ROI analysis.
*   **Customer Segmentation:** Distinguishing between residential, commercial, and industrial loads for more granular insights.
