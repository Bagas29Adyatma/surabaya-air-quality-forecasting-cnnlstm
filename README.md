## Public Demo Notebook

The file `air_quality_forecasting_lstm_cnn_lstm_public_demo.ipynb` is a public demonstration notebook created for portfolio purposes. It does not contain the original dataset from the Environmental Agency of Surabaya City due to a data-sharing agreement.

Instead, this notebook uses synthetic air quality data with a similar structure to demonstrate the main modeling workflow used in the thesis, including:

- synthetic air quality data generation
- data preprocessing
- Kalman smoothing
- normalization
- time series sequence generation
- LSTM model development
- CNN-LSTM model development
- model evaluation using MAE, RMSE, MAPE, and Index of Agreement
- 7-day forecasting demonstration

# Model Architecture

### LSTM Architecture

![LSTM Architecture](images/model_architecture_lstm.png)

The LSTM architecture consists of sequential LSTM layers, dropout regularization, fully connected layers, and an output layer for time series forecasting.

### CNN-LSTM Architecture

![CNN-LSTM Architecture](images/model_architecture_cnn_lstm.png)

The CNN-LSTM architecture combines convolutional layers for local temporal feature extraction and LSTM layers for sequential pattern learning, followed by dropout and fully connected layers for forecasting output generation.

This notebook is intended to show the methodology and technical implementation while maintaining data confidentiality.
