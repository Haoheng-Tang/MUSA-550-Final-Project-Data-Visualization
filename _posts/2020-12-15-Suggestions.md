---
title: "Suggestions"
date: 2020-12-15
published: true
tags: [dataviz, hv-chart]
excerpt: "Embedding interactive hvplot charts on static pages using Jekyll."
hv-loader:
  hv-chart-1: ["charts/mobileFoodHeatMap.html", "600"] # second argument is the height
  hv-chart-2: ["charts/parkingHeatMap.html", "600"] # second argument is the height
  hv-chart-3: ["charts/mobileFoodStartTime.html", "600"] # second argument is the height
  hv-chart-4: ["charts/mobileFoodEndTime.html", "600"] # second argument is the height
toc: true
toc_sticky: true
---

Based on the analysis and algorithm above, suggestions will be given. The model will have both private and public use cases. To individuals, the model predict the possible parking occupancy in the future, so that they can find somewhere easy to park in advanced. To government, the model predict possible vacancy rate or parking in the future, so that they can make use of the vacant parking spaces, changing them into green spaces or take advantage of them through time sharing ways. Mobile food data will be used for analysis. Mobile food service, most of which uses cars to sell food, is strongly related to parking lots because parking lots provide spaces for cars. Those mobile food service can take advantage of the vacant parking spaces at specific time a day.

## Spatial analysis

The mobile food services map

<div id="hv-chart-1"></div>

Parking occupancy map

<div id="hv-chart-2"></div>

At first glance, parts of the occupied parking spaces overlap with mobile food services.

## Time sharing ways

Mobile food services start time

<div id="hv-chart-3"></div>

Mobile food services end time

<div id="hv-chart-4"></div>

From the figure above, we know that most mobile food start from 9 or 10 o’clock and end at 10 or 11 o’clock. Those mobile food services are probably selling food for breakfast. From the parking occupancy analysis in time, we see that the occupancy will not rise until 9:00 am. Since the distribution of mobile food supply is close to the distribution of parking spaces (not vacant), the mobile food service can use the parking spaces to sell breakfast for those who will be arriving at the parking lot until 9:00 or 10:00, especially on Sunday, Monday, Thursday and Friday. In this way, we can make full use of the vacant parking spaces while providing cheap and close-to-customers area for mobile food supply services.