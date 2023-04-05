# Web_scrapers for UFC data
### Prerequisites:
 - Python 3
 - Pandas
 - Numpy
 - Beautiful soup
 - multiprocessing
 - tqdm

### Installation:
1. Clone Or download a local copy
2. Run each .ipynb notebook

### Getting Fighters statistics:
Notebook: https://github.com/sagi778/web_scrapers_ufc_data/blob/main/notebooks/fighters_stats_web_scrape.ipynb
- Connecting to [ufc fighters list](http://www.ufcstats.com/statistics/fighters).
- Extracting data of each link(=fighter).
- Saving data to local path: ../data/ufc_fighters_stats.csv

### Getting Matches statistics:
- Connecting to [ufc events list](http://www.ufcstats.com/statistics/events/completed)
- Collecting events links.
- Collecting matches list from each event.
- converting each match to single data row.
- Stacking all rows to data set. 
- Saving data to local path: ../data/ufc_fighters_stats.csv

### Next: UFC Matches prediction:
- https://github.com/sagi778/ufc_fights_Predictor
