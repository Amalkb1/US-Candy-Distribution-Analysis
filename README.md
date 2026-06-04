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

## 👨‍💻 Author

Amal K B

Aspiring Data Analyst | Business Analyst | Supply Chain Analytics Enthusiast
