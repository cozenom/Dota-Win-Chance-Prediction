# Dota Win Chance Prediction - Patch 7.29

CS 6220 Project
By David Pan and Steniz Wahyudi
Northeastern University Summer 2021

Project Goal: Predicting dota 2 win chance based on hero lineups and side.

Process:
  1. Data Mining - Get match data from OpenDota API
  2. Data Cleaning -  Drop unused columns, encode the hero lineups for analysis
  3. Modeling - Split the data into train and test models
  4. Analysis - Analyzed the data using Logistic Regression (chosen because of the speed and limited ability due to limited memory of the machine)

Result: Reached 56% accuracy score and AUROC score
