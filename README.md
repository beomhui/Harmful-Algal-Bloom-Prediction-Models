### Harmful Algal Bloom Prediction Models Using Convolutional Neural Network

This repository contains the code from the paper "Harmful Algal Bloom Prediction Models Using Convolutional Neural Network", by Donghyun Lee, Beomhui Lee, Sangwon Chae, Sungjun Kwon,  and Sungwon Kang.
In order to make this code run you will have to download and install the neural networks we have considered.

> **Requirements**

* Python v3.6.10
* Keras v2.1.5

> **Data**

In this study, the eight types of water-quality data collected from water-quality monitoring stations operated by the National Institute of Environment Research in South Korea (http://www.koreawqi.go.kr/index_web.jsp) were used. In addition, the four types of weather data collected from the ASOSs operated by the Korea Meteorological Administration (https://data.kma.go.kr/data/grnd/selectAsosRltmList.do) were used. The missing values of data used in the analysis were interpolated by Kalman filter and weather data at the locations of the water-quality monitoring stations were interpolated by IDW interpolation.

> **Chlorophyll-a integrated prediction model**

`Chlorophyll-a integrated prediction model.ipynb` creates and trains the integrated prediction model applied a total of eight time-steps. In addition, `Predict chlorophyll-a concentration.ipynb` generates graphs for the prediction and observed values of 29 water-quality monitoring stations. Moreover, `Comparison model.ipynb` creates and trains the LSTM model for comparison. 

> **Result**
![Figure 4-1](https://user-images.githubusercontent.com/77565332/131963393-8be79613-7310-4e3b-9838-a98e37c708ed.png)


