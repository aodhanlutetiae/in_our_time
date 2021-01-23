Collection and analysis of information about the BBC Radio 4 programme [In Our Time](https://www.bbc.co.uk/programmes/b006qykl), which has been running since 1998. The episode pages were scraped in Jan 2021 and an initial dataset established with the following variables:

- subject: title of episode
- summary: textual summary of what the episode is about
- date_str: date as a string, in a human-readable european format: dd-mm-yyyy
- featured_in_tags: a list of subject tags for a given episode
- address: url for the episode's webpage
- date_dt: date as a datetime object: yyyy-mm-dd
- day: day of the week the programme aired

This repo includes the following files:

- JSON file with a list of all the episode URLs scraped (url_list_932.json)
- jupyter notebook for scraping and cleaning of the data (IOT scraping and wrangling episode data 2301.ipynb)
- CSV with the above data (876, 7) (iot_halfclean.csv)
- jupyter notebook for analysis of the data ('IOT analysis.ipynb')

A second stage of wrangling remains to be done to get the information about the guests out of the original scraped data.
