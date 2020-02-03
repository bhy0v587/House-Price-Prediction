# House-Price-Prediction
This is a solution for Kaggle House Prices competition.

First of all, the competition is described as follows:

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/housesprices.png)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

After we download the data, we get such files: 

The train.csv and test.csv contains the training data and the data on which the testing on model is to be performed. 
The data_description.txt contains the description of the data.

I achieve two kinds of models to predict houses prices.

First one is using machine learning methods, by averaging and stacking models I achieved the score 0.11725 and ranked within top 18% on the leaderboard. The related code is in this file: Data_processing & prediction.ipynb.

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/rank.jpg)

The second one is to use deep learning to solve the problem, by optimizing hyperparameters I achieved the best score 0.12954. The related code is here: DL_prediction.ipynb. 

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/dl_result.jpg)
