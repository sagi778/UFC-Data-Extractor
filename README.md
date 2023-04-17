# UFC Data Extractor
### Prerequisites:
 - Python 3
 - Pandas
 - Numpy
 - Beautiful soup
 - tqdm

### Description:
UFC Data Extractor is a Python script that makes it easy to gather and analyze data from the ufcstats.com. With this tool, you can extract data on fighters, events, and in-depth statistics, and save it to .csv files for further analysis.

### Installation:
1. Clone Or download a local copy
2. Run each .ipynb notebook

### Getting plan for extracting data:
Notebook: https://github.com/sagi778/UFC-Data-Extractor/tree/main/notebooks/updating_lists.ipynb
- Get [ufc_matches_stats.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/ufc_matches_stats.csv) last update time. 
- Get list of events out of [UFC website](http://www.ufcstats.com/statistics/events/completed) latter then last update time.


### Getting Fighters statistics:
Notebook: https://github.com/sagi778/web_scrapers_ufc_data/blob/main/notebooks/fighters_stats_web_scrape.ipynb
- Connecting to [ufc fighters list](http://www.ufcstats.com/statistics/fighters).
- Extracting data of each link(=fighter).
- Saving data to local path: ../data/ufc_fighters_stats.csv

### Getting Matches statistics:
Notebook: https://github.com/sagi778/web_scrapers_ufc_data/blob/main/notebooks/matches_stats_web_scraping.ipynb
- Connecting to [ufc events list](http://www.ufcstats.com/statistics/events/completed)
- Collecting events links.
- Collecting matches list from each event.
- converting each match to single data row.
- Stacking all rows to data set. 
- Saving data to local path: ../data/ufc_matches_stats.csv

### What Next?: 
Who will win? how?
- UFC Matches prediction: https://github.com/sagi778/ufc_fights_Predictor
