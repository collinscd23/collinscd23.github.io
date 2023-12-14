---
layout: post
title:  "NBA DATA"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/blog-image.jpg
---
# NBA DATA over past 10 years
## Introduction
- I wanted to make some comparisons of the top 100 players from each years regualr and off season stats for the NBA. In this blog ill cover the procedure i used to help me find and clean the data from the NBA offical website.
- I found this topic intresting and cool becasue im a big fan of the NBA and basketball in genral. I thought it would be cool to see what intresting correltaions and findings i could while practicing my new learned skills in Data scraping. I think it will also help me to better apperciate the impressive talent and effort it takes to be an NBA player, aswell as the thought that goes into being a data analysis.
- Here are a few questions i wanted Awnsered from my research,
-   1. What player stats are correlated with eachother from the large list of stats collected? Are there any surprising findings?
    2. what does the distribution of "Minutes played" look like thorughout the top 100 players? What does this tell us?
    3. What does the mean of playoff VS regualr season "Mins played" for the middle porportion of players tell us about how teams rotate there talent? Do Bench players get more or less time in the Play off?
    4. How has the game Changed over the Past 10 years. (comparison of "per 48 min' stats and "per possestion" stats)

## Ethical Considerations
- Ethical procautions I took to was doing my research online to find if the NBA allowed webscraping. I found that the NBA allows webscaping for there pages that show past data and are not confortable with current data being scraped and used for sports betting and other facets of money gain. But my use is for personal education. 

## Data Collection & Cleaning
The Data collection was fairly simple and easy to clean given that the NBA website and API provide great data.
I chose to keep all the stats provided on the tables and then adding a few ratios further down the line. One ratio was the possestions stat. This took into account for FGA, OREB, TOV, and FTA to create essentially a Possestion. Then I also made adjustments to make a number of given stats into percenatges.
-The first step was changing the year to an interger which would make future analysis easier.
-Then i went ahead and did some team adjustments.  Standardizing team names by replacing 'NOP' and 'NOH' with 'NO' in the 'TEAM' column. This is referraing the the New Orlean team name change.
I also did some simplifying to the Regular season column changing it to RS.

## Conclusion
Now with the data ready we can jump into action and see what intresting surprises lay hidden in the data. I will continue this blog with a seprate post covering the details and performing an EDA, Hopefully awnsering the questions i have above.


## References 
- https://github.com/collinscd23/NBA-Stats-Project
