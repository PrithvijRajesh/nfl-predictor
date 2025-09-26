NFLGDSC — NFL Prediction App

This project was originally developed as part of the Google Developer Student Club at The University of Texas at Dallas. Initial structure and outline provided by Sannidhya Tiwari.

Original repository: https://github.com/sannidhya09/NFLGDSC
Overview

The NFLGDSC app predicts player performance and game outcomes for upcoming NFL games. It uses both heuristic methods and regression models to give accurate predictions, while ensuring position-aware logic so predictions make sense for each player's role.

Features include:

--Win Probability Prediction

  Calculates the expected points for each team and the probability of each team winning.

  Takes into account team averages, opponent defensive strength, and home/away effects.

--Player Performance Prediction

  Predicts a player's stat (passing yards, rushing yards, receiving yards) or fantasy points.

  Position-aware: ensures predictions are valid for the player’s role (e.g., offensive linemen will not have passing yards).

Uses historical averages, team performance, and regression model outputs.

--Interactive UI with Streamlit

  Red & black theme for a bold, sports-focused aesthetic.

  Player selection with dropdown menus.

  Beautiful cards to display key stats for teams and players.

  Graphs and charts for team comparisons and predictions.

  Workshop-friendly: shows how data flows from API → processing → prediction → UI.

--Caching and Robustness

  API responses are cached to speed up repeated demos.

  Handles missing or incomplete data gracefully.