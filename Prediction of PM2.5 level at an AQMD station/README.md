# Prediction of PM2.5 level at an AQMD station: using nearby stations' data
CSCI 5622's final project for Fall 2022 semester.

Team member: Jooseok Lee, Nitish Venkatesh Septankulam Ramakrishnan, Meghana Vasanth Shettigar

Build a forecasting machine learning model that predicts PM 2.5 level of a target station using nearby stations' air pollution data
<br>
<br>

# Overview
Predicting the level of particulate matter (PM2.5) is becoming increasingly crucial in the field of public health. For example, the United States Environmental Protection Agency (US EPA) designates particulate matter as an important source of air pollution. Accordingly, many air pollution observatory stations are set up to monitor the level of PM2.5. However, not every station is able to measure the level of PM2.5. For instance, only 13 of 30 stations in South Coast Air Quality Management District (AQMD) can monitor the level of PM2.5. In this project, we aim to develop a machine learning model that can predict the level of PM2.5 of stations that have no PM2.5 level monitoring capability. To achieve that, we build a machine learning model that predicts the PM2.5 level of a target station using PM2.5 level data of nearby stations. We also utilize other commonly monitored air pollution data, such as level of NO2 and CO, and basic meteorological data, such as wind direction and speed, to increase the performance of the model. The development direction is based on the assumption that the air quality of one station has a spatiotemporal correlation to the air quality of nearby stations.

# Keyword
Machine Learning, CNN, LSTM, XGBoost, PM2.5, Time-series, Forecast, Python, Keras, Sklearn

# Codes
- CSV_merger code can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/Data/csv_merger.ipynb)
- Preprocessing code can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/Preprocessing.ipynb)
- EDA code can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/EDA.ipynb)
- Model training & analysis code can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/Model%20Training%20%26%20Analysis.ipynb)

# Reports
- Project proposal can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/%5BProposal%5D%20Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station.pdf)
- Poster can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/%5BPoster%5D%20Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station.pdf)
- Final report can be found [here](https://github.com/jooseokLeeCU/ljsilverstar/blob/main/projects_CU/CSCI5622(Machine%20Learning)/Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station/%5BFinal%5D%20Prediction%20of%20PM2.5%20level%20at%20an%20AQMD%20station.pdf)
