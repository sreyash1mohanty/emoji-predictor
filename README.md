# Emoji Predictor Using Stacked LSTM

This project implements an Emoji Predictor using a stacked LSTM (Long Short-Term Memory) model. It utilizes pre-trained word embeddings from the GloVe 50B model for transfer learning in NLP to predict emojis based on text input. The dataset consists of 5 classes of emojis, and the model is trained with Keras.

## Features
- **Model**: Stacked LSTM for text classification
- **Pre-trained Embeddings**: GloVe 50B word embeddings used for transfer learning
- **Classes**: 5 emoji classes
- **Input**: Text data, which is preprocessed and converted into 3D vector format (X_train as 3D vectors)
- **Output**: Categorical emoji prediction
- **Evaluation**: The model is evaluated on the test set, achieving an accuracy of 62%.
- **Early Stopping**: Early callbacks used to improve model accuracy during training

