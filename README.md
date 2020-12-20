# da_project
This work has been created to showcase what we have learned this module 

 Initial part of the project has been performed by my collegue Dawson and consists of scraping number of youtube views for top 10 most popular pokemon youtubers (socialbladescrape.ipynb)
 
 This is a secondary part of the project consists of 3 notebooks, i.e. pokemon_scraping.ipynb, analysis_prep.ipynb, and analysis.ipynb.

pokemon_scraping.ipynb scrapes historical data for top 100 pokemon cards sold from https://pokemonprices.com/top_100 for 2019 and 2020. Items obtained are card names as well as card rarity numbers. Those variables are accompanied by dates collected and prices of pokemon cards on those dates. 

analysis_prep.ipynb is where additional data cleaning is performed. Moreover, pokemon data is modified to obtain average prices for each pokemon card (grouped by name and unique_id, i.e. rarity number) and is joined with youtube views to later obtain insight on how youtube views might affect the pokemon cards prices. 

finally, in analysis.ipynb, statistical analysis is performed. 
