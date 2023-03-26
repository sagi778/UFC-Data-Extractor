# Web_scrapers for UFC data
### Prerequisites:
 - Python 3
 - Pandas
 - Numpy
 - Beautiful soup
 - multiprocessing
 - tqdm

### Getting Fighters statistics:
- Connecting to [ufc fighters list](http://www.ufcstats.com/statistics/fighters).
- Extracting data of each link(=fighter).
  - extracting data is done using multi-processing: using CPU number of cores - 2 (in order to allow enough cores for PC functions).
- Saving data to local path: ../data/ufc_fighters_stats.csv

### Getting Matches statistics:
- Connecting to [ufc events list](http://www.ufcstats.com/statistics/events/completed)
- Collecting events links.
- Collecting matches list from each event.
- converting each match to single data row.
  - extracting data is done using multi-processing: using CPU number of cores - 2 (in order to allow enough cores for PC functions).
- Stacking all rows to data set. 
- Saving data to local path: ../data/ufc_fighters_stats.csv
