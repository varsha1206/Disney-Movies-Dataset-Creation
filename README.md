# Disney-Movies-Dataset-Creation

In this project, I used Beautiful Soup to scrape Disney movie details from Wikipedia. The data I obtained was from the information box provided by wiki on their page. 

I first collected the list of movies and their respective links from the total list of movies [here](https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films), then scraped the information for the movies using beautiful soup and stored it as a list of dictionaries. 

Since Web Scraping produces a lot of unwanted/ unclean data, I performed some basic data cleaning to organise the data and remove junk. 

I also added IMDB ratings using the OMDB API which you can find [here](http://www.omdbapi.com/). The file is first stored as json and then later converted to a CSV file.
Feel free to clean and reinvent the data as you like. 

[I've removed my api key for safety purposes and used and env variable,so make sure you visit their website and get your own key]

##Caution
Before performing any sort of web scraping project, make sure you read the robots.txt file of that webpage to make sure you follow the guidelines specified otherwise there's a chance of getting blocked by the website.

