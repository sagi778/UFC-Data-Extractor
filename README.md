# web_scrapers_ufc_data

### Getting Fighters statistics:
- Connecting to [ufc fighters](http://www.ufcstats.com/statistics/fighters).
- Extracting data of each link(=fighter).
  - extracting data is done using multi-processing: using CPU number of cores - 2 (in order to allow enough cores for PC functions).
- Saving data to local path: ../data/ufc_fighters_stats.csv

### Getting Matches statistics:
- Connecting to [ufc events]http://www.ufcstats.com/statistics/events/completed
- Extracting data of each link(=fighter).
  - extracting data is done using multi-processing: using CPU number of cores - 2 (in order to allow enough cores for PC functions).
- Saving data to local path: ../data/ufc_fighters_stats.csv
