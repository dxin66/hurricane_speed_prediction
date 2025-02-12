# ML project-hurricane_speed_prediction
EDA data analysis、Tensorflow&lt;=2.11、data augmentation、CNN regression、ShuffleNet 

# project description
this project is run by tensorflow.
Its main is to predict hurricane speed prediction.
It uses four data strategies(Vanilla\Adding noise\Time Shifting\Conbined) and three regression model(CNN\ShuffleNet\ResNet).
Experiments shows that combined data augmentation strategies and ShuffleNet have the best performance.

# Dataset
dataset is provided by Kaggle community \url{https://www.kaggle.com/datasets/fedesoriano/wind-speed-prediction-dataset}.

# Evaluation Metrics
since this project is a regression project, MAE and MSE are choose to evaluate the model performance
