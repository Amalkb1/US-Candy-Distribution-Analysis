# 🍬 US Candy Distribution Analysis Dashboard

## 📌 Project Overview

This project analyzes the sales, profitability, factory performance, geographic distribution, and shipping efficiency of a US national candy distributor.

The objective is to identify:

* Most profitable product lines
* Best performing factories
* Customer geographic distribution
* Factory-to-customer shipping efficiency
* Opportunities for factory optimization
* Target vs Actual performance

The project was developed using:

* Python (Google Colab)
* Pandas
* Geospatial Analysis
* Power BI
* DAX

---

## 🎯 Business Problem

A national candy distributor operates multiple factories across the United States and serves customers nationwide.

Management wants to answer:

* Which factories generate the highest profit?
* Which product lines generate the best margins?
* Which customer regions generate the highest demand?
* Which shipping routes are inefficient?
* Can products be reassigned to different factories to reduce transportation distance?
* Are sales targets being achieved?

---

## 🗂 Dataset

The dataset contains:

### Sales Table

* Order Information
* Customer Information
* Product Information
* Sales
* Cost
* Gross Profit

### Factory Table

* Factory Name
* Latitude
* Longitude

### Product Table

* Product Division
* Product Cost
* Product Selling Price

### US ZIP Table

* Geographic Coordinates
* State
* City
* Population

### Target Table

* Sales Targets by Division

---

## 🧹 Data Cleaning & Preparation

Performed using Python in Google Colab.

### Key Steps

* Missing value validation
* Data type conversion
* Date formatting
* Shipping day calculation
* Customer geolocation integration
* Factory geolocation integration
* Distance calculation using Haversine Formula
* Route efficiency calculations

### Calculated Metrics

Shipping Days

Distance KM

Efficiency (Sales/KM)

Efficiency (Profit/KM)

Profit Margin %

---

## 📊 Dashboard Pages

### 1. Executive Overview Dashboard

Provides:

* Total Sales
* Total Profit
* Profit Margin
* Total Orders
* Sales Trend
* Factory Profit Contribution

---

### 2. Geographic Dashboard

Provides:

* Customer Distribution by City
* Order Distribution by State
* Route Analysis
* Geographic Demand Patterns

---

### 3. Product Dashboard

Provides:

* Product Margin Analysis
* Product Performance
* Division Analysis
* Top Margin Products

---

### 4. Factory Dashboard

Provides:

* Factory Profitability
* Factory Efficiency
* Average Shipping Distance
* Factory Contribution Analysis

---

### 5. Target Dashboard

Provides:

* Target vs Actual Performance
* Division Comparison
* Profit Contribution Tree Analysis

---

## 🚚 Factory Optimization Analysis

A factory optimization model was developed to identify products that could be reassigned to different factories.

Methodology:

* Calculate average shipping distance for each product
* Identify nearest available factory
* Compare current average distance vs optimized distance
* Estimate potential transportation savings

---

## 🛠 Technologies Used

Python

Pandas

NumPy

Google Colab

Power BI

DAX

Power Query

Geospatial Analytics

---

## 📈 Key Outcomes

* Identified high-profit factories
* Measured route efficiency
* Evaluated product profitability
* Identified shipping optimization opportunities
* Compared performance against targets
* Developed executive-level business dashboards

---

Business Insights From Your Dashboard
Executive Overview
Revenue & Profitability
Total Sales reached approximately $1.45 Billion
Total Gross Profit exceeded $1 Billion
Overall Profit Margin is approximately 65.9%

This indicates a highly profitable distribution network with strong margins across product lines.

Factory Performance
Best Performing Factory

Lot's O' Nuts

Generates approximately 56% of total factory profit
Gross Profit ≈ $52.8K

This factory is the primary profit driver of the business.

Second Best Factory

Wicked Choccy's

Contributes approximately 40% of total profit
Gross Profit ≈ $36K

Together, these two factories generate more than 95% of total profits.

Underperforming Factories
Sugar Shack
Secret Factory
The Other Factory

These factories contribute very little profit compared to the top two locations.

Product Analysis
Strong Product Portfolio

The dashboard shows consistently high margins across products.

Average Margin:

65.91%

This suggests pricing strategy and production costs are well controlled.

Top Performing Products

The Wonka product family dominates profitability and margin contribution.

Recommendation:

Increase marketing efforts around Wonka products
Expand distribution in high-demand regions
Geographic Analysis
Highest Customer Concentration

Top cities include:

New York City
Los Angeles
Philadelphia
San Francisco
Seattle

These cities represent the largest customer bases.

Geographic Demand

Demand is concentrated in major metropolitan regions.

Recommendation:

Focus inventory placement near major population centers
Strengthen logistics coverage in high-density states
Target Analysis
Target Achievement
Division	Target	Actual
Chocolate	27,000	9,844
Sugar	15,000	40
Other	3,000	310

All divisions are significantly below target.

Key finding:

The business achieved only about 10.2K orders against a target of 45K orders.

Recommendation:

Reevaluate target setting methodology
Increase sales and promotional activities
Investigate demand forecasting assumptions
Shipping Optimization Insights

Based on your Python optimization analysis:

Highest Savings Opportunities
Product	Potential Distance Savings
Nerds	810 KM
Wonka Bar – Fudge Mallows	736 KM
Wonka Bar – Nutty Crunch Surprise	715 KM
Fun Dip	710 KM
Wonka Bar – Scrumdiddlyumptious	679 KM
Key Recommendation

Move production of these products to the suggested nearest factories.

Expected benefits:

Lower transportation costs
Faster delivery times
Reduced fuel consumption
Improved route efficiency
Observation

Most inefficient routes originate from:

Sugar Shack
Lot's O' Nuts

Several products can reduce average shipping distance by 500–800 KM through factory reassignment.

Final Business Recommendation
Continue prioritizing Lot's O' Nuts and Wicked Choccy's as primary production hubs.
Reassign products with high shipping-distance savings potential.
Expand sales efforts in major metropolitan markets.
Review divisional sales targets due to significant underachievement.
Increase investment in high-margin Wonka product lines.
Implement route optimization strategies to reduce logistics costs and improve service levels.

These recommendations directly support profitability growth, logistics optimization, and improved operational efficiency.

## 👨‍💻 Author

Amal K B

Aspiring Data Analyst | Business Analyst | Supply Chain Analytics Enthusiast
