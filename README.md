# ✈️ Airport Traffic Analysis Using SQL

## 📌 Project Overview

This SQL project analyzes airport traffic data to uncover passenger movement patterns, route popularity, flight frequency, seat utilization, and the relationship between city population and airport traffic.

The goal is to answer real-world aviation business questions using SQL queries and data analysis techniques.

---

## 📊 Dataset Information

The dataset contains airport and airline traffic information, including:

- Origin Airport
- Destination Airport
- Origin City
- Destination City
- Airline ID
- Passenger Count
- Flight Information

Additional city population data was used for demographic analysis.

---

## 🎯 Business Questions Solved

### 1. Analyze Passenger Traffic by Route
- Identified the busiest routes based on total passenger volume.
- Found the least busy routes with active passenger traffic.

### 2. Average Passengers per Flight
- Calculated average passengers for each route.
- Measured average passenger traffic handled by airports.

### 3. Flight Frequency Analysis
- Determined routes with the highest number of flights.
- Identified major high-traffic corridors.

### 4. Seat Utilization Analysis
- Estimated seat capacity for airlines.
- Calculated average seat utilization percentages.

### 5. Popular Destination Airports
- Ranked destination airports by inbound passenger traffic.

### 6. Population vs Passenger Traffic
- Examined whether larger city populations correlate with higher airport traffic.

---

## 🛠️ SQL Concepts Used

- Common Table Expressions (CTEs)
- Aggregate Functions
  - SUM()
  - AVG()
  - COUNT()
  - MAX()
- GROUP BY
- ORDER BY
- HAVING
- JOINs
- UNION
- String Functions
- Data Filtering

---

## 📈 Key Insights

### Busiest Routes
Some of the highest passenger traffic routes include:

- Miami, FL → New York, NY
- New York, NY → Miami, FL
- Orlando, FL → New York, NY
- New York, NY → Orlando, FL
- New York, NY → Chicago, IL

### Flight Activity
Major metropolitan areas dominate both passenger traffic and flight frequency.

### Airport Performance
Certain airports serve as major hubs with significantly higher passenger movement.

### Seat Utilization
Airline efficiency was evaluated by comparing passenger counts against estimated seating capacity.

### Population Impact
Cities with larger populations generally showed higher airport passenger traffic, indicating a positive relationship between population size and air travel demand.

---

## 📂 Project Structure
