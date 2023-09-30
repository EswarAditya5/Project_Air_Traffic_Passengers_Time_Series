# Project_Air_Traffic_Passengers_Time_Series
## Time Series Analysis on San_Fransisco_Air_Traffic_Passengers_Time_Series


### Technology used:
<div align ='left'>
<img src ='https://technology.amis.nl/wp-content/uploads/2020/11/image_thumb-27.png', height = "50" alt = 'Jupyter'/><img width='12'/> 
<img src = 'https://cdn.dribbble.com/users/6569/screenshots/16471177/media/8bbfe7fd594073dc6271d5d852c7381a.png', height = "50" alt = 'Vs code'/><img width = '12'/>
<img src = 'https://thomasjpfan.github.io/data-umbrella-2020-streamlit-slides/images/streamlit.png', height = "50" alt = 'Streamlit'/><img width = '12'/>
<img src = 'https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png', height = "50 alt = 'Github'/><img width = '12'/>
<img src = 'https://img.uxwing.com/wp-content/themes/uxwing/download/brands-social-media/chatgpt-icon.png', height = "50" alt = 'ChatGPT'/><img width = '12'/>
</div>

### Overview
This project involves a thorough time series analysis of San Francisco air traffic statistics, with the objective of comprehending and predicting patterns in air traffic demand. Various time series analysis techniques, including ARIMA, Prophet, and Plotly for visualization, along with statistical tests such as ADFuller and KPSS for stationarity analysis, will be employed.

### Data
The dataset used in this analysis contains historical San Francisco air traffic statistics, including date and the total number of flights. This dataset serves as the foundation for the time series analysis.

### ARIMA Modeling
The Autoregressive Integrated Moving Average (ARIMA) model will be utilized to capture temporal patterns in the air traffic data. The ARIMA model entails differencing the data to establish stationarity, identifying the autoregressive (p), differencing (d), and moving average (q) parameters, and fitting the model. ARIMA aids in making short-term forecasts and uncovering trends and seasonality in air traffic demand.

### Prophet Modeling
In addition to ARIMA, the Prophet forecasting model, developed by Facebook, will be applied. Prophet is designed to handle time series data with prominent seasonal and holiday patterns. It automatically detects changepoints in the data and incorporates them into the forecast. This model offers flexibility and robustness in capturing time series patterns in San Francisco air traffic.

### Visualization with Plotly
Plotly, a powerful Python library for data visualization, will be harnessed to create interactive and informative visualizations of the air traffic data, model predictions, and forecasted trends. These visualizations enhance the understanding of the dataset and the performance of the models.

### Stationarity Analysis
To ensure the suitability of time series models like ARIMA and Prophet, stationarity analysis will be conducted. This involves using the Augmented Dickey-Fuller (ADF) test and Kwiatkowski-Phillips-Schmidt-Shin (KPSS) test. Stationarity is a fundamental assumption in time series analysis, and these tests assist in determining whether differencing is necessary to attain stationarity in the San Francisco air traffic data.

### Deployment with Streamlit
The time series analysis will be deployed using Streamlit, a Python library for creating web applications with ease. The Streamlit application will enable users to interact with the analysis, explore visualizations, and make predictions based on the developed models. Access the deployed application through this link: [Streamlit](https://project6airtrafficpassengerstimeseries-xz5lmq9fe9myo6j7ar2r9b.streamlit.app/)

### Conclusion
This project delivers a comprehensive time series analysis of San Francisco air traffic statistics. ARIMA and Prophet models are employed for forecasting, Plotly is used for visualization, and the analysis is deployed using Streamlit for an interactive web-based experience. Additionally, stationarity analysis is performed to validate the modeling approach. The insights derived from this analysis can be valuable for airlines, airport authorities, policymakers, and anyone interested in understanding and predicting air traffic demand in San Francisco.
Feel free to explore the code, findings, and the Streamlit app in this repository to gain a deeper understanding of the analysis and the methods I used. If you have any questions or feedback, please don't hesitate to reach out.

Thank you for visiting this project!

**Author:** Eswar Aditya
**Contact:** eswaraditya63@gmail.com

<!--
https://github.com/Makorg123/Project6_Air_Traffic_Passengers_Time_Series/assets/84630559/24bb9480-3419-4f8d-8011-c7afe668a147
-->
