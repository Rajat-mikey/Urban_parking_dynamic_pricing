# Urban_parking_dynamic_pricing
An intelligent, real-time pricing model for 14 parking lots using Python, Bokeh, and demand-based logic. Built as a smart city project to optimize parking with rerouting intelligence and competition-aware pricing.

## Features
- 📈 Linear, demand-based, and competitive pricing models
- 🔁 Real-time rerouting logic
- 🌍 Geo-aware competition handling (Haversine logic)
- 📉 Bokeh dashboard with dropdown-based lot selection

## 🧠 Models
- **Model 1:** Linear pricing based on occupancy
- **Model 2:** Demand-based pricing (occupancy, queue, traffic, vehicle type)
- **Model 3:** Geo-aware competitive adjustment with reroute triggers

## 📁 Files
- `dynamic_pricing.ipynb`: Complete code + explanations
- `final_report.pdf`: Report with assumptions, formulas, visuals
- `data/dataset.csv`: Raw parking data

## 🛠️ Tech Stack
**pandas, Numpy**
**python**
**Google collaboratory**
**pathway**
**bokeh dashboards**

## Architecture Diagram
```mermaid
graph TD
    A[Raw Parking Data] --> B[Data Cleaning & Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Model Training]
    D --> F[Dynamic Pricing Output]


