# Uber Ride Price Prediction Dashboard

This project was developed as part of the **Introduction to Big Data Analytics** course at AUCA. It aims to analyze and visualize Uber ride data to identify pricing patterns, trends, and actionable insights.

## 🔍 Project Overview

Uber, as a ride-hailing service, generates large amounts of trip data daily. This project uses Uber ride records to:
- Analyze ride prices
- Understand temporal and geographical trends
- Provide business insights for price optimization

## 🎯 Objectives

- Perform exploratory data analysis on Uber ride data
- Build an interactive Power BI dashboard
- Identify key factors influencing pricing
- Provide actionable recommendations based on data

## 🧰 Tools Used

- Power BI
- Microsoft Excel / Power Query
- GitHub
- Jupyter Notebook (for initial exploration)
- Kaggle dataset (source)

## 🧪 Methodology

### Data Collection
The Uber dataset was sourced from Kaggle and contained ride information such as pickup locations, timestamps, distances, and prices.

### Data Cleaning
Performed using:
- Power Query in Power BI
- Filtering missing values
- Renaming and formatting columns
- Removing duplicates

### Analysis Process
1. Data imported into Power BI
2. Calculated fields created (e.g., price per km)
3. DAX formulas used for:
   - Monthly averages
   - Price trends by distance
   - Fare type filters
4. Visualizations built: bar charts, line graphs, maps, and slicers

## 📊 Power BI Dashboard Highlights

- **Ride Price Trends:** Price changes over time
- **Distance vs. Price:** Correlation between trip length and cost
- **Pickup Heatmap:** Geographic concentration of pickups
- **Ride Type Breakdown:** Price by ride type (UberX, UberPOOL, etc.)

## 📈 Results & Insights

- Price increases during peak hours and weekends
- Longer rides don’t always mean higher prices due to promotions
- Certain areas have consistently higher fares (e.g., airports)
- Seasonal variations affect pricing patterns

## ✅ Recommendations

- Increase driver availability during peak hours
- Offer discounts in high-fare areas to increase ridership
- Improve route optimization for mid-distance trips

## 📂 Project Structure
`cleaned_data/` – Contains cleaned Uber dataset  (Uber Ride Price Prediction)
- `screenshots/` – Documentation images (data loading, cleaning, dashboard)
power.pbix` – Final Power BI Dashboard
- `Final_Report.md` – Project summary and insights



# Uber Ride Price Prediction – Final Report

## 🔹 Introduction
This project aims to analyze Uber ride fare patterns using data from Kaggle. The goal is to identify key trends across time, location, and pricing to uncover business insights that could help improve Uber's operational efficiency and customer satisfaction.

## 🔹 Methodology
We used a cleaned Uber dataset, imported into Power BI for exploratory data analysis and visualization. Data preprocessing was done in Excel and Power Query. Various visualizations were created to show ride frequency, price distribution, and temporal patterns.

## 🔹 Analysis
- **Fare Patterns**: Prices were higher during peak hours and weekends.
- **Time Patterns**: Most rides occurred between 5 PM to 8 PM daily. Monthly spikes were noted during holidays.
- **Ride Duration**: Shorter rides had the most frequent requests, but longer ones generated higher fares.
- **Distribution**: Box plots showed extreme outliers in pricing.
- **Temporal Trends**: Usage increases during colder seasons, possibly due to reduced walking/travel comfort.
- **Geography**: (Add map insight if available)

## 🔹 Results
- Peak periods were evenings and weekends.
- Prices fluctuated based on time of day and possibly season.
- Weekdays had more consistent pricing.
- Holidays saw a rise in both ride count and fare prices.

## 🔹 Conclusion
The Uber ride data revealed clear trends in consumer behavior and fare pricing. Visual analytics confirmed that demand is time-sensitive, and pricing strategies could be optimized accordingly.

## 🔹 Recommendations
- Implement **dynamic pricing** during peak hours and seasons.
- Offer discounts during low-demand periods.
- Use **heatmaps** to allocate cars more efficiently.
- Integrate **weather data** in future analysis for fare adjustments.

