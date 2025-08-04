# IMDB Movie Review Sentiment Analysis

A Streamlit app for IMDB movie review sentiment analysis using a pre-trained Simple RNN model. Enter a review and get instant classification (positive/negative) with prediction score. Includes data preprocessing and helper functions for user input.

## Features
- Sentiment prediction for movie reviews (positive/negative)
- Uses TensorFlow/Keras Simple RNN model
- Interactive Streamlit web interface

## Getting Started

1. **Install dependencies:**
   ```
   pip install -r requirements.txt
   ```

2. **Run the app:**
   ```
   streamlit run main.py
   ```

3. **Usage:**
   - Enter a movie review in the text area.
   - Click "Classify" to see the sentiment and prediction score.

## Files

- `main.py` – Streamlit app for prediction
- `requirements.txt` – Python dependencies
- `simple_rnn_imdb.h5` – Pre-trained model file

## Technologies

Python, TensorFlow, Keras, Streamlit

##