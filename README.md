# Wine-Prediction
Supervisied model to predict Wine based on its location and user Reviews !
I have uploaded 2 notebooks :- 1. EDA-wine and 2. Preprocess and modelling .

I used supervisied models to predict Wine based on its location and user Reviews !

I used F1-micro as performance metric for our multiclass - classification problem !

Features Used - ['user_name', 'country', 'review_description', 'designation', 'points', 'price', 'province', 'region_1', 'winery', 'variety' ] Basically all feature except Review_title and Region_2 .

Model Used and its Accuracy on CV ( Split on train ) :-
Dummy KNN - F1 - 0.53
Random Forest - F1 Score - 0.79
XGB - F1 Score - 0.747
So , For test label prediction I used Random Forest.

I have attached the 'test with preds.csv' which has 'pred_variety' and all features that I used in my model.

Note : This test csv file has sorted rows by country so will look diffrent from original test as rows are inter-changed.
I also attached 'Final_train.csv' with all processed features used.

Top Insights from Data Analysis : -
Chardonay and white wines are the best rated among all price range.
Germany and France produces the best cheap wines.
Portugal's Costliest wines are extremely high rated among other countries' wines.
Cramele Winery Produces most amount of Cheap wines.
Williams Selyem winery produces the highest no. of best rated wines.¶
See the Visualization On EDA notebook !
