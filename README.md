# Baseball-Prediction-Project
A project I worked on last spring. My goal here was to try to create a tool to predict the winner of MLB baseball games.

The script takes in a CSV that I created via web scraping that has historical baseball game data, specifically ERAs and scores. I then used the elo rating rystem to generate ratings for the teams, updating after every game. Runnining the script scrapes more data about baseball games in the latest season, and gets up to date data. I trained a nueral net on the historical data to predict game scores based on elos and ERAs. The script then provides some statistics on the model's accuracy, and allows the user to input information about teams in order to get predictions for current game outcomes.

The second version (2.02) that I created later added the following new features:

  Preprocessing for increased nueral net accuracy

  The ability to save and reuse trained models

  Logistic regression on score predictions to provide implied probabilities for game outcomes

  Improved user interaction

  Kelly criterion calculations

The original script was in colab but I moved to Jupyter notebook for the second version which worked better. To run the newer script you will need to download the attached csv and then modify the file path on line 99. I'd definitely recommend using the 2.02 jupyter version over the colab one.

I'm interested in probabilities, risk and prediction and I took on this project primarily out of intellectual curiosity. I have used it to make predictions for fun but never to gamble my actual money and I would advise against doing so. I've found that its predictions are usually similar to the implied probabilities in betting lines except for when there is information like an injury that the model cannot integrate, meaning there's no real edge.
