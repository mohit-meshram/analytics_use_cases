# Bike Sharing Case Study
> Program for building linear regression model for bike sharing case study


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Project involves building linear regression model for predicting bike users count for a bike rental company. The dataset used is the data set of company named BoomBikes. The project tries to create a model to predict the three dependent variables - casual user count, registered user count, total user count. Project tries to identify significant features in prediction of this variables


## Conclusions
- The model for the casual users count prediction is 
- casual =  (0.3148)*const + (-0.2394)*workingday + (0.498)*temp + (-0.2343)*hum + (-0.1923)*windspeed + (0.0969)*season_2 + (0.0611)*month_3 + (0.0618)*month_9 + (0.0954)*month_10 + (-0.0455)*weathersit_3
- The model for registered users count prediction is
- registered =  (0.3149)*const + (0.1603)*workingday + (0.582)*temp + (-0.3387)*hum + (-0.1918)*windspeed + (0.069)*season_2 + (0.1824)*season_4 + (0.1222)*month_9 + (0.0543)*weekday_6 + (-0.2211)*weathersit_3
- The model for total users count is 
- cnt =  (0.3682)*const + (0.045)*workingday + (0.677)*temp + (-0.3705)*hum + (-0.227)*windspeed + (0.0961)*season_2 + (0.1686)*season_4 + (0.1174)*month_9 + (0.0641)*weekday_6 + (-0.1994)*weathersit_3


## Technologies Used
- Python 3.9.6
- Pandas 1.3.4
- NumPy 1.21.3
- Matplotlib 3.4.3
- Seaborn 0.11.2
- Scikit-learn 1.0.1
- Statsmodel 0.13.1
- VS code
- Jupyter for VS code
- Microsoft Excel

## Contact
Created by [@mohit-meshram] - feel free to contact me!
