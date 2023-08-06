# Stock-Prediction-Model
It is a model to predict the close data/value of any asset from yfinance

Machine learning has always interested me, so I decided to widen my scope of knowledge, theoretically and practically.

I downloaded Live Stock data on Gold from https://finance.yahoo.com/. I extracted data from 2008 to the present year 2023.

I built a Stock prediction model that will predict the Close data/value of any Stock asset. All the user has to do is enter the Ticker code of the asset (e.g. Gold GC=F) and It will download the dataset in a data frame using the Pandas library.

As stated before, I downloaded the data on Gold and parsed it to a data frame using the Pandas library. I ran an exploratory analysis on the Open and Close values/data of Gold from 2008 - 2023 using visualization with the Matplotlib and Seaborn libraries of Python.

I divided this dataset into two variables using the first, Date, and Open values/data to train the model as input values(Feature), and using the Close values/models to also train the model but as my output values(Target).

I trained and fitted the model using the Sklearn library, and used the Linear Regression model to run predictions from what the model has been trained on, which on inputting any Open value/data of an asset (Gold in this project), will predict the close value.

Well, Python is an awesome language and this can be done in not too many lines of code. After achieving my predicted values, I tested the perfection of my predictions using the r2 score library (how accurate they were).


I then used the Lasso and Ridge libraries to check underfitting and overfitting and lastly using the joblib library to save my model.



