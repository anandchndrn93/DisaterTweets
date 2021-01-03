# Natural Language Processing with Disaster Tweets
code for Kaggle competitions: 'Natural Language Processing with Disaster Tweets' to Predict which Tweets are about real disasters and which ones are not. The model were trained then a few testing scenarios were executed to figure out bugs.

Tensorflow, Keras and Scikit-Learn libraries were used for training

3 different models LSTM,xgboost and SGD were trained. LSTM model out performed the other two and was able to achieve prediction with an accuracy of 0.79 on kaggles test data. How ever on testing, it was seen that consistency of LSTM model was slightly off. As for XGBoost and SGDClassifier simple quality analysis shows that even though predictions are consistent they fail to capture the meaning of texts. so even random chunks of strings gets classified as disaster tweets. we don't face this problem with LSTM. 

dataset : https://www.kaggle.com/c/nlp-getting-started/data

