# 📈 Activity Metric - Aggregated Parking Transactions

### Contributor: **Jacob Lee**
Email:jjl168@pitt.edu
Course: CMPINF 0010 — Best Neighborhood in Pittsburgh 
Dataset: *Aggregated Parking Transactions*

---

## 🎯 Goal of my Sub-Metric

My sub-metric evaluates the **daily activity** and **neighborhood vibrancy** in Pittsburgh neighborhoods using parking and meter data from the WPRDC.

## 📌 Summary 

Evaluating parking activity and meter utilization across Pittsburgh neighborhoods to assess daily neighborhood vibrancy and their contribution to overall livability.

---

## 📊 Datasets Used

**Aggregated Parking Transactions — WPRDC**
🔗 https://data.wprdc.org/dataset/parking-transactions

---

## 🧩 Sub-Metric Description - Activity

This sub-metric measures the level of daily activity and human presence in Pittsburgh neighborhoods using parking and meter data from the Western Pennsylvania Regional Data Center (WPRDC).
The goal is to identify areas with consistent parking usage and high turnover, indicating vibrant neighborhoods and active local services.

Metric Formula

Component                        What it Represents                        Weight
Average Transactions Per Meter   Frequency of parking usage                0.5
Turnover Rate                    Distinct transactions per meter per day   0.3
Peak-Hour Utilization            Maximum occupancy during peak             0.2
Daily vibrancy score = (0.5* Normalized Average transactions) + (0.3 * Normalized Turnover Rate) + (0.2 * Normalized Peak-Hour Utilization)


Higher scores show active and vibrant neighborhoods with strong daily activity.

---

## 🧠 Why This Matters for “Best Neighborhood”

Stable neighborhoods:
- Attract steady daily visitors and activity.
- Support local shops, restaurants, and services.
- Encourage walkability and community engagement.
- Reflect strong economic and social energy.

A neighborhood with high daily vibrancy is **active, accessible, and full of life**.

---

## ✅ Outputs in Notebook

My analysis produces:
- Ranking of neighborhoods by Daily Vibrancy Score
- Visualizations showing areas with the highest and lowest parking activity
- A contribution to our team’s **overall PLEM score**, representing daily neighborhood liveliness and accessibility

---

## 🔧 Analysis Steps

1. Loaded and cleaned Parking Transactions and Metered Parking Inventory, 

2. Linked meters and transactions to Pittsburgh neighborhoods using location or zone data.

3. Calculated daily transactions per meter and turnover rates for each neighborhood.

4. Identified peak-hour usage patterns to capture activity intensity.

5. Aggregated parking metrics at the neighborhood level.

6. Normalized all components (transactions, turnover, peak-hour utilization).

7. Computed the Daily Vibrancy Score using weighted components.

8. Visualized results to highlight neighborhoods with the highest and lowest daily activity.

---

## 📊 Results

The analysis produced a ranked list of neighborhoods by Daily Vibrancy Score.
Top-performing neighborhoods showed:

High levels of parking activity and meter turnover

Strong daytime and evening utilization patterns

Consistent visitor circulation and accessibility

---

## 🔍 Summary Statement

> **This sub-metric helps identify neighborhoods with high daily activity, accessibility, and social energy — key indicators of a vibrant and livable Pittsburgh neighborhood.**
