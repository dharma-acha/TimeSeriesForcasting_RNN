## Time-Series Forecasting using RNN
### Overview
Time-series forecasting involves predicting future values based on previously observed values. In this project, we leverage Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) networks to perform time-series forecasting. The goal is to achieve an accuracy of more than 75% for the final model.

### Dataset

Retail Sales Dataset

### Steps


**1. Read and Preprocess:** Load the dataset, handle missing values, normalize the data, and print main statistics (e.g., mean, standard deviation).

**2. Visualization:** Create at least three visualizations (e.g., time-series plots, correlation heatmaps, seasonal decomposition) using libraries like matplotlib, seaborn, or plotly.

**3. Prepare Data:** Split the dataset into training, testing, and validation sets. Convert features to categorical values if necessary and normalize the data.

### Data Preprocessing:

* Handle missing values, normalize features, and split data into training, validation, and testing sets.
* Use techniques like Min-Max scaling or Z-score normalization.

### Build RNN Model

**Architecture:** Construct an RNN model with at least three RNN layers. You can use frameworks like TensorFlow or PyTorch.

**Training:** Train the RNN model with various setups and hyperparameters (e.g., learning rate, batch size). Aim to achieve the expected accuracy. Save the model weights that yield the best results.

### Model Building

* **Input Layer:** Prepare input sequences for the RNN.

* **RNN Layers:** Capture temporal dependencies in the data.

* **Dense Layer:** Output the final forecast value.

### Visualization

1. Plot the training and validation accuracy over epochs.
2. Plot the training and validation loss over epochs.
3. Generate a confusion matrix using the model's predictions on the test set.
4. Calculate and report evaluation metrics such as precision, recall, and F1 score using sklearn.metrics.precision_recall_fscore_support.


### Contact

If you have any questions or comments, feel free to contact me on [Email](mailto:achadharma333@gmail.com)


