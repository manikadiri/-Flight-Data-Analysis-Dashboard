# ✈️ Flight Data Analysis Dashboard

The **Flight Data Analysis Dashboard** is an interactive Power BI dashboard designed to analyze flight operations, airline performance, delays, airport activity, and route performance.

It enables users to explore large-scale flight data through interactive KPIs, charts, slicers, and cross-page filtering. The dashboard helps identify delay patterns, cancellation trends, high-performing airlines, busy airports, and frequently used flight routes.

---

## 📊 Dashboard Overview

The dashboard consists of **5 interactive pages**:

1. ✈️ Flight Overview
2. 🏢 Airline Performance
3. ⏱️ Delay Analysis
4. 🛫 Airport Performance
5. 🗺️ Route Performance

All pages are connected through interactive slicers and filters, allowing users to analyze flight data dynamically.

---

## 🚀 Key Insights

### ✈️ Overall Flight Performance

The Flight Overview page provides a high-level summary of flight operations.

Key KPIs include:

- Total Flights
- Delayed Flights
- Delayed Flight Percentage
- Cancelled Flights
- Completed Flights
- Diverted Flights

These KPIs provide a quick understanding of overall airline and flight performance.

---

## 📈 Visual Components

### 1. ✈️ Flight Overview

The Flight Overview page provides an overall summary of flight operations.

Visualizations include:

- Total Flights KPI
- Delayed Flights KPI
- Cancelled Flights KPI
- Flight Status Distribution
- Total Flights by Day of Week
- Total Flights by Month
- Top Flight Routes
- Interactive Filter Panel

Users can analyze flight activity based on:

- Date
- Airline
- Origin
- Destination
- Route
- Location

---

### 2. 🏢 Airline Performance

The Airline Performance page compares different airlines based on their operational performance.

Key analysis includes:

- Total Flights by Airline
- Average Departure Delay
- Average Arrival Delay
- Delay Percentage
- Cancelled Flights
- Diverted Flights
- Airline-wise Flight Performance

This page helps identify airlines with higher flight volumes and better or weaker operational performance.

---

### 3. ⏱️ Delay Analysis

The Delay Analysis page focuses on understanding flight delays and their major causes.

Key analysis includes:

- Departure Delay
- Arrival Delay
- Average Delay
- Severe Delays
- Delay Categories
- Delay Causes
- Airline-wise Delay Comparison
- Delay Trends

Major delay causes analyzed include:

- Carrier Delay
- Weather Delay
- NAS Delay
- Security Delay
- Late Aircraft Delay

This helps identify the major factors responsible for flight delays.

---

### 4. 🛫 Airport Performance

The Airport Performance page analyzes flight activity across different airports.

Key analysis includes:

- Top Origin Airports
- Top Destination Airports
- Airport Flight Volume
- Average Departure Delay
- Average Arrival Delay
- Airport-wise Performance
- Origin and Destination Analysis

This page helps identify the busiest airports and understand their operational performance.

---

### 5. 🗺️ Route Performance

The Route Performance page analyzes flight routes between origin and destination airports.

Key analysis includes:

- Top Flight Routes
- Total Flights by Route
- Average Delay by Route
- Route-wise Flight Performance
- Most Frequent Origin-Destination Pairs
- Route Delay Analysis

This helps identify high-volume routes and routes experiencing significant delays.

---

## 🎛️ Interactive Filter Panel

The dashboard contains a centralized filter panel that allows users to dynamically analyze the data.

Available filters include:

- 📅 Date
- 🏢 Airline
- 🛫 Origin
- 🛬 Destination
- 🗺️ Route
- 📍 Place

The slicers are synchronized across the dashboard pages so that selections can be used for cross-page analysis.

---

## 🧠 Data Analysis & Feature Engineering

The flight dataset was processed and transformed before creating the Power BI dashboard.

Important derived columns include:

- `dep_hour`
- `arr_hour`
- `is_delayed`
- `is_severe_delay`
- `delay_minutes`
- `distance_category`
- `flight_duration_category`
- `main_delay_cause`
- `flight_status`
- `route`

Flight status was categorized into:

- Completed
- Cancelled
- Diverted

---

## 📋 Dataset

The dashboard is based on the **Flight Data 2024 CSV Dataset**.

