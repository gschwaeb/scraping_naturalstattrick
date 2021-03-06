# Scraping Data Tables from Natural Stat Trick Using Beautiful Soup

This repo contains the [jupyter notebook](https://github.com/gschwaeb/scraping_naturalstattrick/blob/main/scraping_natural_stat_trick_player.ipynb) used to scrape data from Natural Stat Trick.

In this notebook, I will be demonstrating how to grab data from tables on the website Natural Stat Trick. Natural Stat Trick is a website for getting standard and advanced NHL statistics. It is one of the more well known and frequently referenced sources of data in the NHL analytics world for writers and fans alike.

First, using the Beautiful Soup library, I'll go through the steps to scrape the html and convert the data to a Pandas DataFrame. Then, I'll show a convenient one liner that works for tables on Natural Stat Trick and will work for tables on other webpages depending on their complexity. Finally, a tip on altering the URL to change the parameters of the data you can get.

Associated blog post: https://gsstats.medium.com/scraping-data-tables-from-natural-stat-trick-using-beautiful-soup-3251191bc3e1

