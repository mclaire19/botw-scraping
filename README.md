# botw-scraping
The [Writing Excuses podcast](https://writingexcuses.com/) is a weekly writing podcast hosted by writers in science fiction and fantasy; starting in season 7, they included recommendations for books to read each week that fit within the theme of the podcast or that the authors themselves just personally liked. 

This repo includes a Jupyter Notebook that scrapes book recommendations from seasons 7-12 from the Writing Excuses website, cleans them, and writes them into a csv. Two output CSVs are also included.

Some improvements to make this script more comprehensive could include:
- Using additional regular expressions to further clean the text (e.g. getting rid of commas and dealing with apostrophes)
- "Clicking" on the included audible links on each page to scrape additional book details
- Scraping recommendations for season 13 and 14, which are not posted in the main part of the Writing Excuses site.
