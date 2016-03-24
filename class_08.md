
#### Exercise

  * Data Smells - [Fairfax arrests data](https://github.com/JOUR479K/agate_exercises)

#### Assignments

  * Python: Using the Fairfax arrests data, Agate and Jupyter notebook. Remember that after you restart the server with the `jupyter notebook` command from the terminal/command-line, you'll need to run the cells that contain code, starting with `import agate`, before you add/edit. Be sure to rename your notebook to your own first name or first initial/last name. Then do the following:
    - Group by charge descriptions like we did before, but instead of doing a Count of the charges, create a `median_age` for each charge description (the agate function is [Median](http://agate.readthedocs.org/en/1.3.0/cookbook/statistics.html?highlight=median#aggregate-statistics)). Then order by that calculated median age, with the highest age first.
    - It turns out that there *are* rows with no charge description - we just didn't look for them well enough! Using the method we used in class to locate rows with 'ALEX' in the address column, try to find how many rows where `Charge Descrip` is missing (tip: the Python term for no data is `None`, so try filtering for that). Save those rows to a new variable, like `missing`. Then can calculate the number of rows in missing using the `len` command like we did with the Alexandria records.

  When you are finished, quit the notebook server (Control-C or Control-V) and git add, commit and push the .ipynb file to Github. IMPORTANT: Before you push, remember to run `git pull origin master` first, then push. If git pull gives you an intermediate screen that you don't recognize, hit ESC, then the colon character followed by wq, and then Enter. As always, send questions my way.

  * Read about Jeremy Bowers' projects: [The Roberts Court's Surprising Move Leftward](http://www.nytimes.com/interactive/2015/06/23/upshot/the-roberts-courts-surprising-move-leftward.html),[NYT Docket](https://github.com/newsdev/nyt-docket) & [NFL Stats](https://github.com/jeremyjbowers/nfl-stats)
  * Projects: Peer Review (email forthcoming), and I'd like each group to present a brief (1-2 minute) update on your project work at the start of class on Wednesday. I won't be there, but it will give Jeremy a way to hear about what you're doing. Send me an email with your update.
