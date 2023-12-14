---
layout: post
title:  "NBA EDA Analysis"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/blog-image.jpg
---
# In-Depth NBA Player Statistics Analysis

In this analysis, I delve into the intricacies of NBA player performance through a series of visualizations. Each graph tells a unique story about the players and games across several seasons. Here's what I've discovered:

## Multiple Lines Trend Chart Analysis

![Multiple Lines Trend Chart](assets/images/100df.png)
*Figure 1: Multiple Lines Trend Chart*

In Figure 1, I'm looking at a trend chart that tracks various basketball statistics over the years. The stability of the possession estimates (`POSS_est`) at the top suggests that team possessions have been consistent, which is crucial for evaluating performance. The lines for Field Goals Made (`FGM`) and Field Goal Attempts (`FGA`) indicate a steady shooting performance. Minor variations could reflect changes in strategies or roles within the team.

## Points Scored Trend Chart Analysis

![Points Scored Trend Chart](/assets/images/40df.png)
*Figure 2: Points Scored Trend Chart*

In Figure 2, I notice that the Points Scored (`PTS`) metric stands alone, which likely means it's influenced by several factors like `FGM` and `FGA`. The consistency across the chart demonstrates that players' roles and contributions have been steady over the seasons, despite the dynamic nature of basketball.

## Free Throw Percentage vs Play Time Scatter Plot Analysis

![Free Throw Percentage vs Play Time Scatter Plot](path-to-your-image-free-throw.png)
*Figure 3: Free Throw Percentage vs Play Time Scatter Plot*

In the scatter plot of Figure 3, there is a dense cluster of data points between 75% to 90% free-throw efficiency, showing that most players shoot within this range, regardless of their minutes played. This suggests that free throw skill may not necessarily improve with more playtime.

## Correlation Heatmap Analysis

![Correlation Heatmap](/assets/images/heatmap.png)
*Figure 4: Correlation Heatmap*

The heatmap in Figure 4 reveals how different stats interact. For example, the correlation between Points Scored (`PTS`) and Field Goals Made (`FGM`) is intuitive – more points usually come from making more baskets. This visualization helps me understand the relationships between various aspects of the game.

## Histogram of Minutes Played in Playoffs Analysis

![Histogram of Minutes Played in Playoffs](path-to-your-image-mins-played-graph.png)
*Figure 5: Histogram of Minutes Played by Players in Playoffs*

Lastly, the histogram in Figure 5 shows the distribution of minutes played during the playoffs. The steep decline after the initial peak suggests a reliance on key players who log the most minutes. This insight is pivotal when considering player fatigue and performance in crucial games.

Through each figure, I gain valuable insights into player performance, team dynamics, and the strategic elements that play into the beautiful game of basketball. Should a deeper dive be required, I can refer to the raw data and statistical analysis within the code and CSV files for more context.




---

