# web_scrapers_ufc_data

### about:
#### Getting fighters statistics:
- Connecting to [ufc fighters statistics](http://www.ufcstats.com/statistics/fighters).
- Extracting data of each link(=fighter).
  - extracting data is done using multi-processing: using CPU number of cores - 2 (in order to allow enough cores for PC functions).
- Saving data to local path: ../data/ufc_fighters_stats.csv
