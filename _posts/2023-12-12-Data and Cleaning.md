---
layout: post
title:  "NBA DATA"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/bball.png
---
# NBA DATA over past 10 years
## Introduction
I wanted to compare the top 100 players from each year's regular and offseason stats in the NBA. In this blog, I'll cover the procedure I used to find and clean the data from the NBA official website.
I find this topic interesting and cool because I'm a big fan of the NBA and basketball in general. I thought it would be cool to see what interesting correlations and findings I could uncover while practicing my newly learned skills in data scraping. I think it will also help me to better appreciate the impressive talent and effort it takes to be an NBA player, as well as the thought that goes into being a data analyst.
Here are a few questions I wanted answered from my research:
What player stats are correlated with each other from the large list of stats collected? Are there any surprising findings?
What does the distribution of "Minutes Played" look like throughout the top 100 players? What does this tell us?
What does the mean of playoff vs regular season "Mins Played" for the middle proportion of players tell us about how teams rotate their talent? Do bench players get more or less time in the playoffs?
How has the game changed over the past 10 years? (Comparison of "per 48 min" stats and "per possession" stats)

## Ethical Considerations
One ethical precaution I took was to research online to find if the NBA allows web scraping. I found that the NBA allows web scraping for their pages that show past data and are not comfortable with current data being scraped and used for sports betting and other facets of monetary gain. But my use is for personal education.

## Data Collection & Cleaning
The data collection was fairly simple and easy to clean given that the NBA website and API provide great data.
I chose to keep all the stats provided in the tables and then added a few ratios further down the line. One ratio was the possession stat. This took into account FGA, OREB, TOV, and FTA to create essentially a Possession. Then I also made adjustments to turn a number of given stats into percentages.

The first step was changing the year to an integer which would make future analysis easier.
Then I went ahead and made some team adjustments. Standardizing team names by replacing 'NOP' and 'NOH' with 'NO' in the 'TEAM' column. This refers to the New Orleans team name change.
I also simplified the Regular Season column, changing it to 'RS'.

## Conclusion
Now with the data ready, we can jump into action and see what interesting surprises lay hidden in the data. I will continue this blog with a separate post covering the details and performing an EDA, hopefully answering the questions I have above.


## References
[NBA StreamLit App](https://nba-app-26cfxmvx5jaadc6rumhqcm.streamlit.app/)
[GitHub Repository for NBA Stats Project](https://github.com/collinscd23/NBA-Stats-Project)


