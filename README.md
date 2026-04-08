# London Housing: Market & School Catchment Analysis

An interactive [Power BI dashboard](https://app.powerbi.com/view?r=eyJrIjoiNDJiMjg1MTktYWE2Yy00NGY2LWI3ZWQtMTU4MjgxZmNhNGY0IiwidCI6IjZjMWQ0MTUyLTM5ZDAtNDRjYS04OGQ5LWI4ZDZkZGNhMDcwOCIsImMiOjEwfQ%3D%3D) for analyzing the London housing market, allowing users to explore property prices, features, school quality, and district-level trends.

<img src="./images/cover.png" width="" height="500">

---

## Skills Demonstrated
✔ **Business Intelligence & Visualization**
- Designed multi-page dashboards with clear navigation, drillthrough, and interactive filtering.
- Built geospatial maps, heatmap, word clouds and trend analysis to support market insights.

✔ **Data Modeling & Semantic Layer**
- Developed a *star schema* with fact and dimension tables.
- Managed relationships, cardinality, and DAX calculations for analytics.

<img src="./images/star.png" width="" height="500">

✔ **Analytical Insight & Storytelling**
- Analyzed property listings across different districts from the perspectives of pricing trends, schools ratings and property features.
- Modeled YoY (year-on-year) and QoQ (quarter-on-quarter) pricing trends and compared districts against the national median.

✔ **User Experience & Interaction**
- Enabled drillthrough and hover tooltips. 
- Implemented a comprehensive filter pane with numeric sliders, dropdowns, and school-related filters.

<img src="./images/filter_pane.png" width="" height="500">

---

## Use Case
> **Disclaimer:**  
> *This project uses synthetic data. All statistics, trends, and insights are for demonstration and educational purposes only and do not reflect actual London housing market conditions.*

This is a report designed for London Real Insights Ltd., a hypothetical real estate agency based in London.

It provides management of the Company with a comprehensive view of property listings across various districts in the city. Users can filter listings based on specific criteria, including property price, house features, and schools in the neighborhood. 

---

## Features

- **Dashboard**: Synthesized listings into high-level KPIs, including median asking prices, normalized property dimensions, and aggregated school performance.

 ![](images/dashboard.png)
- **School Analytics**: Map property listings by proximity to schools, Ofsted ratings, school size, and class size.

![](images/school.png)
- **Listings Explorer**: A breakdown of listings by district, location, sizes and feature word clouds.

![](images/listings.png)
- **Market Trends**: Track historical price trends, growth rates, and compare district prices to national medians. Identify the Top 10 highest-value districts by price per square foot.

![](images/market.png)

---

## Key Business Insights

- High-performing school districts (Ofsted "Outstanding") directly correlate with listing density and price stability. For instance, Harrow emerged as a top-tier "value" district, boasting the highest volume of listings (506) near Outstanding schools. 
- Highest asking prices concentrated in the centre (e.g. Kensington and Chelsea, Westminster, and City of London) and the most affordable options found on the outskirts.
- Despite short-term volatility, the 20-year trend line confirms London’s status as a resilient "safe haven" for capital, with consistent recovery patterns following the economic shocks in the 2008 financial crisis and the 2020 pandemic.
- Natural Language Processing (NLP) on property descriptions reveals that "Large" "Backyard" and "Family" are the most frequent keywords, signaling a permanent shift in buyer priorities toward square footage and outdoor space and family-friendliness.
  
---

## Workflow Overview

1. **Access Power BI report online** [here](https://app.powerbi.com/view?r=eyJrIjoiNDJiMjg1MTktYWE2Yy00NGY2LWI3ZWQtMTU4MjgxZmNhNGY0IiwidCI6IjZjMWQ0MTUyLTM5ZDAtNDRjYS04OGQ5LWI4ZDZkZGNhMDcwOCIsImMiOjEwfQ%3D%3D)
2. **Navigate via the sidebar or the homepage** to explore:
   - **Summary (Dashboard)**: Market snapshot and KPIs.
   - **Listings**: Average prices, property locations, and feature word clouds. Drill through market data of the selected district.
   - **Schools**: Listings by school rating, size, and proximity.
   - **Market**: Trends of the property price by districts and comparison to the national median.
3. **Interact with filters and slicers** to customize the analysis:
   - Filter by property price, year built, district, home type, or features.
  
---

## Data Sources

> **Note:**  
> All [datasets](https://raw.githubusercontent.com/cckmwong-data/london_housing/main/dataset/housing_data.xlsx) used in this project are synthetic, created to mimic real-world patterns for educational and analytical demonstration only. No real personal, commercial, or sensitive data is included.

---

## Author

**Carmen Wong**  

---
