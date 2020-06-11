# gmaps zurich covid19 mobility scrape

This data was collected during the lockdown in Switzerland during the first wave of the COVID-19 pandemic.
The repository contains CSV files based on the GMaps scraping job that ran from 2020.03.18 to 2020.06.11.

The source code of the scraping job is here: https://github.com/philshem/gmaps_popular_times_scraper/

Data is archived here for research purposes.
No data ownership is presumed based on the sharing of this data.


+ [metadata.csv](https://raw.githubusercontent.com/philshem/gmaps_zurich_covid19_mobility_scrape/master/metadata.csv) = listing of places being scraped. this can be joined to the timeseries below on the column "url" 

+ [all_current.csv](https://raw.githubusercontent.com/philshem/gmaps_zurich_covid19_mobility_scrape/master/all_current.csv) = only places with "current" and "normal" values (3.45 MB uncompressed)

+ all.csv --> [all.csv.tar.gz](https://github.com/philshem/gmaps_zurich_covid19_mobility_scrape/blob/master/all.csv.tar.gz?raw=true) = full scrape data (72.8 MB compressed, 1.39 GB uncompressed)

+ overview of data format: https://github.com/philshem/gmaps_popular_times_scraper/#results (note that scrape_time is in UTC)