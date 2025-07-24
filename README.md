# Cleaning-data-and-the-skies
🌿 Ozone Pollution Analysis Across California

Author: Bushra
Tools Used: Python, Pandas, Matplotlib, Seaborn, Folium

---
📌 Project Overview

As a data analyst in an environmental context, I tackled daily ozone measurement data from the U.S. Environmental Protection Agency (EPA) across California monitoring stations. The dataset required substantial cleaning before insights could be drawn. My goal: uncover geographic and temporal ozone trends, highlight high-risk areas, and explore urban pollution dynamics.

---

🔧 Data Cleaning & Validation

• Removed null entries from critical fields: `Daily Max 8-hour Ozone Concentration`, `Site Latitude`, `Site Longitude`.
• Converted date formats and extracted `weekday` labels to analyze urban activity.
• Handled outliers using IQR filtering and validated ozone units.
• Deduplicated observations based on `Site ID`, `Date`, and `POC`.

---

📈 Exploratory Analysis

• Temporal trends: Aggregated ozone levels across time. Weekday vs. weekend behavior revealed subtle urban impact—weekday concentrations slightly elevated.
• Regional mapping: Pivoted latitude and longitude to visualize spatial differences. Identified consistent high-concentration zones in southern California.
• Method discrepancy: Compared `Method Code` outputs to assess instrumentation bias.


---

🌍 Geospatial Heatmap

Using Matplotlib and Folium:

• Created a matrix-based heatmap from average ozone concentrations pivoted by site coordinates.
• Built an interactive Folium map highlighting sites reporting > 0.04 ppm—visually flagging regions of concern.
• Plotted with color gradients to reflect intensity, revealing geographical clusters.


---

📊 Key Insights

• Certain stations consistently reported high ozone levels across multiple days.
• Weekday pollution patterns suggest urban activity plays a role.
• Southern regions showed multiple hotspots requiring further air quality management.


---

🔗 Resources

• 📁 GitHub Repository: 
• 🧪 DataCamp Competition Summary: 


---

Let me know if you want help refining the visual layout or crafting a matching LinkedIn caption with hashtags! This is a standout project for your portfolio—sharp, analytical, and backed by environmental impact. 💼🌟


