### Reading

  * [Getting Data from the Web](http://datajournalismhandbook.org/1.0/en/getting_data_3.html)

### Scraping!

  * Fork [this repository](https://github.com/SMPA3193/first-web-scraper) to your GitHub account.
  * Clone it locally, then `cd first-web-scraper`
  * Next, create a new virtual environment: `mkvirtualenv scraper`
  * `pip install requests`
  * `pip install BeautifulSoup`

### Assignments

  * Scraping: using the `first-web-scraper` repository we worked on in class, copy the congress/scrape.py file into the crime folder. Open it in TextWrangler and replace the House url with [this one](http://www.tdcj.state.tx.us/death_row/dr_scheduled_executions.html) and then adjust the script to extract the upcoming Texas executions into a new CSV file named `executions.csv` (you'll need to replace the filename in the `scrape.py` file and change the headers, too, and you'll have to find the right HTML table to pull from). Not sure where to start? Try running the crime/scrape.py script. If you get an error, make a change to the line the error occurs on. Print out the row you're working with to see it.
  * Final Projects: Give me an update on what data source(s) you'd like to use in your project. Haven't decided? Let me know the candidates or any other issues. Put it all in a text file called `update_032317.txt` and push it to your Github group.
  * [Public Info Doesn't Always Want to be Free](https://source.opennews.org/en-US/learning/public-info-doesnt-always-want-be-free/)
