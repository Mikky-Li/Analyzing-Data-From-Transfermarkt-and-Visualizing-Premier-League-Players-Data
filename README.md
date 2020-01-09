# Scraping-data-from-Transfermarkt.de-and-Visualizing-Premier-League-Players-Data
In this project, I:
1. Scrap Premier League players data from Transfermarkt, which is a German-based website that has footballing information, such as scores, results, statistics, transfer news, and fixtures. Columns include Name, Jersey Number, Age, Borned date, Club and Position using Beautiful Soup package, which is designed for parsing HTML documents. 
2. Perform Data cleansing by transforming some variables (Player Value, Age) from string to numeric.
3. Visualize Data

However, one biggest limitation for this project is that I cannot scrap nationality. Some players have dual citizenship so Beautiful Soup cannot identify which country should be parsed so it has to parse both. This causes wrong parsing in the end as the number of countries is definitely larger than the number of players. So I decided to seek other ways to identify players nationality, such as Wikipedia API. I will update the Jupyter Notebook once I figured out how to parse the nationalities in a correct way. 
