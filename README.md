# NIFTY index prediction
Trained LSTM models to predict the NIFTY index and performed hyperparameter tuning.
Scraped #nifty tweets between 2017-2022 to calculate sentiment and use it as a feature for our model.
Model did not perform well upon the addition of sentiment as a feature hence discarded this as a feature and saved previously trained model as the final model as a pickle file.
Created a Flask web-app to deploy the model to predict the next day's index price by feeding the live previous 80 days data scraped from https://finance.yahoo.com/ as input.

