# Movies-Dataset-Power-Bi-Dashboard-

# Dataset Description:
This data set contains information about +9000 movies extracted from TMDB API.

# Columns Descreption:
Release_Date: Date when the movie was released.
Title: Name of the movie.
Overview: Brief summary of the movie.
Popularity: It is a very important metric computed by TMDB developers based on the number of views per day, votes per day, number of users marked it as "favorite" and "watchlist" for the data, release date and more other metrics.
Vote_Count: Total votes received from the viewers.
Vote_Average: Average rating based on vote count and the number of viewers out of 10.
Original_Language: Original language of the movies. Dubbed version is not considered to be original language.
Genre: Categories the movie it can be classified as.
Poster_Url: Url of the movie poster.

# Exploration Summery
we have a dataframe consisting of 9827 rows and 9 columns.
our dataset looks a bit tidy with no NaNs nor duplicated values.
Release_Date column needs to be casted into date time and to extract only the year value.
Overview, Original_Languege and Poster-Url wouldn't be so useful during analysis, so we'll drop them.
there is noticable outliers in Popularity column
Vote_Average bettter be categorised for proper analysis.
Genre column has comma saperated values and white spaces that needs to be handled and casted into category.
We endded up with a datafram of a total of 6 columns and 25551 rows to dig into during our analysis after comleting our cleaning.

![image](https://github.com/user-attachments/assets/83f01a0e-e6d3-459a-aa2d-76742181ea83)
![image](https://github.com/user-attachments/assets/9b6da6fc-8ca0-44d0-9098-a497cd6dffa6)
