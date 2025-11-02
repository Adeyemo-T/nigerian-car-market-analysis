## Project Background

The Nigerian automotive market is highly dynamic, characterized by diverse consumer preferences and a mix of imported used and new vehicles. A primary challenge for dealers and logistics firms is the **lack of clear, data-driven insights** into consumer choice, price elasticity, and optimal inventory sourcing.

This project thoroughly analyzes transactional and historical data to identify market trends, segment consumer preferences, and uncover actionable insights to optimize inventory and marketing strategies across major regions in Nigeria.

Insights and recommendations are provided on the following key areas:
* **Pricing & Value Analysis:** Evaluation of the average price, mileage, and horsepower to determine vehicle value perception.
* **Consumer Preference Segmentation:** Analysis of drivers' choices (manual vs. automatic), popular colours, and top vehicle models.
* **Regional Market Share:** Assessment of sales distribution across Nigerian states to guide logistics and targeted marketing.

* **Interactive Dashboard:** The full Market Insights dashboard can be accessed [here](LINK_TO_POWER_BI_DASHBOARD).

 ## Data Structure & Initial Checks

#### Data Overview
The analysis was conducted on a denormalized **Kaggle dataset** compiled from Nigerian car market listings. The raw data consisted of a single **Excel file** containing several thousand records and variables including: **Price, Mileage, Horsepower, Year, Location, and Car Model.**

#### Data Cleaning and Preparation
The entire data cleaning and preparation process was executed using native **Excel functionality** and **Power Query (M Language)** to ensure data integrity and transformation efficiency.

* **Type Conversion & Standardization (Power Query):** Used Power Query to efficiently convert currency and numerical columns (e.g., Price, Mileage) to the correct decimal/numeric format for aggregation and calculation.
* **Aggregation (Pivot Tables):** **Pivot Tables were utilized extensively in Excel** to summarize raw data, calculate key metrics (like average price by model), and perform necessary aggregations before visualization in the dashboard.
* **Missing Value Handling (Excel):** Addressed and investigated missing entries, particularly in geographical and specific model fields, to minimize data loss while preserving accuracy.
* **Feature Engineering:** Created essential features required for the dashboard, such as segmenting the **Nigerian regions** and calculating the **Age of the vehicle** (using the *Year* column) to better reflect market value.
![Image](https://github.com/user-attachments/assets/cc5ba1be-10ea-42ad-b3c5-f2e085a4bd27)

![Image](https://github.com/user-attachments/assets/ddd8b0da-6de7-4b8d-90eb-cf617456c3bd)


## Executive Summary

The Nigerian car market shows a high concentration of value in specific vehicle models and years, with an **average market price of ₦5.0M**. Analysis indicates that consumer preference is heavily weighted toward popular foreign-used brands, suggesting a market focused on durability and price sensitivity over newness. The primary strategic opportunity lies in **optimizing inventory sourcing** to align with the dominant preferences for specific top models and manual transmission options.

#### Overview of Key Market Metrics

The overview highlights the scale and core characteristics of the vehicles in the market data.

![Image](https://github.com/user-attachments/assets/7162e7a9-b8e9-4327-b978-13bd0b2a299c)


#### Consumer Preference Deep Dive

* **Top Models:** The market's inventory is highly concentrated around the **Top Ten most popular models** (e.g., Toyota, Volkswagen), indicating strong brand loyalty.
* **Driver's Choice:** **Manual transmission** cars hold a significant share of the market, a critical preference for inventory sourcing.
* **Colour Preference:** The market shows a high demand for neutral and subdued colours (Black, Silver, White).

![Image](https://github.com/user-attachments/assets/c64491e0-4f91-4e28-9bed-c8c8d61bfff4)


#### Geographic and Sourcing Analysis

* **Source Origin:** The market is predominantly fueled by **Foreign Used** vehicles rather than Nigeria Used or New vehicles.
* **Regional Demand:** The map highlights which regions or states have the highest volume of listings/sales, crucial for logistics and distribution planning.

![Image](https://github.com/user-attachments/assets/aeeafc5b-21a9-47b5-9c82-2840620fcb75)

## Business Recommendations

Based on the uncovered market insights and consumer preferences, the following actions are recommended for dealers, inventory managers, and marketers:

* **Optimize Sourcing for Manual Models:** Given the strong revealed preference for **manual transmission** vehicles, inventory managers should actively prioritize sourcing high-quality, foreign-used models with manual configurations to align inventory with consumer demand and ensure faster turnover.
* **Inventory Concentration Strategy:** Focus purchasing power and resources on the **Top Ten most popular models** (e.g., Toyota, Volkswagen). This strategy capitalizes on proven brand loyalty and high market liquidity, reducing the risk associated with less popular inventory.
* **Targeted Regional Marketing:** Use the **Geographic Analysis** to concentrate marketing spend and physical inventory (showrooms or distribution centers) in the states identified as having the highest sales volume. This improves logistics efficiency and market penetration.
* **Value-Driven Pricing Strategy:** Position marketing and sales messaging to emphasize **vehicle value** (low mileage, high horsepower) rather than just the year of manufacture.
* **Colour and Aesthetics Alignment:** Ensure that the majority of imported inventory aligns with the dominant aesthetic preference for **neutral colors** (Black, Silver, White) to minimize time-on-lot for stock.
