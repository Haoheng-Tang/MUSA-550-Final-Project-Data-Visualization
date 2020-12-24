---
title: "Example: Embedding Folium chartsss"
date: 2019-04-13
published: true
tags: [dataviz, folium]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
folium-loader:
  hvplot-1: ["parking_map.html", "500"] # second argument is the height
  hvplot-2: ["heatmapByHour.html", "300"] # second argument is the height
  hvplot-3: ["heatmapByWeekday.html", "300"] # second argument is the height
toc: true
toc_sticky: true
---

This post will show analysis of parking pattern (San Francisco) in space and time. 

## Analysis in space

The parking pattern in space can been seen in the interactive map below.

<div id="hvplot-1"></div>

## Analysis in time
The parking pattern in time can been seen in the heatmap below.

<div id="hvplot-2"></div>

This shows the parking occupancy by hour of a sample in San Francisco.

<div id="hvplot-2"></div>

This shows the parking occupancy by weekday of a sample in San Francisco.
