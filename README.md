# Busting_Fandango_Rating_Sytem

## Objective
If you are planning on going out to see a movie, how well can you trust online reviews and ratings? Especially if the same company showing the rating also makes money by selling movie tickets. Do they have a bias towards rating movies higher than they should be rated?

This project tries to verify if Fandango movie rating is biased or not, by comparing its 'Ratings' metric and 'Stars' which the website shows on movie thumbnail.

## About the DataSet
This is the data behind the story [Be Suspicious Of Online Movie Ratings, Especially Fandango’s](https://fivethirtyeight.com/features/fandango-movies-ratings/] openly available on 538's github: [https://github.com/fivethirtyeight/data](https://github.com/fivethirtyeight/data). There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

## Conclusion
While analyzing the data of Fandango, it was observed that Fandango does the Math.ceil for every critic/user rating. For example if critic review is 4.1, Fandango will potray it as 4.5 on its website, claiming movie to better than its actual worth.

Also when compared with other website ratings like IMDB showed in KDE plot in cell 244, it was found out that for every movie, Fandango has given more positive rating than its counterparts, which shows an intention to potray movie is better than it is, so more customer are attracted to watch it.
