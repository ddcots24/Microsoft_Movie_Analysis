# Microsoft_Movie_Analysis
## Overview
Topic: Microsoft wants to enter the movie business industry
- As a part of their Data Scientist team, I was tasked to give three recommendations to Microsoft for entering the industry 
- We used SQL along with the Python package Pandas to load in and clean data from data sets as well as analyze, create visualizations in tableau and make recommendations
## Business Understanding
- The key stakeholders are the higher ups in the company such as the CEO and Owners
- Microsoft is entering a very saturated industry with many big competitors
   - How can Microsoft best navigate starting a new movie studio?
- A good measure of success in any industry is the return on investment and profit
- In our analysis we focused in on recent movies from 2010-2019 and their profitability
- The more granular focus of our analysis was in the profitability of top: movie genres, movie run times and movie release times
## Data Understanding
- Used two different data sets
  - IMDB [website](https://www.imdb.com/)
    -   A data set which contained categorical information on movie start years, run times, peoples profession associated with the movie (actors, actresses, writers, directors, producers etc..)
  -  [The Numbers](https://github.com/ddcots24/Movie-Data-Analysis-Microsoft/blob/main/zippedData/tn.movie_budgets.csv) [website](https://www.the-numbers.com/)
     -  A data set which contained numerical information on movie production budgets and gross earnings from which we were able to calculate the profit
 -  We merged the two different data sets to conduct our analysis on movie profitability in our three areas of focus
## Data Analysis/Visualizations ([Tableau Viz's](https://public.tableau.com/views/MicrosoftMovieAnalysis/GenresandProfit?:language=en-US&:display_count=n&:origin=viz_share_link))
### Most Profitable Genres
 - Based on our data we found most profitable genres by median profit
 - From the top 10 genres with the highest profitability based on the median profit we decided to focus in on the top 4 genres
### Top 3 Genre's Profitability based on Run Times 
- For these Top 4 profiting genres, we analyzed each with respect to profit by run times
- We found that for animation movies the most profitable run times are in the time range of 80-110 minutes
- For the other three genres, the most profitable run times are in the interval of 140-155 minutes
  - The 125-140 and 155-170 run times are quite profitable as well
### Most Profitable Months to Release the Movies for Top 3 Genres 
- Profitability of top 3 Genres
  - Ran a Market trend Analysis
  - Saw that the most profitable movies were released in May, June, July and November
## Conclusion
- If Microsoft were to enter the movie industry we would give 3 recommendations:
   - Pursue 1 of the top 3 most profitable genres (Animation, Adventure and Sci-Fi)
   - For Adventure, Sci-Fi focus on run times between 135-150 minutes. For Animation focus on run times between 90-105 minutes
   - If you are going release a movie, do so in May, June, July or November
 ## Repository Information
 - This repository contains:
   - A gitignore file
   - 2 preliminary Jupyter Notebooks
   - Final project Jupyter Notebook
   - A readme file
