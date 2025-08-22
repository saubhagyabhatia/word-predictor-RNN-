#🧠 Word Predictor using RNN (PyTorch)

A simple yet powerful Recurrent Neural Network (RNN) model built with PyTorch to predict answers to questions based on text input.
Achieved an impressive 95.54% accuracy 🎯.
🚀 Features

Preprocessing pipeline: tokenization, vocabulary building, handling <UNK> tokens

Implemented custom RNN model in PyTorch

Trains on a dataset of questions & answers

Predicts answers to unseen questions

⚙️ How It Works

Text Preprocessing

Tokenization

Vocabulary building

Handling unknown words with <UNK>

Model Architecture

Embedding layer

SimpleRNN → Fully connected layer

Softmax for prediction

Training

Loss: CrossEntropyLoss

Optimizer: Adam

Accuracy achieved: 95.54%

📊 Results

Training Accuracy: 95.65%

Model successfully predicts correct answers to most questions

🔮 Future Improvements

Replace RNN with LSTM/GRU for better handling of long dependencies

Experiment with Attention Mechanisms

Train on larger, more diverse datasets

🛠️ Tech Stack

Python 🐍

PyTorch 🔥

Pandas, NumPy
