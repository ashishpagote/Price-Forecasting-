# Price-Forecasting-Real-Time-Visualisation-GSite

Created by: Ashish Murlidhar Pagote and Tianlu Lu

The market price of a product can change for many reasons. The relation of market supply and customer demand influences the price of a product most. Also, there are many other reasons, such as technology innovation, society stability or customer preference, can also affect the price of goods.
In this project, we find a dataset from Kaggle that contains the daily price of twenty-three different commodities from the year 2000 to the current year. These commodities vary from 6 categories, and they are energy, industrial metals, precious metals, grains, livestock and softs. All prices are quoted in Euros per unit weight.

We forecasted the price of 5 commodities using the Autoregressive Integrated Moving Average method. We performed differencing, ACF and PACF to get the parameters of the ARIMA model after cleaning and performing imputation on our data. We then analyzed our trained model by statistics generated in the Sarimax Result and ensured the assumptions while training the ARIMA model hold true. We then generated several performance metrics of our model on training and test data. Finally, we discussed a methodology to create and publish a live site that captures the predictions of our model.


