# LOL-Predict-Game

1. Predict Based on Parameters
   - apikey.py (Enter your RIOT Api key here)
   - riot_collect_data.ipynb (Scipt to collect data and store into database based on different in-game parameters)
   - riot_matches.db (database made with sqlite to hold game data, 10 000+ entries, uncleaned data)
   - riot_predict_match.ipynb (incompete script to predict the outcome of a user's last ranked game)
   - riot_process_data.ipynb (script to read data from database, clean data, and create a neural network to predict game winner 80%~ accurate)
   - scrap data notebook.ipynb (scrap notebook to see data and test new scripts)

  
2. Predict with Gold Over Time
   - apikey.py (Enter your RIOT Api key here)
   - collect_data.ipynb (Scipt to collect data and store into database based on gold over time in a match)
   - matches.db (database made with sqlite to hold game data)
   - model_with_gold_only.ipynb (script to read data from database, clean data, and create a neural network to predict game winner 77%~ accurate)
   - read_data.ipynb (notebook to read database data and test scripts for formatting)
