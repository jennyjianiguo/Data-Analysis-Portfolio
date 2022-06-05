## Web scraping and data exploration of IMDb's top 100 movies ranked by IMDb users.

Python libraries used: pandas, BeautifulSoup, request

SQL skills used: joins, subqueries, CTEs, temp tables, windows functions, aggregate functions, creating views, converting data types

**Web Scraping using Python**

- Collected movie title, rank, year, time, genre, rating, metascore, votes, gross profit, description, director, and actor information from IMDb page
- Consolidated data into pandas database
- Converted database to CSV file

**Exploratory Data Analysis using SQL**

Queries explored:
- Directors that appear on the list more than once
- Most popular film periods
- Ranking top movies that were released in the same year
- Most Popular Genres (through parsing comma separated data)

**Sources**

Data from [IMDB](https://www.imdb.com/search/title/?count=100&groups=top_1000&sort=user_rating).
