# League of Legends Game Predictor

This is an Artificial Neural Network which analyzes 8000+ games of League of Legends and based on the chosen parameters is able to predict the outcome of a game with ~80% accuracy.

* apikey.py (enter your RIOT Api key here)
* riot_collect_data.ipynb (script to collect data and store into database based on different in-game parameters)
* riot_matches.db (database made with sqlite to hold game data, 10000+ entries, uncleaned data)
* riot_predict_match.ipynb (incomplete script to predict the outcome of a user's last ranked game)
* riot_process_data.ipynb (script to read data from database, clean data, and create a neural network to predict game winner ~80% accurate)
* scrap data notebook.ipynb (scrap notebook to see data and test new scripts)
