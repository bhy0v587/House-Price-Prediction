# House-Price-Prediction
This is a solution for Kaggle House Prices competition.

First of all, the competition is described as follows:

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/housesprices.png)

Ask a home buyer to describe their dream house, and they probably won't begin with the height of the basement ceiling or the proximity to an east-west railroad. But this playground competition's dataset proves that much more influences price negotiations than the number of bedrooms or a white-picket fence.

With 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, this competition challenges you to predict the final price of each home.

After downloading the data, we get such files: 

The train.csv and test.csv contains the training data and the data on which the testing on model is to be performed. 
The data_description.txt contains the description of the data.
The sample_submission.csv contains the sample csv data.

## Methods
- Visualization: analyze data distribution and relevance
- Feature engineering: drop outliers, add loss data and new properties, data transformation and vectorize non-numeric properties...
- Models seclection and Ensemble learning

### Requirements
- Python 3.7
- Numpy
- Pandas
- Matplotlib
- Seaborn
- Sklearn
- Torch 1.3.1 

## Results

I achieve two kinds of models to predict houses prices.

First one is using machine learning methods, by averaging and stacking models I achieved the score 0.11725 and ranked within top 18% on the leaderboard. The related code is in this file: Data_processing & prediction.ipynb.

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/Leaderboard_Rank.png)

The second one is to try using deep learning to solve the problem, by optimizing hyperparameters I achieved the best score 0.12954 which seems not well-performed. The related code is here: DL_prediction.ipynb. 

![alt text](https://github.com/bhy0v587/House-Price-Prediction/blob/master/image/DL_Result.png)

## Analysis and Improvement
- Deeper feature engineering
- Take more time tuning models for global optimal solution
- Underutilize visualization packages (matplotlib, seaborn...)
- Try more model ensemble methods with different models and find teammates


