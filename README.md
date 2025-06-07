# Twitter-Sentiment-Analysis-Using-RNN-and-LSTM
This repo contains a complete end-to-end pipeline for Twitter Sentiment Analysis leveraging deep learning models — specifically Bidirectional RNN and LSTM architectures — to classify tweets into positive, neutral, and negative sentiments.

🚀 What’s Inside?
Data Preprocessing: Clean, tokenize, and pad tweets for efficient input into neural networks.

Label Encoding: Converting categorical sentiments into machine-readable formats with one-hot encoding.

Model Architectures:

Bidirectional Simple RNN: Captures context from both past and future tokens with regularization techniques to minimize overfitting.

LSTM Model: Enhanced sequence learning using LSTM layers to improve long-term dependencies and accuracy.

Training Setup: Early stopping callbacks to prevent overfitting and ensure optimal model performance.

Evaluation: Detailed accuracy and loss tracking on both validation and test sets, achieving strong performance:

RNN: ~89% accuracy

LSTM: ~92% accuracy — clear proof that memory helps!

Performance Visualization: Includes confusion matrices and classification reports for deep insights into model strengths and weaknesses.

📈 Why This Matters?
Sentiment analysis is a cornerstone of modern NLP applications — from brand monitoring to social media analytics and customer feedback analysis. This project demonstrates how classic recurrent networks can still pack a punch when tuned right, while LSTMs elevate the performance by understanding sequence context better.

🛠️ Tools & Technologies
Python, TensorFlow/Keras

Scikit-learn for preprocessing and evaluation

Pandas, NumPy for data handling

Matplotlib & Seaborn for visualizations

🔍 Dataset
Sourced from Kaggle: Twitter Entity Sentiment Analysis

How to Run
Clone the repo

Install dependencies

Prepare your dataset with preprocessing steps

Train the models (RNN or LSTM)

Evaluate on test data

Explore insights and tweak hyperparameters to improve performance

