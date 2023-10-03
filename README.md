# data_collection_challenge

### This repo contains the necessary artifacts to satisfy the requirements of this challenge.

| File | Description |
| - | - |
| `mars_articles.json` | JSON export of the Mars news articles and previews for Part 1 of this challenge. |
| `mars_weather_export.csv` | CSV export of the Mars temperature data for Part 2 of this challenge. | 
| `part_1_mars_news.ipynb` | Jupyter Notebook code used for Part 1 of this challenge. |
| `part_2_mars_weather.ipynb` | Jupyter Notebook code used for Part 2 of this challenge.  |

### Analysis Questions for Part 2 - Mars Weather

These questions and answers are included in the Jupyter Notebook, but added here for convenience.

# How many months exist on Mars?
There are 12 months represented in the data (Month 1 through Month 12). Above is the breakdown of the number of readings per Martian month.

# How many Martian (and not Earth) days worth of data exist in the scraped dataset?
By selecting the distinct 'sol' records in the data, I found there are 1867 days worth of data.

# What are the coldest and the warmest months on Mars (at the location of Curiosity)?
The data shows that Month 3 is the coldest month (average is -83.3 degrees celcius) and Month 8 is the warmest (average is -68.4 degrees celcius).

# Which months have the lowest and the highest atmospheric pressure on Mars?
The data shows that Month 6 has the lowest atmospheric pressure (745.1) and Month 9 has the highest atmospheric pressure (913.3).

# About how many terrestrial (Earth) days exist in a Martian year?
By looking at the data, I can see that Martian Month 1 starts at sol 351, 1019, and 1688. The terrestrial dates for these sol values are 2013-08-01, 2015-06-19 and 2017-05-06. By finding the difference between the start date and end date for each of these spans, I was able to calcuate the total earth days in a Martian year to be 687.
