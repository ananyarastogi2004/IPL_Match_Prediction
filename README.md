# IPL_Match_Prediction
The model predicts the IPL Second Inning Match Score using various algorithms like Linear Regression, Decision Tree 
Regression, Random Forest Regressor, Support Vector Machine, XGBoost, KNR and predicts the IPL Match Winning 
Probability using logistic regression and ANN algorithms.


IMPLEMENTATION OF THE GUI

The Graphical User Interface is developed for the machine learning models using the Streamlit application. For the backend of the site Python is used. All the input information necessary for the model for the prediction is provided to the model.

A. Score Prediction Model

The GUI requires at least five overs of the data to predict the score. The model requires the input data of the Batting team, Bowling team, Over, Runs, Wickets, Run Scored in the last five overs, Wickets fall in the last five overs to predict the score of the match, as shown in Fig.

![Score Predictor](Score_predictor.png)

We input the data as :

Batting team: Chennai Super Kings

Bowling team: Mumbai Indians

Current Over: 10.2

Current Runs: 74

Wickets Fallen: 3

Runs scored in Last 5 Overs: 32

Wickets taken in last 5 Overs: 1

Predicted Score Range: 130 to 136

The output we got from the model is not exactly the predicted output. So, to increase the accuracy of the model, we add and
subtract 3 to give the range of score as shown in Fig... So, our model works in the majority of the cases.

B. Probability Prediction Model

The GUI requires the batting team, bowling team, host city, target, current runs, overs completed, and wickets out data as input to predict the probability of the IPL match, as shown in Fig.

![Win Probability Predictor](IPL_win_predictor.png)

We input the data as:

Batting team: Chennai Super Kings

Bowling team: Mumbai Indians

Host City: Mumbai

Target: 134

Score: 74

Overs Completed: 10.20

Wickets Out : 3

The output we get is:

Chennai Super Kings - 87%

Mumbai Indians - 13%

The chances of CSK winning the match is predicted by the model as 87%, and MI is 13 %
