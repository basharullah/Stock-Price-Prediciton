# Stock-Price-Prediciton

This project is to implement Stacked LSTM and NeuralProphet built with PyTorch to predict stock prices using time series forecasting.

## Visualizing Results

- Stacked LSTM
![image](https://github.com/basharullah/Stock-Price-Prediciton/assets/84793175/3a59bb60-8ca0-427d-80ab-6e9b73f96d30)

RMSE for Training Data: 21.365121039720137
RMSE for Test Data: 87.65722205877714

- Neural Prophet
![image](https://github.com/basharullah/Stock-Price-Prediciton/assets/84793175/99a3d904-4f13-4132-b411-e9eb42287546)

RMSE for Training Data: 1.3481472663070373
RMSE for Test Data: 36.35974877025983

## Conclusion

The significantly lower RMSE values obtained by NeuralProphet compared to Stacked LSTM indicate that NeuralProphet outperforms the Stacked LSTM model in terms of predictive accuracy on both the training and test datasets. This suggests that NeuralProphet may be a more suitable choice for time series forecasting tasks, offering better performance with less complexity in model architecture and tuning.



