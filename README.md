# FIFA_19_predictions
Try to predict position zones and release clauses of players on basis of some attributes relating to the player


1> data.csv is the main dataset , containing all the informations with respect to the players

2> clean_dataset.ipynb was used to remove corrupted data within the csv file, removing NAN instances , redundant data etc, cleaned dataset was saved as clean_data.csv

3>data_visualization was used to visualize some statistics with regards to the data to gain some insights which might be helpful with regards to feature engineering later

4>preprocessing.ipynb was used for features generation, two techinques were tried out, mutual inforamtion and PCA, ultimately PCA was taken to be technique used for generating a new dataset on which models would be trained

5> model_on_numerical attributes was used to train a XGBoost Classifier for predicting player positions and XGBoost regressor was used for predicting release clauses for players

Results -I achieved about 86% accuracy for position prediction and mse error of 2 million euros for release clause prediction
