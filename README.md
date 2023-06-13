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

### Getting plan for extracting data effeciently:
Notebook: https://github.com/sagi778/UFC-Data-Extractor/tree/main/notebooks/updating_lists.ipynb
- Get [ufc_matches_stats.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/ufc_matches_stats.csv) last update time (if not exist will extract all data). 
- Get list of events out of [UFC website](http://www.ufcstats.com/statistics/events/completed) latter then last update time & save it to [update_list_events.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/update_list_events.csv).
- Creating list of fighters who fought at [update_list_events.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/update_list_events.csv) & save it to [update_list_fighters.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/update_list_fighters.csv)

### Getting Matches statistics:
Notebook: https://github.com/sagi778/UFC-Data-Extractor/blob/main/notebooks/matches_stats_web_scraping.ipynb
- Get list of link of events for update [update_list_events.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/update_list_events.csv)
- Loop through link list & extracting data from each event & save it to [ufc_fighters_stats.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/ufc_fighters_stats.csv)

### Getting Fighters statistics:
Notebook: https://github.com/sagi778/UFC-Data-Extractor/blob/main/notebooks/fighters_stats_web_scrape.ipynb
- Get list of link of fighters which required update from [update_list_fighters.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/update_list_fighters.csv)
- Loop through link list & extracting data to [ufc_matches_stats.csv](https://github.com/sagi778/UFC-Data-Extractor/blob/main/data/ufc_matches_stats.csv)

### Getting Next Card matches:
Notebook: https://github.com/sagi778/UFC-Data-Extractor/blob/main/notebooks/upcoming_web_scrape.ipynb
- Extracting upcoming event fights [Next Cards](https://github.com/sagi778/UFC-Data-Extractor/blob/main/cards/)

### What Next?: 
Who will win? how?
- UFC Matches prediction: https://github.com/sagi778/ufc_fights_Predictor
