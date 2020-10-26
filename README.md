# Video_game_stat_analysis
You work for the online store Ice, which sells video games all over the world. User and expert reviews, genres, platforms (e.g. Xbox or PlayStation), and historical data on game sales are available from open sources. You need to identify patterns that determine whether a game succeeds or not. This will allow you to spot potential big winners and plan advertising campaigns.


In front of you is data going back to 2016. Let’s imagine that it’s December 2016 and you’re planning a campaign for 2017.
(The important thing is to get experience working with data. It doesn't really matter whether you're forecasting 2017 sales based on data from 2016 or 2027 sales based on data from 
2026.)


The dataset contains the abbreviation ESRB. The Entertainment Software Rating Board evaluates a game's content and assigns an age rating such as Teen or Mature.


## Data Description 
* games.csv 

| Attribute         | Description                                      |
|-----------------|------------------------------------------------|
| Name            | Name of the game                                  |
| Platform        | Gaming platform                                      |
| Year_of_Release | Year of release                                 |
| Genre           | Game genre                                |
| NA_sales        | Sales in North America in USD million |
| EU_sales        | Sales in Europe in USD million           |
| JP_sales        | Sales in Japan in USD million           |
| Other_sales     | Sales in other countries in USD million   |
| Critic_Score    | Critic score (maximum of 100)                |
| User_Score      | User Score (maximum of 10)              |
| Rating          | ESRB Rating|

Question: 
- How many games were released in different years. Is the data for every period significant?
- How long does it generally take for new platforms to appear and old ones to fade?
- Which platforms are leading in sales? Which ones are growing or shrinking? 
- Are the differences in sales significant? What about average sales on various platforms?
- What can we say about the most profitable genres? Can you generalize about genres with high and low sales?
- Look at the region distribution of the findings. 

Hypotheses for testing: 
—Average user ratings of the Xbox One and PC platforms are the same.
—Average user ratings for the Action and Sports genres are different.
