This Project Is All About Time Series Data 

PROBLEM STATEMENT:
Given an IPL Dataset, can u predict the scores of the IPL team Currently Playing. The Dataset Has Following Cols:
* mid - match id
* date - when matches are played
* venue - place where matches aew played
* bat_team - batting team
* bowl_team - bowling team
* batsman - batsman
* bowler - bowler
* runs - runs scored
* wickets - wickets
* overs - overs - next 3 are based on this
* run_last_5 - runs scored in last 5 overs
* wicket_last_5 - wickets in last 5 overs
* stricker - batsman playing as main 1
* non-striker - batsman playing as runner up - not main 0
* total - total score (target variable)


PACKAGES USED:
* Pandas - For data handling and manipulation
* Scikit Learn - For model and algorithms
* Jupyter - Working IDE


FILES:
* IPL Score Prediction Using Simple Linear Regression.ipynb - Main File With Code
* ipl.csv - Dataset Used
* ipl_score_predict_model.pkl - Model File , Can Be Pickled
