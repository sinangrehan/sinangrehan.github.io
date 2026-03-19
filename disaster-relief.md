---
layout: post
title: Data Visualizations From Senior Thesis
---

For my undergraduate senior thesis, I studied the effect of federal disaster relief administered by FEMA on income inequality. Using a partial adjustment regression (AR1 model), I found that FEMA aid exacerbated income inequality. Below are some exploratory visualizations of the dataset I built. In the future I will include a section on my analysis. 

<iframe 
  src="/assets/disaster_relief_viz.html" 
  width="100%" 
  height="800px" 
  frameborder="0">
</iframe>

This scatterplot explores the relationship between federal disaster relief and income inequality across U.S. states from 2006 to 2019. Each bubble represents a state in a given year, sized by population and colored by Census region. The x-axis shows total FEMA aid received (on a log scale, not inflation adjusted), while the y-axis shows the year-on-year change in the Gini coefficient — a standard measure of income inequality, where higher values (up to 1) indicate greater inequality, while lower values (down to 0) indicate less inequality. A positive y-value indicates that income inequality increased relative to the prior year after FEMA aid was administered. Some states experience hurricanes regularly, so they tend to regularly receive aid (e.g. Florida, Texas, New York). Some states are prone to intermittent disasters, such as California (which experiences wilfires). Use the slider to explore how this relationship evolved over time.

<iframe 
  src="/assets/disaster_relief_lines.html" 
  width="100%" 
  height="700px" 
  frameborder="0">
</iframe>

These charts show the trajectories of Gini coefficient and total FEMA aid by state over the full 15-year period. Highlighted states are those that received the most federal disaster aid over the study period — including Louisiana, Texas, Florida, and California. The grey lines represent all other states. Notable spikes in FEMA aid correspond to major disaster events: Hurricane Katrina in 2005, Hurricane Sandy in 2012, and Hurricane Harvey in 2017.
