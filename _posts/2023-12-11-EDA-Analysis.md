---
layout: post
title:  "NBA EDA Analysis"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/hoop.png
---
# In-Depth NBA Player Statistics Analysis

In this analysis, we explore the nuances of NBA player performance through various visualizations, each telling a unique story about the players and games over several seasons. Here are the key insights:

# How has the game changed over the past years?
## FG3A (Three pointer Attempts Per 48 mins)
![FG3A per 48 mins](/assets/images/FG3A_48.png)

This graph illustrates the average number of three-point attempts made each year by the top 100 players per 48 mins. A significant increase in three-point attempts is evident, rising by nearly 15 per 48 mins. This shift reflects a notable change in basketball's dynamics, especially with the emergence of sharpshooters like Stephen Curry and Damian Lillard, who popularized a deep-shooting play style since 2012. The following graph further demonstrates that the three-pointer isn't the only aspect that has evolved.


## Number of Possesions (Number of Possessions per 48 mins)
![Number of POSS per 48 mins](/assets/images/POSS_48.png)
We observe a positive trend in the number of possessions over recent years. This increase suggests a faster game pace, implying more shooting, rebounding, turnovers, or steals. It's particularly interesting to note that top players now utilize a larger portion of possessions for three-point shooting, among other strategies.


## FG3A (Three pointer Attempts Per 100 Possesions)
![Number of FG3A per 100 POSS](/assets/images/FG3A_100.png)

To conclude this section, let's examine how three-point attempts have evolved per 100 possessions. This graph offers a deeper understanding of the evolving offensive strategies in the NBA, particularly focusing on three-pointer attempts per 100 possessions. The data indicates a consistent upward trend, reflecting a strategic shift towards prioritizing three-point shots. This change is not just a result of individual players' skills but also a broader adaptation in team tactics, embracing the three-pointer as a crucial element of modern basketball. This evolution signifies how analytics and player proficiency have jointly propelled the game into a new era, where long-range shooting is no longer an exception but a norm.

# What player stats are correlated with each other from the Data set collected? 
## Correlation Heatmap Analysis

![Correlation Heatmap](/assets/images/heatmap.png)


The heatmap showcases interactions between different stats. For instance, the correlation between Points Scored ('PTS') and Field Goals Made ('FGM') is strong, as more points typically result from making more baskets. This visualization aids in understanding the relationships among various game aspects. 

![Zoom on Heatmap](/assets/images/newplot.png)
An intriguing observation is the moderate correlation between Assists ('AST') and Steals ('STL'). This might indicate that players who steal the ball often pass it to a teammate for a score. However, the correlation between Steals ('STL') and Points Scored ('PTS') is not as significant, suggesting that players who steal the ball are less likely to score themselves, highlighting a distinct playstyle.

# What does the distribution of “Minutes Played per game in RS VS Playoffs” thoughtout the TOP 100 players from 2012 to 2021 look like? AND what can we learn.
## Mins played Chart Analysis
![Mins PLayed RS vs Playoff from 2012 to 2012](/assets/images/Playoffsvsreg.png)
With some further investigation we can see that during the regular season the amount of time is pretty normally distributed betweeen the 48 mins in an game. With the higher profile players playing more minutes and the bench players playing less. We can see the center of the data crash, and both endeds are increased. The better players are getting more time playing and the others are getting less. This makes sense because in the playoffs the teams are more focused on winning and not worried about keeping there stars in as healthy because they want to win. AS for the regular season its okay to give the other players more time since the games dont matter as much. 

## Histogram of Minutes Played in Playoffs Analysis
![Histogram of Minutes Played in Playoffs](/assets/images/Minsplayedgraph.png)

Here is a further look into the time played in the playoffs. 
Lastly, the histogram  shows the distribution of minutes played during the playoffs. The steep decline after the initial peak suggests a reliance on key players who log the most minutes. This insight is pivotal when considering player fatigue and performance in crucial games. Typically the starting 5 players roated with around 2 or 3 from the bench will play a majority of the playoff games. 
This can create a intresting dynamic around lots of the teams in the NBA. 

# Conclusion
The immense talent in the NBA is not only impressive but also serves as a testament to the dynamic nature of the sport. Through these visualizations, we see how the game has evolved, driven by both individual brilliance and strategic innovations. The increasing emphasis on three-point shooting and the shifting dynamics of possession and playtime during playoffs highlight the league's adaptability and players' readiness to embrace new challenges.

Furthermore, the insights gleaned from the correlation heatmap and the distribution of minutes played underscores the intricate balance between individual performance and team strategy. As we move forward, it's fascinating to consider how these trends will continue to shape the future of basketball. Will the emphasis on three-pointers and pace continue to rise, or will we see a resurgence of traditional playstyles? As analytics become more deeply integrated into sports strategy, the NBA is poised for further exciting developments, promising a continually evolving spectacle for fans and players alike.

## References
### [Streamlit NBA App](https://nba-app-26cfxmvx5jaadc6rumhqcm.streamlit.app/)


### [GitHub Repository for NBA Stats Project](https://github.com/collinscd23/NBA-Stats-Project)
---

