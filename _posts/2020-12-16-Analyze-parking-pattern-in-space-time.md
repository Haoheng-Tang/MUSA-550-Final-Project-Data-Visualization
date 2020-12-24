---
title: "Analysis of parking pattern in space and time"
date: 2019-04-13
published: true
tags: [dataviz, hv-chart]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
hv-loader:
  hv-chart-1: ["charts/parking_map.html", "500"] # second argument is the height
  hv-chart-2: ["charts/heatmapByHour.html", "300"] # second argument is the height
  hv-chart-3: ["charts/heatmapByWeekday.html", "300"] # second argument is the height
toc: true
toc_sticky: true
---

This post will show analysis of parking pattern (San Francisco) in space and time. 

## Analysis in space

The parking pattern in space can been seen in the interactive map below.

<div id="hv-chart-1"></div>

## Analysis in time
The parking pattern in time can been seen in the heatmap below.

<div id="hv-chart-2"></div>

This shows the parking occupancy by hour of a sample in San Francisco.

<div id="hv-chart-3"></div>

This shows the parking occupancy by weekday of a sample in San Francisco.
