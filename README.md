# Fertilization Prediction Forecast
This project utilizes time-series data from soil sensors to predict soil fertilization levels. Part of the dataset used has been made publicly available via Mendeley Data under DOI: http://doi.org/10.17632/87stbx334b.1. Additionally, a preliminary statistical analysis of this dataset has been published in Smart Agricultural Technology under the title "A Novel Dataset for Wireless Soil Monitoring of a Strawberry Harvest and Respective Evaluation of Physicochemical Qualities", with DOI: http://dx.doi.org/10.1016/j.atech.2022.100055.

The code provided implements a custom function for plotting and stacking data, which is then used to build and evaluate three regression models: Linear Regression, Ridge Regression, and LSTM (Long Short-Term Memory) networks.

The results presented in the figure below illustrate a comparison of the three models' performance in predicting soil fertilization levels during the first quarter of the season:
![image](https://github.com/user-attachments/assets/6d7cbd58-acfe-40b2-bf83-acfac49aaee7)
