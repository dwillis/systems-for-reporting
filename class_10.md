
#### Working with local CSV file

  1. Download [this CSV file](https://raw.githubusercontent.com/dwillis/smpa3193-exercises/master/baby_names_nyc.csv) to your class folder inside your Desktop folder.
  2. Open Terminal and start up a Python session by typing `python`
  3. Let's import the tool we'll need to read in a CSV file: Python's [csv module](https://docs.python.org/2/library/csv.html), open the CSV file and then print out each row:
  ```python
  import csv
  file = open('baby_names_nyc.csv')
  csv_data = csv.reader(file)
  for row in csv_data:
    print row
  ```

  4. Try the last two lines again.
  5. Let's loop through again, printing out just those rows where the name is "IRENE"

#### Local Setup

Exit Python using Control-D and in the same directory, do the following commands from the command-line:

  * `pip install virtualenvwrapper`
  * `mkvirtualenv exercises`
  * `pip install urllib3[secure] pyopenssl ndg-httpsclient pyasn1 requests`

#### Working with an online CSV file

  Exit the Python session using Control-D and let's setup what we need to grab a file from the Web, including the library that handles [making web requests](http://docs.python-requests.org/en/master/). Copy the following command:

  `pip install urllib3[secure] pyopenssl ndg-httpsclient pyasn1 requests`

  Then type `python` to start a new session:

  ```python
  import csv
  import requests
  url = "https://raw.githubusercontent.com/dwillis/smpa3193-exercises/master/baby_names_nyc.csv"
  r = requests.get(url)
  csv_data = csv.reader(r.text)
  for row in csv_data:
    print row
  ```

  Now let's do it again, trying to isolate on "ELIJAH".

#### Agate Walkthrough


#### Assignments for Feb. 21

  * Described [here](https://github.com/SMPA3193/python)
