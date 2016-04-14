
### Scraping Exercise

  * [MD Attorney General press releases](https://www.oag.state.md.us/Press/index.htm)
  * Fork [this repository](https://github.com/JOUR479K/first-web-scraper) to your GitHub account.
  * Clone it locally, then `cd first-web-scraper`
  * Next, create a new virtual environment: `mkvirtualenv scraper` or `virtualenv scraper` (if you do the latter, also do `source scraper/bin/activate`)
  * `pip install requests`
  * `pip install BeautifulSoup`

### Reading

  * [Public Info Doesn't Always Want to be Free](https://source.opennews.org/en-US/learning/public-info-doesnt-always-want-be-free/)

### Assignments

  * Scraping: using the `first-web-scraper` repository we worked on in class, replace the Maryland url with [this one](http://www.tdcj.state.tx.us/death_row/dr_scheduled_executions.html) and extract the upcoming Texas executions into a new CSV file named `executions.csv` (you'll need to replace the filename in the `scrape.py` file and change the headers, too, and you'll have to find the right HTML table to pull from).
  * Final Projects: Tell me your problems. Put a file called `problems.md` in your team's repository with any problems you've run into, in order of importance, and what you've tried to resolve them. Be prepared to discuss the top 2-3 in class.
  * Reading: [To Scrape, Perchance To Tweet](https://source.opennews.org/en-US/articles/scrape-perchance-tweet/)
