Twitter Sentiment Analysis Using RNN, GRU & LSTM -

This repository contains a complete end-to-end deep learning pipeline for Twitter Sentiment Analysis, using powerful recurrent architectures like Bidirectional RNN, GRU, and LSTM to classify tweets into positive, neutral, and negative sentiments.

What’s Inside?
1. Data Preprocessing - Clean, tokenize, and pad raw tweets to make them digestible for neural networks.
2. Label Encoding - Sentiments are one-hot encoded for multiclass classification (positive/neutral/negative).

Model Architectures:
1. Bidirectional Simple RNN - 
Captures context from both past and future words with regularization to reduce overfitting.
Accuracy: ~89%

2. Bidirectional GRU - 
Combines performance with efficiency, great for capturing sequence dependencies without being too heavy.
Accuracy: ~90.2%

3. Bidirectional LSTM -
The memory wizard. Handles long-term dependencies like a champ, leading to the best performance.
Accuracy: ~92%

Training Setup:
1. Includes early stopping callbacks and dropout layers to control overfitting.
2. Fine-tuned architectures with L2 regularization and proper batch sizes.

Evaluation Metrics:
1. Accuracy, confusion matrices, and classification reports to give a clear picture of model performance.

Visualization:
1. Loss and accuracy plots across epochs
2. Heatmaps for confusion matrices

Why This Project Matters ?
Sentiment analysis is the backbone of:
1. Social media monitoring 
2. Customer feedback systems 
3. Brand and reputation management 

This project shows how classic RNNs, efficient GRUs, and powerful LSTMs can turn noisy tweet data into meaningful insights — even without transformer-level complexity.

Tools & Technologies:
1. Python, TensorFlow / Keras
2. Scikit-learn for preprocessing and metrics
3. NumPy, Pandas for data wrangling
4. Matplotlib, Seaborn for visualizations

