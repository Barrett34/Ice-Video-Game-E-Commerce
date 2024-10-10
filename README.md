# Ice-Video-Game-E-Commerce
Identify patterns that determine whether or not a video game will succeed or not. Dataset from video game store Ice.

# Intorduction

In this study I will look at a dataset from 2016 to prepare a 2017 prognosis for a company named Ice. We will determine whether or not a video game will succeed or not based on statistical and exploratory data analysis. This will allow us to spot potential big winners and help with planning advertising campaigns for Ice.

# Hypotheses

1. Average user ratings of the Xbox One and PC platforms are the same.

2. Average user ratings for the Action and Sports genres are the same.


# Data Description
— Name - Video game title

— Platform - Platform the video game was on

— Year_of_Release - Release Year

— Genre 

— NA_sales (North American sales in USD million) 

— EU_sales (sales in Europe in USD million) 

— JP_sales (sales in Japan in USD million) 

— Other_sales (sales in other countries in USD million) 

— Critic_Score (maximum of 100) 

— User_Score (maximum of 10) 

— Rating (ESRB) - E: everyone; - E10+: everyone 10+; - T: Teen; - M: Mature 17+; - A: Adults only 18+; - RT: rating pending.

# Conclusions

In this study of the video game dataset, we analyzed video game player's behavior in order to identify patterns that show whether a game succeeds or fails and test two statisical hypotheses.

We first got familiar with the data and calculated some descriptive statistics. After completing that analysis, we cleaned up the data: making column names more readable, filling in missing values, appropriating data types, checked for dupes. We decided to keep some values as the way they already were because we didn't find any appropriate way to fill them all. We didn't want to incorrectly change data that could lead to false assumptions. We then finally calculated total sales for all regions.

After completing a exploratory analysis, we came to the following conclusions:

- Most games in this dataset were released between 2009-2012, but anything before 2000 is not very significant since we are creating a prognosis for 2017.

- There were 5 platforms that standout the most in terms of sales in the 3 regions: `PS4`,`PS3`,`3DS`,`X360`,`XOne`

- It takes around 6-10 years for a new platform to appear and for the older ones to fade around 5 years. We took this into consideration for our 2017 prognosis to make sure the most popular platforms were included.

- No significant difference was found in the top 5 platforms in terms of sales.

- From the scatterplots and Pearson coefficients, we saw that there was a small positive linear correlation between sales and professional critic reveiws for the `PS4`. There was no linear correlation between the sales and gamer reviews for the `PS4`.

- There was no significant difference between sales for the same game on different platforms.

- Aciton games were the most profitable and popular. In general more active games have higher sales in comparison to more intellectual games which showed very low sales.

Region Study with the Top 5 Platforms and Genres:

- NA region: The typical NA region player enjoys playing `M` rated action games on the `X360` platform. The 2nd most played ESRB rated game received `E` rating. The second most enjoyed genre in this region was `Shooter`.

- EU region: The typical EU region player enjoys playing `M` rated action games on the `PS4` platform. The 2nd most played ESRB rated games received `E` rating. The second most enjoyed genre in this region was `Shooter`.

- JP region: The typical JP region player enjoys playing `E` rated role-playing games on the `3DS` platform. The 2nd most played ESRB rated games received `T`. The second most enjoyed genre in this region was `Action`.

Statistical Hypothesis Testing:

1. Average user ratings of the `XOne` and `PC` platforms are the same.
2. Average user ratings of the `Action` and `Sports` genre are the same.

The first test we accepted the null hypothesis - the average was the same.
The second test we rejected the null hypothesis - the average was different.
