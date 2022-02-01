# Dota 2 Win Chance Prediction - Patch 7.29

CS 6220 Project
By David Pan and Steniz Wahyudi
Northeastern University Summer 2021

## Description: 
Dota 2 is a game with 2 teams of 5 unique heroes (chosen from 121 heroes at the time) each where one team always wins (there are no draws). Therefore, normally each team's win chance would be around 50/50. Every version (patch) of the game, some heroes are stronger and some are weaker. In this project we are trying to see if it is possible to better predict which team would win based off of each teams 5 starting hero picks with no other information. 


## Project Goal: 
Predicting dota 2 win chance based on hero lineups and side.

Process:
  1. Data Mining - Get match data from OpenDota API
  2. Data Cleaning -  Drop unused columns, encode the hero lineups for analysis
  3. Modeling - Split the data into train and test models
  4. Analysis - Analyzed the data using Logistic Regression (chosen because of the speed and limited ability due to limited memory of the machine)

Result: Reached 56% accuracy score and AUROC score

Note: Data files are pretty big and unable to be uploaded here, send me a message to request them
