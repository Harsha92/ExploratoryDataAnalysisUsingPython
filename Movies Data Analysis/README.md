
---
# **Table of Contents**
---

1. [**Introduction**](#Section1)<br>
2. [**Problem Statement**](#Section2)<br>

---

[![Movies](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/movies_image_git.jpeg "Movies")](https://www.google.com/url?sa=i&url=https%3A%2F%2Ftowardsdatascience.com%2Fbuilding-a-movie-genre-classifier-using-a-dataset-created-using-google-images-4752f75a1d79&psig=AOvVaw2xqS3d6PgXt8Di_GRpkIhw&ust=1613185577663000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCMifpuKu4-4CFQAAAAAdAAAAABAn "Movies")

# Introduction

The Internet Movie Database (IMDb) is a website that serves as an online database of world cinema. This website contains a large number of public data on films such as the title of the film, the year of release of the film, the genre of the film, the audience, the rating of critics, the duration of the film, the summary of the film, actors, directors and much more. Faced with the large amount of data available on this site, I thought that it would be interesting to analyze the movies data on the IMDb website between the year 2006 and the year 2016.

# Study of the problem
Objective: Cinemania, an American Box Office where tickets are sold to the public for movies is planning to add new services and enhance the quality of existing services. To tackle this problem we are performing the analysis of IMDB data from 2006 to 2016.

# Python libraries

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

# Key Insights from Data
Below are some useful observations from movies data
- [No.of movies released in each year](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/Visualizations/Movies_Year.png "No.of movies released in each year")
- [No.of movies released in each genre](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/Visualizations/Movies_Genre.png "No.of movies released in each genre")
- [Revenue of movies as per genre](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/Visualizations/Revenue_Genre.png "Revenue of movies as per genre")
- [Top Directors who generated most revenue](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/Visualizations/top_Directors.png "Top Directors who generated most revenue")
- [Top 10 actor and director combinations](https://raw.githubusercontent.com/Harsha92/ExploratoryDataAnalysisUsingPython/main/Movies%20Data%20Analysis/images/Visualizations/Actor_Director.png "Top 10 actor and director combinations")

- Director J.J. Abrams has made the highest revenue in Action Genre of 1.56 billion dollars followed by Joss Whedon with an revenue of 1.08 billion dollars. 
- Director David Yates has made the highest revenue in Adventure Genre of over 1.2 billion dollars with main actors as Daniel Radcliffe and Emma Watson. 
- Director Pete Docter has made the highest revenue of  649.43 million dollars  in animation genre.
- There are 55 Action Genre movies in top 100 movies which made the revenue of 18.225 billion dollars and with average audience rating of 7.2 and Metascore of 65
- There are 22 Animation Genre movies in top 100 movies which made the revenue of 6.429 billion dollars and with average audience rating of 7.6 and Metascore of 75
- Action genre has generated the highest revenue of 34513.48 million dollars followed by Animation genre with revenue of 9083.46 million dollars.
- Boyhood is the movie which has highest Critic Rating of 100/100 directed by Richard Linklater released in 2014
- The Dark Knight is the movie which has highest Audience Rating of 9/10 directed by Christopher Nolan released in 2008



# What I have learned?
After completing the project, I got goo understanding of below concepts:

- Understood all the steps involved in a typical data analysis process
- Be comfortable posing questions that can be answered with a given dataset and then answering those questions
- Understood how to investigate problems in a dataset and wrangle the data into a format that can be used
- Have practice communicating the results of your analysis
- Be able to use vectorized operations in NumPy and pandas to speed up your data analysis code
- Got familiar with pandas' Series and DataFrame objects, which let me access the data more conveniently
- Understood how to use Matplotlib, Seaborn to produce plots showing my findings
