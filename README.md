# World cup blackjack game

Created this repo to host some code used to run a World Cup Blackjack competition. The rules are as follows:

* Each player is randomly allocated 3 teams.
* The winner has combined goals closest to 21 without going bust.

There are a couple of notebooks to help set this up:

* `generate_picks.ipynb` - Randomly allocate each player 3 teams, and output the result as `df_players_picks.csv`. Run this once when the game begins and push the csv to the repo.
* `get_goals_for_picks.ipynb` - Setup to pull the total goals for each player automatically, render using Quarto, and deploy to GitHub Pages. 