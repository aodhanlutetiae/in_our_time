A github repository for analysis of the BBC Radio 4 programme 'In Our Time', which has been running since 1998. The episode pages were scraped in Jan 2020 and an initial dataset established with the following variables:

- subject: title of episode
- summary: textual summary of what the episode is about
- date_str: date as a string, in a human-readable european format: dd-mm-yyyy
- featured_in_tags: a list of subject tags for a given episode
- address: url for the episode's webpage
- date_dt: date as a datetime object: yyyy-mm-dd
- day: day of the week the programme aired

This repo contains:

- JSON file with a list of all the episode URLs scraped (url_list_932.json)
- jupyter notebook for scraping and cleaning of the data (IOT scraping and wrangling episode data 2301.ipynb)
- CSV with the above data (876, 7) (iot_halfclean.csv)
- jupyter notebook for analysis of the data ('IOT analysis.ipynb')
