---
title: "Analysis of potential features"
date: 2020-12-17
published: true
tags: [dataviz, hv-chart]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
hv-loader:
  hv-chart-1: ["charts/demodata.html", "900"] # second argument is the height
toc: true
toc_sticky: true
---

This post will show analysis of potential features for parking occupancy prediction.

## Street tree

The parking pattern in space can been seen in the interactive map below.

![An interactive map of street trees in SF]({{site.url}}{{site.baseurl}}/assets/images/hvplot-street-tree.png)

## Demographics

The demographic pattern in space can been seen in the choropleth map below.

<div id="hv-chart-1"></div>


## 311 Requests

The distribution of 311 requests can been seen in the map below.

![A map of 311 requests in SF]({{site.url}}{{site.baseurl}}/assets/images/311hexmap.png)