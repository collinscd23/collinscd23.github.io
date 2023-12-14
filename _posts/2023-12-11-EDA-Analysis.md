---
layout: post
title:  "NBA EDA Analysis"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/blog-image.jpg
---
# In-Depth NBA Player Statistics Analysis

In this analysis, I delve into the intricacies of NBA player performance through a series of visualizations. Each graph tells a unique story about the players and games across several seasons. Here's what I've discovered:

# How has the game changed over the past years?
## FG3A (Three pointer Attempts Per 48 mins from 2012 to 2021)
![FG3A per 48 mins](/assets/images/FG3A_48.png)
*Figure 1: FG3A per Min Trend Chart*
This graph shows us the average number of 3 point attempts made each year by the top 100 players per 48 mins. One of the first things I noticed from the data was the increased number of 3 point attempts taken. With almost 15 more 3 pointers taken per 48 mins. This shows a very big change in the game of basketball. With the rise of stars like Stephen Curry, Damian Lillard and others playing a very deep shooting play style as increased dramaticlly since 2012. As we will see in the next graph that the 3 pointer isnt the only thing that has changed.
## Number of Possesions (Number of Possessions per 48 mins from 2012 to 2021)
![Number of POSS per 48 mins](/assets/images/POSS_48.png)

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

