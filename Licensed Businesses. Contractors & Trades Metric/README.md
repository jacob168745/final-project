📊 Economic Stability & Services — Individual Analysis

Dataset Used:
Licensed Businesses, Contractors & Trades — Western Pennsylvania Regional Data Center (WPRDC)
Link: https://data.wprdc.org/dataset/licensed-businesses-contractors-trades

Author: Chase Marsalko
Sub-Metric: Economic Stability & Services
Final Metric Name: Stability Score

🧠 Purpose

This analysis measures how economically stable and service-supported each Pittsburgh neighborhood is.
The logic: neighborhoods with long-standing businesses and a healthy number of them offer more reliable services and contribute to long-term community strength.

This score will later be combined with group-member metrics for Parking Activity & Community Engagement to determine the Best Neighborhood in Pittsburgh.

🔍 Method Overview
✅ Steps Completed in Notebook
Step	What Was Done
1️⃣	Loaded and cleaned business license data
2️⃣	Parsed zip codes from business address text
3️⃣	Mapped ZIP → Neighborhood
4️⃣	Calculated years active using license dates
5️⃣	Removed duplicates to ensure one record per unique business
6️⃣	Grouped by neighborhood and aggregated metrics
7️⃣	Scored neighborhoods using a weighted Stability Score
8️⃣	Visualized rankings using bar charts
📐 Stability Score Formula

For each neighborhood, we compute:

Component	Description	Weight
Business Longevity	Average years active of businesses	0.60
Business Count	Total number of active businesses	0.40

Both components are normalized (0–1 range) before weighting:

Stability Score = (0.6 × Longevity_norm) + (0.4 × BusinessCount_norm)


✅ Trade diversity may also be added later if NAICS categories are merged into the dataset.

🏆 Findings (Example Preview)

Neighborhoods are ranked based on overall Stability Score.
Visual output (bar chart) highlights leaders → more reliable economic environment.

Example:
✅ Regent Square, Oakland, and Downtown scored highly due to strong longevity + service density.
