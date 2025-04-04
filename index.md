---
layout: default
title: HW5 Visualization
---

# Homework 5: Bigfoot Sightings Visualized

## 📊 Plot 1: Bigfoot Sightings Per Year

This bar chart shows the number of Bigfoot sightings reported each year. The x-axis represents years and the y-axis represents counts. Tooltips allow readers to hover over bars for more detail.

I used ordinal encoding for `year`, and quantitative encoding for the count. No colormap was needed. The data was grouped by year using `groupby()` and `.size()`.

"This plot is similar to Homework 5's bar chart, but I changed the dataset and used Altair instead of Streamlit."

---

## 🗺️ Plot 2: Interactive Map of Sightings

This map plots all sightings by coordinates. Each point is colored by `state`. A legend-based filter lets users highlight specific states, improving geographic clarity. Tooltip reveals the report's location and date.

I dropped missing latitude/longitude data. I used `selection_point` + `add_params` to implement interactivity (Altair 5). 

"This plot is new. Homework 5 did not use this interaction or this map style."

---

## 🔁 Interactivity Discussion

The map uses an interactive legend to filter by state. This improves clarity and helps users analyze regional patterns without visual clutter.

---

### 🔗 Resources

[📁 The Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/bfro_reports_fall2022.csv)  
[📓 The Notebook](https://github.com/atharvasathaye/hw5-jekyll/blob/main/hw5_notebook.ipynb)

---

## 📈 Visualizations

<iframe src="assets/plot1.html" width="700"
