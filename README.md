# Predict NCAA Tournament
Predict which team will win in each match in NCAA Division I Men's Basketball Tournament 

## Scraping
We will use 3 different dataset from 3 different website using webscraping method from 2010-2011 until 2018-2019 NCAA Regular Season. The scraping algorithm stored in  __Scraper__ folder. The dataset from scraping will be stored in __Data__ folder. Below are the brief explanation about the dataset :
- __Kenpom__ = Possession-based metrics calculated by Ken Pomeroy for each team in each year
- __Vegas__ = Vegas betting odds for each match
- __Teamrankings__ = 115 Team statistics for each team in each year

## Preprocessing Dataset
After we scrape all three dataset then we will combine them into one final dataset for modelling. First we will have to synchronize the team name format of all three dataset. We will be using __change_team_name.csv__ (Tweaked version of TeamSpellings.csv from Google Cloud & NCAA® ML Competition 2019-Men's Kaggle Competition) to do this



