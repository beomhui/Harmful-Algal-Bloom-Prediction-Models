### Integrated prediction of harmful algal bloom using CNN deep learning technology

This repository contains the code from the paper "Integrated prediction of harmful algal bloom using CNN deep learning technology", by Donghyun Lee, Beomhui Lee, Sangwon Chae, Sungjun Kwon.
In order to make this code run you will have to download and install the neural networks we have considered.

<br />

> **Requirements**

* Python v3.6.10
* Keras v2.1.5

<br />

> **Data**

In this study, the eight types of water-quality data collected from water-quality monitoring stations operated by the National Institute of Environment Research in South Korea (http://www.koreawqi.go.kr/index_web.jsp) were used. In addition, the four types of weather data collected from the ASOSs operated by the Korea Meteorological Administration (https://data.kma.go.kr/data/grnd/selectAsosRltmList.do) were used. The missing values of data used in the analysis were interpolated by Kalman filter and weather data at the locations of the water-quality monitoring stations were interpolated by IDW interpolation.

<br />

> **Chlorophyll-a integrated prediction model**

`Chlorophyll-a integrated prediction model.ipynb` creates and trains the integrated prediction model applied a total of eight time-steps. In addition, `Predict chlorophyll-a concentration.ipynb` generates graphs for the prediction and observed values of 29 water-quality monitoring stations. Moreover, `Comparison model.ipynb` creates and trains the LSTM model for comparison. 

<br />

> **Result**

![Figure 4-1](https://user-images.githubusercontent.com/77565332/131963393-8be79613-7310-4e3b-9838-a98e37c708ed.png)
Visualized predictions for each monitoring station made by the chlorophyll-a integrated prediction model. Map image is obtained from OpenStreetMap (openstreetmap.org) and licensed under CC-BY-SA (https://www.openstreetmap.org/copyright).


