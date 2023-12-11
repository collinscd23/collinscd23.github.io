---
layout: post
title:  "NBA EDA Analysis"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
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

![Histogram of Minutes Played](/assets/images/Minsplayedgraph.png)

The histogram reveals how different players are utilized in terms of playing time during crucial playoff games, highlighting the reliance on key players.


### 3. **Mean of Playoff VS Reg. Season for mins played for the middle portion of Players**
We can see that as the season comes to playoff season the rotation of players tightens. The more productive players will get more time and the less productive will see less MINS
![Histogram of Playoff vs Reg](/assets/images/Playoffsvsreg.png)
## Conclusion



---

