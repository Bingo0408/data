# data_repo
This project is for data science purpose, which provides a repo for data

To add/update this repo, you may follow below steps

1. init repo if you are new for it
  + git init

2. add updated file
  + git add .

3. commit update with comments
  + git commit -m "add data file into repo"

4. add a shortname-"origin" for remote repo
  + git remote add origin https://github.com/Bingo0408/data_repo.git

5. push your update to remote server
  + git push -u origin master

# read csv python code
```python
git_repo = "https://raw.githubusercontent.com/Bingo0408/data_repo/master/%s"

prsa = pd.read_csv(git_repo % "PRSA_data.csv")
passengers = pd.read_csv(git_repo % "international-airline-passengers.csv")

airline_delays = pd.read_csv(git_repo % "AirlineDelays.csv")
cars = pd.read_csv(git_repo % "cars.csv")
top_2000_games = pd.read_csv(git_repo % "BGG_Top_2000_Games.csv")
minard = pd.read_csv(git_repo % "minard.csv")
minard_cities = pd.read_csv(git_repo % "minard-cities.csv")
minard_temp = pd.read_csv(git_repo % "minard-temp.csv")
minard_troops = pd.read_csv(git_repo % "minard-troops.csv")
sample_nodes = pd.read_csv(git_repo % "sample_nodes.csv")
sample_edges = pd.read_csv(git_repo % "sample_edges.csv")
baseball = pd.read_csv(git_repo % "baseball.csv")
us_states = pd.read_csv(git_repo % "us_states.csv")
lesmis = pd.read_csv(git_repo % "LesMis-Connections.csv")
africa = pd.read_csv(git_repo % "africa.csv")

pandas = pd.read_csv(git_repo % "pandas.csv")
pollution = pd.read_csv(git_repo % "pollution.csv")

EURUSD1440 = pd.read_csv(git_repo % "EURUSD1440.csv")
EURUSD_2017 = pd.read_csv(git_repo % "EURUSD_2017.csv")

shampoo_sales = pd.read_csv(git_repo % "sales-of-shampoo-over-a-three-ye.csv")
whiskey = pd.read_csv(git_repo % "whiskey.csv")
```
