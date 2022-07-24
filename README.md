# Analysis of the TMdB Movies Dataset.
## by Keith Obade


## Dataset

This data set contains information of about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

This data set has the following columns: id - This is the unique identifier of a movie:

- imdb_id - This is the Imbd identifier
- popularity - This shows movies and their probability of discovery since with higher popularity it's boosted in the search results.
- budget - This shows the budget of the associated movie.
- revenue - This shows the revenue earned from the movie.
- original_title - This is the title of the movie.
- cast - This shows the main actors of the movie.
- homepage - This shows the website of the movie.
- director - Shows the director of the associated movie.
- tagline - This shows the major line for the associated movie.
- keywords - This shows the key words of the associated movie.
- overview - This shows the summary of the associated movie.
- runtime - Shows the number of minutes the associated movie runs for.
- genres - shows the genres of the associated movie
- production_companies - This shows the production companies involved.
- release_date - This shows the release date of the associated movie.
- vote_count - This shows the total vote count of the associated movie.
- vote_average - This shows the average vote count of the associated movie.
- release_year - This shows the release year of the associated movie.
- budget_adj - shows the budget of the associated movie in terms of 2010 dollars, accounting for inflation over time.
- revenue_adj - shows the revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time

This dataset was fairly clean so I took these steps to wrangle:

  - Removed unnecessary columns
  - Changed null values on the director column to No Directors.
  - Dropped other null values on the columns.


## Summary of Findings


### Limitations

- One limitation I had was that I removed all the null values in the directors data of which I could research on the missing data on the internet and I would find some of the data.

- I also did not perform statistical tests on the data frame provided.

- I also left the duplicated value in the data frame.

### Conclusion 1

From the first question, Are the movies that are released more recently have more profit? We were able to find out that the profit gradually increased upto certain years but it had a lot of fluctuations over the years and it wasn't a clear gradual increase of movie profits over the years.

We can also the adjusted profit is way higher in the years before 2010 showing that with inflation the value of profit is affected over the years.

### Conclusion 2

From the second quetion, Does the voting average and vote count affect the popularity rating of a movie? We found out that the two parameters (voting average and vote count) have a weak correlation with the popularity but for the vote count there is a stronger correlation than voting average since most of the vote count were in the upper quartile of the popularity rating. We can also see that the top 5 movies are not similar in the two parameters showing that the vote count and vote average do not have a clear correlation from the findings.
