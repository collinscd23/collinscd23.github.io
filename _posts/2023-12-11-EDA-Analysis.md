---
layout: post
title:  "Post Name"
author: Your name
description: Short yet informative description
image: /assets/images/blog-image.jpg
---
# In-Depth Analysis of NBA Player Data Using Advanced Visualizations

In this blog, we dive into an intricate analysis of NBA player statistics, leveraging advanced visualizations to extract meaningful insights. The analysis is grounded in the `NBA Data Analysis.ipynb` notebook, where we have used Plotly for our visualizations.

## Data Preparation

The dataset includes comprehensive player statistics, and we have performed a series of data manipulation steps to prepare it for analysis. Here's an overview of our approach:

- Data is grouped by players and years.
- Statistical columns are normalized by minutes played.
- Additional metrics such as FG%, 3PT%, FT%, and True Shooting Percentage (TRU%) are calculated.

## Visualization and Insights

### 1. **Correlation Heatmap**

We have created a correlation heatmap to understand the relationships between different statistics:

![Correlation Heatmap](/assets/images/heatmap.png)

This heatmap offers insights into how various stats like points, assists, and rebounds are interrelated. For instance, a high correlation between assists and points suggests playmakers also contribute significantly to scoring.

### 2. **Histogram of Minutes Played**

A histogram of minutes played in the playoffs is used to understand player utilization:

![Histogram of Minutes Played](/assets/images/Mins played graph.png)

The histogram reveals how different players are utilized in terms of playing time during crucial playoff games, highlighting the reliance on key players.

## Conclusion

This analysis, enriched with advanced visualizations, provides a deeper understanding of NBA player performances. It underlines the importance of statistical correlations and player utilization patterns in strategizing for games.

---

**Note**: Replace the `/path/to/...` with the actual paths or URLs where the images from the Jupyter notebook are hosted.
