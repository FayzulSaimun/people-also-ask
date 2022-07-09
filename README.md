# paa-scraper
Scrape questions and their answer from google **people also ask**

This scraper is able to scrape any level's deep **PAA(people also ask)** question and their answer for any seed keywords.
By altering the level number, you may decide how deep you want the paa to go. 
Following scraping, you can group the questions groups with similar meaning. TF-IDF was employed by me for clustering.

Used **ThreadPoolExecutor** for scaling the process. You may need proxies in oder to scrape without blocking from google.
