---
layout: post
title: "2026 NHL Playoff Predictions"
date: 2026-04-08
category: blog
excerpt: "A dashboard using 500 simulations to predict NHL playoff probabilities, built with Python and Streamlit."
---


Quick project (~3 hours) building a dashboard to visualize the probability a NHL team will make it to the playoffs. These predictions are based off of 500 simulations of the remaining games in the season, and data is pulled each time the page loads.

The teams are evaluated based on season performance plus how well they performed in their last 10 games (hot streak). The teams go head to head and simulations are run 500 times to evaluate how many times the team qualifies for the playoffs.

Predictions generally match [MoneyPuck](https://moneypuck.com/predictions.htm). In the future, I plan to expand upon these types of projects with more advanced predictions for each game, but this was a fun start.

[View the NHL Playoff Predictions Dashboard](https://katebowie-nhl-dashboard.streamlit.app)
