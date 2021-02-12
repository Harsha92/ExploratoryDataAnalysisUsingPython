
[![Movies](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/movies_image_git.jpeg "Movies")](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftowardsdatascience.com%2Fbuilding-a-movie-genre-classifier-using-a-dataset-created-using-google-images-4752f75a1d79&psig=AOvVaw2xqS3d6PgXt8Di_GRpkIhw&ust=1613185577663000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMifpuKu4-4CFQAAAAAdAAAAABAn "Movies")

# Introduction

The Internet Movie Database (IMDb) is a website that serves as an online database of world cinema. This website contains a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more. Faced with the large amount of data available on this site, I thought that it would be interesting to analyze the movies data on the IMDb website between the year 2006 and the year 2016.

# Study of the problem
Objective: Cinemania, an American Box Office where tickets are sold to the public for movies is planning to add new services and enhance the quality of existing services. To tackle this problem we are performing the analysis of IMDB data from 2006 to 2016.

# Python and Data Science

To do Data Science with Python, I use Python with the following software libraries:
- **Numpy:** it contains many functions for numerical computation (vectors, matrices, polynomials, etc.).
- **Matplotlib:** it allows to trace and visualize data in the form of graphs.
- **Pandas:** it allows to manipulate and analyze data (dataframes).
- **Seaborn:** it complements Matplotlib by providing attractive statistical graphics.

# Approach 

The problem was divided into several steps:

1. **Data Collection:** Data was collected in a csv file from IMDB website. Here is the  [movies data](https://raw.githubusercontent.com/insaid2018/Term-1/master/Data/Projects/1000%20movies%20data.csv "movies data") which we used for analysis.
2. **Data Wrangling:** The datasets were uploaded to a dataframe and explored. Null values were filled in wherever appropriate and polluted values were discarded or wrangled.
3. **EDA:** Extensive data visualisation and summary statistics were used to extract insights and pattern from the data. 

# Preparing the dataset

Here is the [movies data](https://raw.githubusercontent.com/insaid2018/Term-1/master/Data/Projects/1000%20movies%20data.csv "movies data") which are released between 2006 and 2016.

After having the data available and understanding the meaning of each data items, I started the data selection phase, that is, the data I want to keep for my Data Science study.
Here are the data I want to keep:
- Movie title
- Genre of the movie
- Duration of the movie (in minutes)
- Release year of the movie
- Number of public votes
- Public rating (score out of 10)
- Critics rating (score out of 100)
- Movie Gross (millions of dollars)
- Director of the movie
- Main actors in the movie
- Rank of the movie
