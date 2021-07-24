# [Forecasting Tool](https://forecast-generator.herokuapp.com/)

__Description:__ A web application to generate time-series forecasts on your dataset. 

Models supported include:
 * Autoregressive Integrated Moving Average (ARIMA) Time-Series Model
 * Facebook Prophet
 * Simple Moving Average (MA)

Provides user the ability to adjust the baseline forecast using the adjustment block available on the right. Up to 3 adjustments are supported currently. Annotations are added on the chart showing the adjustments made.

All these models have been built using Python. User interface is built using Dash and Plotly. Deployed on Heroku.

Build Log in Heroku: <br>

![build-log](https://user-images.githubusercontent.com/58986256/126865656-77b99d03-8dd1-4b40-8f96-7f8560063e64.png) <br>

Forecast Generator Dashboard: <br>

![forecast-generator-dashboard](https://user-images.githubusercontent.com/58986256/126865691-66694eb9-5d7b-490a-bd39-0e55658e1307.png) <br>

Temperature Forecast Using MA Model:

![temp-forecast-MAmodel](https://user-images.githubusercontent.com/58986256/126865750-bb1e7bce-42e6-4813-b8f6-c99726c3afa7.jpg)

Temperature Forecast Using ARIMA Model:

![temp-forecast-ARIMAmodel](https://user-images.githubusercontent.com/58986256/126865776-a6da1ebb-8666-4f37-a50c-3e196efa8e23.jpg)

Temperature Forecast Using Facebook Prophet Model:

![temp-forecast-FBProphetmodel](https://user-images.githubusercontent.com/58986256/126865805-44c7a3ae-af0b-426e-8ed3-c374f23e8cfa.jpg)
