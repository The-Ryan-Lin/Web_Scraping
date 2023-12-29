# Web_Scraping

This folder contains previous work I have conducted on web scraping, mostly using beautiful soup. More information can be found for each of the exercises below: 

__1. Scraping Coronavirus Data:__ Scraping_Converting_Cleaning_COVID_data.ipynb

Utilising web scraping to gather the latest data on worldwide COVID-19 cases from the [Worldometers website's coronavirus information page](https://www.worldometers.info/coronavirus/'). The data includes Total cases, Total deaths, New cases, New deaths, Active cases, Serious, Critical, Total cases, Total recovered, and Newly recovered. 

__2. Scraping Movie Information from the British Film Board Classification Website:__ Web_Scraping_Exercise_Movie_Info_British_Film_Board.ipynb

Here, I created advanced user defined helper functions to scrape movie information items from the BBFCs website: </br>

a. __Scraping the recents page:__ By either finding each items corresponding 'h4' tag and its next sibling, or locating the correspinding 'div' element and extracting its text contents.
* 'Title', 'Rating Content', 'Synopsis', 'Classified Date', 'Language', 'Director(s)', 'Production Year', 'Release Date', 'Genre','Running Minutes' and 'Cast'
  
b.  __Scraping information from a predefined list of movie titles:__ Created a helper function to iterate through each movie title, fetch the URL for the movie, and then scrape the detailed information from that URL using the scrape_movie_info function.
* 'Title', 'URL', 'Type', 'Rating', 'Content', 'Synopsis', 'Classified Date', 'Language', 'Director', 'Production Year', 'Genre', 'Running Minutes', 'Cast', 'UK Age Rating'
  
__3. Scraping Largest Companies by Revenue:__ Web_scraping_with_beautiful_soup_Fin4Tomorrow_case_study.ipynb

In this exercise, I scrape the Wikipedia website - [List of largest companies by revenue (Wikipedia 2021)](https://en.wikipedia.org/wiki/List_of_largest_companies_by_revenue) to attain information on the worlds largest companies.
