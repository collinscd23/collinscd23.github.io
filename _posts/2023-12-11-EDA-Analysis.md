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
Here we can see that the Number of Possessions as also had a postive trend over the past few years. This can lead us to a few intresting insights. First is the pace of the game. Naturally the more times you get the ball means that you are either shooting, Rebounding, turning it over or stealing more. So the pace is faster. I found this to be very intresting. The best way i can connect this with the last visual is that the top players tend to spend more of the possesions shooting threes then they did in the past aswell as a number of other factors. 

## FG3A (Three pointer Attempts Per 100 Possesions from 2012 to 2021)
![Number of FG3A per 100 POSS](/assets/images/FG3A_100.png)

As a final look lets see how the # point attempt as changed per 100 possesion. 

# What player stats are correlated with each other from the Data set collected? 
## Correlation Heatmap Analysis

![Correlation Heatmap](/assets/images/heatmap.png)
*Figure 4: Correlation Heatmap*

The heatmap reveals how different stats interact. For example, the correlation between Points Scored (`PTS`) and Field Goals Made (`FGM`) is intuitive – more points usually come from making more baskets. This visualization helps me understand the relationships between various aspects of the game. 

![Zoom on Heatmap](/assets/images/newplot.png)
Some Intresting findings I came across while looking over this chart is that is that AST (assists) and STL (steal) have a fairly warm correlation, which is intresting because We can assume that when a player steals the ball they are a connection to Passing it to someone else who scores. I was curious then to see if maybe the correlation was similar to PTS scored meaning that they would steal the ball and then score themselves. It turns out the correlation between STLs and PTS arent very close. Maybe then players who tend to steal the ball also tend to pass it to a teammate who scores. Showing a possible type of playstyle. 

# What does the distribution of “Minutes Played per game in RS VS Playoffs” thoughtout the TOP 100 players from 2012 to 2021 look like? AND what can we learn.
## Mins played Chart Analysis
![Mins PLayed RS vs Playoff from 2012 to 2012](/assets/images/Playoffsvsreg.png)
With some further investigation we can see that during the regular season the amount of time is pretty normally distributed betweeen the 48 mins in an game. With the higher profile players playing more minutes and the bench players playing less. But as we look at the Playoffs we see the center kind of implode. Where both endeds are inflated. The better players are getting more time playing and the others are getting less. This makes sense because in the playoffs the teams are more focused on winning and not worried about keeping there stars in as healthy because they want to win. AS for the regular season its okay to give the other players more time since the games dont matter as much. 

## Histogram of Minutes Played in Playoffs Analysis
![Histogram of Minutes Played in Playoffs](/assets/images/Minsplayedgraph.png)
*Figure 5: Histogram of Minutes Played by Players in Playoffs*
Here is a further look into the time played in the playoffs. 
Lastly, the histogram  shows the distribution of minutes played during the playoffs. The steep decline after the initial peak suggests a reliance on key players who log the most minutes. This insight is pivotal when considering player fatigue and performance in crucial games. Typically the starting 5 players roated with around 2 or 3 from the bench will play a majority of the playoff games. 
This can create a intresting dynamic around lots of the teams in the NBA. 

# Conclusion
Even though the talent required to be in the NBA is imense its still very mindblowing to know that the gap in skill is still massive between a select few players in the NBA and it shows through a number of the graphs ive found. 


---

