The model cleverly combines the classic Exponential Smoothing model (ES) and a Recurrent Neural Network (RNN)

- The ES decomposes the time series in level, trend and seasonality components.
- The RNN is trained with all the series, has shared parameters and it is used to learn common local trends among the series while the ES parameters are specific for each time series.

## what is forecasting?

## Exponential Smoothing model (ES)

The larger the value of the theta, the more the most recent observation is emphasized. The quicker the observation decay happens.

#### Simple exponential smoothing (SES)

- https://www.youtube.com/watch?v=i7Pyf1z_8XE

#### Simple exponential smoothing (SES)

- https://www.youtube.com/watch?v=Fqge2HDH2Co

![output](img/decreasing_weight.png)
