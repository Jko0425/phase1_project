![Mad Max](https://github.com/Jko0425/phase1_project/blob/main/Mad%20Max.jpg)
# What Drives a Film's Profit Margin?

## Overview
Movie studios often take risks when it comes to funding something new or different. This project can help minimize Microsoft's risks. The data shows that ratings and cast/crew members may contribute increasing profit margins. However, a renown cast/crew may result in a high production budget, which may deter investors. If less capital is invested, the studio may need to shift genres in order to maximize their return. The studio may use the findings from this project to aid their decision process.

## Business Problem
There are many variables that affect a movie's ROI (e.g. if the movie is part of a series/universe, or the notoriety of a cast member). Some of these variables may be difficult to measure. Therefore, quantitative data, such as `ratings`, `cast/crew members`, and `genres`, will be investigated. By analyzing the data provided, a company like Microsoft will be able use these results to determine what type of movie to invest in.

## Data
A conglomerate of data from different databases is used in this project. The names of the cast/crew and ratings is provided by [IMDB](https://www.imdb.com/), whereas the data for budget and gross is provided by [The Numbers](https://www.the-numbers.com/). The data for ratings and vote count from IMDB was substituted in for the missing data provided by [The Movie Database](https://www.themoviedb.org/?language=en-US).

## Results/Analysis
The films that are in the top 10% of earnings, have ratings considerably higher than the average. The _Highest ROI_ and _Lowest ROI_ contains returns that are in the top 10% and bottom 10% respectively; whereas, the _Mid ROI_ contains a number of returns above and below the overall median.
![boxplot](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/boxplot.png)
The following bar chart demonstrates a similar theme; film series often dominate the box office. These films also have higher ratings most likely due to their cult-like following (e.g. Marvel). Films directed by Steven Spielburg (one of the most prominent directors) are well below the top 10% of earners, while averaging higher ratings.
![scatter_directors](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/bar_chart_directors.png)
The writers' scatterplot shows how an original idea can become a successful franchise as seen by Ken Daurio's _Despicable Me_ and Geogre Lucas' _Star Wars_. The Coen brothers, despite their decorated original scripts, routinely score below the top 10%. 
![scatter_writers](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/bar_chart_writers.png)
Again, actors/actresses that are involved in series rountinely having higher ROIs than their counterparts.
![scatter_actors](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/bar_chart_actors.png)
Action and adventure genres seem to dominant the big screen. This may be the result of the oversaturation of superhero movies. 
![hist_genres](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/hist_genres.png)
When looking at which films had the greatest return as a percentage comedy drama and horror seem to dominate. This may be do to the low budget needed to produce these films, whereas action and adventure films require a substantially high budget.
![hist_genres_top_percent](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/hist_genres_top_percent.png)
However, producing a comedy or drama may be a gamble as these genres also return the lowest percentage.
![hist_genres_low_percent](https://github.com/Jko0425/phase1_project/blob/main/Data_charts/hist_genres_low_percent.png)

## Conclusion
Based on these results, Microsoft can make a successful film by following these recommendations:
* __Focus on a high rating__. Films with higher ROI often averaged higher ratings than their competitors.
* __Be careful in hiring talents__. Most of the successful directors are seen directing film series and not originals. If they are given a new IP, would they perform better or worse than someone more renown like Steven Spielburg? Christopher Nolan has shown he is capable of producing original content with high ratings and ROIs, while an actor like Brad Pitt has low earnings despite staring in films with higher than average ratings.
* __Choose a genre based on the available budget__. If Microsoft wishes to manage smaller projects, they should look into genres like horror. On the otherhand, if Microsoft wants to create a blockbuster film, the action and adventure genre is best.
