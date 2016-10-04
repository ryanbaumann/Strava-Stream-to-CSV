# Strava-Stream-to-CSV
Python script to download Strava API stream data directly to a CSV

#Running
1. Install [Python 2.7.12](https://www.python.org/downloads/release/python-2712/)
2. `git clone git@github.com:ryanbaumann/Strava-Stream-to-CSV.git && cd Strava-Stream-to-CSV`
3. `'pip install -r requirements.txt`
4. Navigate to https://www.strava.com/settings/api#_=_, create and app, and get your API client ID and client secret.
5. Create a new file `client.secret` and populate it with `<clientID, client Secret>` all on the same line.
6. Open strava-to-csv.py as a text file.  Update the `limit` variable to download the number of activities that you want.
7. Run `python strava-to-csv.py`
8. Your data will be in the CSV file in the repo base directory.

Related blog post at 
https://ryanbaumann.com/blog/2015/4/6/strava-api-cycling-data-for-visualization
