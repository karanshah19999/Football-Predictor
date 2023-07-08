# Football-Predictor Summary
Using a poisson distribution a football predictor was used to predict the goals scored and score of a match

#Implementation
•	Imported the data for all 35 game weeks played by the 20 teams into excel.
•	Created two models marked as “Goals model” and “Expected Goals model” which included data such as matches played, wins, losses, draws, Goals Scored, Goals Against and Points.
•	Both models included two separate tables to indicate home games and away games.
•	Created a Poisson distribution to predict the number of goals scored per game by factoring in Home form and Away form.
•	Created an over and under odds table which may be used for betting.
•	Using the Poisson distribution created a table to indicate the most likely scoreline of each game.
•	At this point in time, only 32 games had been played.
•	By cumulatively back testing from Game Week 1 to the current Game Week (32) at that point in time and furthermore forward testing for the last 3 Game Weeks we achieved an accuracy score of 58.2% in the Goals model and 60.7% score in the XG model.
