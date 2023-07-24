# Data-Driven Insights for Microsoft's New Movie Studio

## Table of Contents

* Introduction
* Business Problem
* Data Understanding
* Data Preparation
* Exploratory Data Analysis
* Business Recommendations
* Limitations and Future Steps
* Conclusion

## Introduction

Welcome to Microsoft's New Movie Studio Data Insights! In this project, I aim to discover the secrets of box office success by analyzing various factors that influence a movie's performance. 

By exploring genres, ratings, runtime, and audience engagement, I strive to provide valuable insights for making data-driven decisions in the movie industry.

## Business Problem

The movie industry is highly competitive, and producing successful films requires a deep understanding of audience preferences and market trends. 

Microsoft's New Movie Studio aims to leverage data-driven insights to enhance the chances of creating well-received and commercially successful movies. 

The key challenges include identifying the most promising genres, collaborating with successful studios, and engaging the audience effectively.

## Data Understanding

Movie data was collected from the following sources:

* Box Office Mojo.
* IMDB.
* Rotten Tomatoes.
* TheMovieDB.
* The Numbers.

The datasets contains valuable variables such as movie genres, runtime, ratings, and the number of votes. 

Our target variable is the average rating, which serves as a measure of audience satisfaction.

## Data Preparation

To ensure the accuracy of our analysis, we performed data cleaning, removing irrelevant information and handling missing values. 

Additionally, we calculated the total gross revenue of each movie to understand the overall financial success.

## Exploratory Data Analysis

Through exploratory data analysis, we identified trends in total gross revenue over the years, highlighting the movie industry's growth and profitability. 

We also explored the top movie studios with the highest average ratings, providing insights for potential collaborations. 

Furthermore, we investigated the most common genres of high-rated movies to guide the studio's production decisions.

### The Trend of Total Gross Revenue Over the Years

![graph](./images/fig1.png)

The total gross revenue has generally increased over time, indicating a growth in the movie industry's revenue generation

### Movie Studios Having the Highest Average Ratings for their Films

![graph](./images/fig2.png)

Trafalgar, NAV, GrtIndia, SHO, BSC, PDA,App., Good Deed, RME and MUBI movie studios received the highest average ratings for their films. This indicates their strong performance in delivering movies that are well-received by the audience.

### Most Common Genres of Movies that have Received High Ratings

![graph](./images/fig3.png)

Drama, Documentary, Comedy, Action, Adventure, Biography, Romance, Crime, Thriller and Animation genres have the movies with high ratings (i.e., movies with an average rating above 7.5). 
This indicates their popularity and frequency in movies that have been well-received by the audience.

### The Correlation Between the Runtime of a Movie and its Average Rating

![graph](./images/fig4.png)

I found a correlation coefficient of 0.1373. This a weak positive correlation between the runtime of a movie and its average rating.
Meaning that the increase in average rating with longer runtime is not very strong.

### How the Number of Votes Received by a Movie Impacts its Average Rating

![graph](./images/fig5.png)

I found a correlation coefficient of 0.2619. There is a positive correlation between the number of votes received by a movie and its average rating.
Meaning that, on average, as the number of votes received by a movie increases, its average rating tends to increase as well.

## Business Recommendations

Based on this analysis, I propose the following recommendations for Microsoft's New Movie Studio:
* Focus on Popular Genres: Concentrate movie production efforts on genres that have consistently received high ratings, such as Drama, Documentary, Comedy, and Action. These genres have a higher chance of resonating with the audience.

* Collaborate with Top-Rated Studios: Consider partnerships or collaborations with studios that have a proven track record of producing high-rated films. Collaborating with successful studios can boost the studio's reputation and increase the likelihood of producing successful movies.
* Engage with the Audience: Actively engage with the audience to encourage voting and participation. Increased audience engagement can lead to higher ratings and valuable feedback for future improvements.

Based on our analysis, we propose the following recommendations for Microsoft's New Movie Studio:

Focus on Popular Genres: Concentrate movie production efforts on genres that have consistently received high ratings, such as Drama, Documentary, Comedy, and Action. These genres have a higher chance of resonating with the audience.

Collaborate with Top-Rated Studios: Consider partnerships or collaborations with studios that have a proven track record of producing high-rated films. Collaborating with successful studios can boost the studio's reputation and increase the likelihood of producing successful movies.

Engage with the Audience: Actively engage with the audience to encourage voting and participation. Increased audience engagement can lead to higher ratings and valuable feedback for future improvements.

## Limitations and Future Steps

While our analysis provides valuable insights, it has certain limitations. The movie industry is dynamic, and factors influencing movie success can change rapidly. Continuous monitoring and adaptation are necessary to stay competitive. To further improve this project, we can explore advanced predictive modeling and sentiment analysis techniques to better understand audience preferences.

In the future, integrating real-time data and conducting market research surveys for direct audience feedback would enhance our decision-making process.

## Conclusion

This analysis equips Microsoft's New Movie Studio with data-driven insights to make strategic decisions in the competitive movie industry. By focusing on popular genres, collaborating with successful studios, and actively engaging with the audience, the studio can improve its chances of producing successful and well-received films.
