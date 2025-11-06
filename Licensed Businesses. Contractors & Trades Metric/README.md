# 📈 Economic Stability Metric — Licensed Businesses in Pittsburgh

### Contributor: **Chase Marsalko**
Email: cbm58@pitt.edu
Course: CMPINF 0010 — Best Neighborhood in Pittsburgh  
Dataset: *Licensed Businesses, Contractors & Trades*

---

## 🎯 Goal of My Sub-Metric

My metric evaluates the **economic stability and service availability** in Pittsburgh neighborhoods using licensed business data from the WPRDC.

## 📌 Summary

Analyzing business longevity and local service density across Pittsburgh neighborhoods to assess economic stability and contribution to overall livability.

---

## 📊 Dataset Used

**Licensed Businesses, Contractors & Trades — WPRDC**  
🔗 https://data.wprdc.org/dataset/business-contractors-trades

---

## 🧩 Sub-Metric Description — Economic Stability

This sub-metric measures the strength and reliability of neighborhood economies using business licensing data from the Western Pennsylvania Regional Data Center (WPRDC).
The goal is to identify areas with consistent business activity and long-term establishments, indicating stable local services and economic health.

Metric Formula

Component	What It Represents	Weight
Average Years Active	Longevity of licensed businesses	0.6
Business Count	Total number of licensed businesses	0.4
Stability Score = (0.6 * Normalized Average Years Active) + 
                  (0.4 * Normalized Business Count)


Higher Stability Scores reflect neighborhoods with strong, long-standing, and diverse business presence.

---

## 🧠 Why This Matters for “Best Neighborhood”

Stable neighborhoods:
- Keep businesses open longer
- Retain jobs locally
- Provide consistent, essential services
- Support long-term residential growth

A neighborhood with strong business stability is **resilient and economically healthy**.

---

## ✅ Outputs in Notebook

My analysis produces:
- Ranking of neighborhoods by Economic Stability Score
- Visualizations showing strongest + weakest business areas
- A contribution to our team’s **overall PLEM score**

---

## 🔧 Analysis Steps

1. Loaded and cleaned business, contractor, and trade license datasets.

2. Extracted ZIP codes and mapped them to Pittsburgh neighborhoods.

3. Parsed license issue and expiration dates to calculate years active.

4. Removed duplicate entries and standardized business names.

5. Aggregated data by neighborhood.

6. Normalized values for average years active and business counts.

7. Calculated the Stability Score for each neighborhood.

8. Visualized results using bar charts to show top neighborhoods by stability.

---

## 📊 Results

The analysis produced a ranked list of neighborhoods by economic stability.
Top-performing neighborhoods showed:

High counts of active, licensed businesses.

Longer average business operation times.

Strong representation across multiple trades and industries.

These neighborhoods demonstrate stronger long-term economic reliability and local engagement.

---

## 🔍 Summary Statement

> **This sub-metric helps identify neighborhoods with reliable services and strong local economies — an important part of determining Pittsburgh’s best neighborhood.**


