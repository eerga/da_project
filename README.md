## The popularity secret behind Pokémon card resale market

### Goal
Our Data Analytics team assessed the influence of Pokémon YouTubers on Pokémon card resale. Our **hypothesis** was: the higher the YouYube views are, the higher the resale rate of Pokémon cards is. We web scraped historical data of Pokémon card prices and top 10 Pokémon YouTubers’ views, using Wayback Machine and Python </br>

### Notebook description
 Initial part of the project has been performed by my collegue Dawson and consists of scraping the number of YouYube views for top 10 most popular Pokémon YouTubers from [SocialBlade](socialblade.com) (*socialbladescrape.ipynb*). The packages we used are *Chromedrive* and *BeautifulSoup*.
 
 Second part of the project consists of 3 notebooks, i.e. *pokemon_scraping.ipynb*, *analysis_prep.ipynb*, and *analysis.ipynb*.

1. *pokemon_scraping.ipynb* **scrapes** historical data for **top 100 pokemon cards** sold from [here](https://pokemonprices.com/top_100) for 2019 and 2020. Items obtained are card names and card rarity numbers. Those two variables are accompanied by dates collected and prices of pokemon cards on those dates. 

2. analysis_prep.ipynb is where additional data cleaning is performed. Moreover, Pokémon data was modified to obtain average prices for each Pokémon card (grouped by name and unique_id, i.e. rarity number) and is joined with YouTube views to later obtain insight on how YouTube views might affect the Pokémon cards prices. 

3. In analysis.ipynb, statistical analysis is performed and appropriate conclusions are made.

### Project Conclusion
After conductig statistical analysis and building a descriptive model, we concluded that YouTube views solely cannot explain an increased popularity in Pokémon card resale and other features should be incorporated into the study.
