# [911 calls Forecast System](http://www.911forecast.site)
During my Insight Data Science project I developed an application to improve emergency response by forecasting 911 calls (http://www.911forecast.site). In particular I focused on medical emergency and used a dataset of 911 calls streamed in real-time from Montogmery Country, PA (http://montcoalert.org/gettingdata/)).

The web app was developed in Flask. The time-series model was developed in python by using sklearn toolkit and included in  insightmodel.py

# System architecture
<img src="sys_architecture.png" alt="">



<img src="img_1.png" alt="">



<img src="img_2.png" alt="">

## [Data layer] (emsmodule_data_exploration_2.ipynb)
This class was developped to create an abstraction layer on top of the DB.

## [Maps layer](emsmodule_maps.ipynb.ipynb)
This class was developped to determine the spatial distribution of the 911 calls and the Geo forecast probability distribution


