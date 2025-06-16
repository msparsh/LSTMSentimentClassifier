# LSTMSentimentClassifier

## Overview
This project implements a sentiment classifier using Long Short-Term Memory (LSTM) networks. It processes IMDB movie reviews to predict whether a review is positive or negative.

## Features
- Preprocessing of text data using TensorFlow's `TextVectorization` layer.
- Dynamic vocabulary size determination based on the dataset.
- LSTM-based neural network for sentiment classification.
- Early stopping to prevent overfitting during training.

## Requirements
The project requires the following Python packages:
- `tensorflow`
- `tensorflow-datasets`

Install the dependencies using:
```bash
pip install -r requirements.txt
```

## Usage
1. Clone the repository and navigate to the project directory.
2. Install the required dependencies using the command above.
3. Open the `LSTM.ipynb` notebook in Jupyter Notebook or any compatible IDE.
4. Run the cells sequentially to train the model and evaluate its performance.

## Dataset
The IMDB movie reviews dataset is used for training and testing. It is automatically downloaded using TensorFlow Datasets.

## Model Architecture
- **Embedding Layer**: Converts words into dense vector representations.
- **LSTM Layers**: Two stacked LSTM layers with dropout for regularization.
- **Dense Layer**: Outputs a single value with a sigmoid activation for binary classification.

## Results
The model achieves approximately 78% accuracy on the test dataset.

## License
This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.