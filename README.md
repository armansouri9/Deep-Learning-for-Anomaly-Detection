# Deep Learning for Anomaly Detection

This repository contains an implementation of a deep learning model for anomaly detection. The model is based on LSTM (Long Short-Term Memory) and is designed to detect anomalies in time series data.

## Dataset

The dataset used for testing is a simple synthetic dataset. It consists of randomly generated data points with labels indicating whether they are anomalies or not.

## Code

The code consists of the following main components:

- `CustomDataset`: This class defines a custom dataset for training and testing the model.
- `LSTM`: This class defines the LSTM model architecture.
- `train`: This function performs the training of the model.
- `test`: This function performs the testing of the model.
- Main code: This section includes the necessary code for dataset creation, model initialization, loss function definition, optimizer selection, training, and anomaly detection.

## Usage

To use this code, follow these steps:

1. Clone the repository:

```
git clone https://github.com/armansouri9/Deep-Learning-for-Anomaly-Detection.git
```

2. Install the required dependencies (PyTorch, NumPy, and scikit-learn).

3. Run the code in your preferred Python environment.

## Results

After running the code, the model will be trained and tested on the provided dataset. The training and testing loss will be displayed for each epoch. Finally, the indices of detected anomalies will be printed along with the total number of data points and the count of anomalies in the test set.

Additionally, a scatter plot will be shown to visualize the original data and the detected anomalies.

## License

This project is licensed under a Free License.
