---
layout: post
title:  "NBA DATA"
author: Carson Collins
description: A look at the top 100 NBA players stats from Regular and post season over the last 10 years
image: /assets/images/bball.png
---
# NBA DATA over past 10 years
## Introduction
As a passionate NBA fan and budding data analyst, I embarked on a project to compare the top 100 NBA players' regular and postseason stats over the last decade. This blog outlines the methods I employed for data extraction and cleaning from the NBA's official website. My goal was to uncover fascinating correlations and insights while honing my data scraping skills. I believe this exercise will deepen my appreciation for the exceptional talents in the NBA and the intricate process of data analysis. Key questions guiding my research include:

Which player stats correlate significantly, and are there any unexpected findings?
How is the distribution of "Minutes Played" among the top 100 players, and what insights does it offer?
What do comparisons of playoff versus regular season "Minutes Played" for mid-level players reveal about team rotations and bench player utilization?
How has the game evolved in the past few years, as seen through "per 48 min" and "per possession" statistics?

## Ethical Considerations
Before proceeding, I ensured my data scraping aligned with ethical standards. The NBA permits web scraping of historical data, provided it's not used for sports betting or financial gain. My project, focused solely on personal education, aligns with these guidelines.

## Data Collection & Cleaning
The data collection was fairly simple and easy to clean given that the NBA website and API provide great data.
I chose to keep all the stats provided in the tables and then added a few ratios further down the line. One ratio was the possession stat. This took into account FGA, OREB, TOV, and FTA to create essentially a Possession. Then I also made adjustments to turn a number of given stats into percentages.

The first step was changing the year to an integer which would make future analysis easier.
Then I went ahead and made some team adjustments. Standardizing team names by replacing 'NOP' and 'NOH' with 'NO' in the 'TEAM' column. This refers to the New Orleans team name change.
I also simplified the Regular Season column, changing it to 'RS'.

## Conclusion
Extracting data from the NBA's website and API was straightforward, thanks to their well-organized datasets. I retained all stats from the tables, adding ratios like a 'Possession' stat—factoring in FGA, OREB, TOV, and FTA—and converting numerous stats into percentages for more nuanced analysis.

Initial steps included converting the 'Year' field to an integer format for easier analysis and standardizing team names (e.g., merging 'NOP' and 'NOH' into 'NO' for New Orleans). Additionally, I simplified the Regular Season column label to 'RS'.



## EDA!
If you found this post intresting and want to know how the data turned out and what I learned check out my next post!
[Analysis and Insights!](https://collinscd23.github.io/2023/12/11/EDA-Analysis.html) 

## References
### [Streamlit NBA App](https://nba-app-26cfxmvx5jaadc6rumhqcm.streamlit.app/)


### [GitHub Repository for NBA Stats Project](https://github.com/collinscd23/NBA-Stats-Project)



