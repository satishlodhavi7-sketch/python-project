# Amazon Prime Movies and TV Shows EDA

This project performs Exploratory Data Analysis (EDA) on the Amazon
Prime Movies and TV Shows dataset from Kaggle using Python, Pandas, and
Matplotlib.

Dataset:
https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows

## Objective

The objective is to explore the dataset, understand its contents,
identify patterns, and visualize key information about movies and TV
shows available in the dataset.

## Libraries Used

-   Python
-   Pandas
-   Matplotlib

Install the required libraries:

``` bash
pip install pandas matplotlib
```

## Dataset

Download the dataset from Kaggle and place the CSV file in the same
folder as your Python script or Jupyter Notebook. The CSV file is
commonly named `amazon_prime_titles.csv`.

## Exploratory Data Analysis

The analysis includes checking the dataset shape, column names, missing
values, and duplicate records. Duplicate rows are removed, date values
are converted to datetime format, and duration values are extracted for
analysis. Missing categorical values are handled where needed for
plotting.

## Visualizations

Eight graphs are included in this project:

1.  Movies vs TV Shows --- a bar chart comparing the number of movies
    and TV shows.
2.  Titles by Release Year --- a line chart showing the number of titles
    by release year.
3.  Top 10 Production Countries --- a horizontal bar chart showing the
    countries most frequently listed.
4.  Content Ratings --- a horizontal bar chart displaying the
    distribution of content ratings.
5.  Top 10 Genres --- a horizontal bar chart showing the most common
    genres.
6.  Movie Runtime Distribution --- a histogram showing movie durations
    in minutes.
7.  TV Shows by Number of Seasons --- a bar chart comparing TV shows by
    season count.
8.  Titles Added by Year --- a line chart showing the number of titles
    added each year, based on the date_added column.


## Conclusion

This project explores the Amazon Prime Movies and TV Shows dataset
through eight Matplotlib visualizations. The graphs help examine content
types, release years, production countries, ratings, genres, movie
runtimes, TV show seasons, and catalog additions. Final observations
should be written after running the analysis and reviewing the actual
charts.

## Dataset Credit

Dataset provided by Shivam Bansal on Kaggle:
https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows
