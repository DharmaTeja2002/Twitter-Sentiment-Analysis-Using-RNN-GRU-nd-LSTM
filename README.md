# Twitter-Sentiment-Analysis-Using-RNN-and-LSTM
This repo contains a complete end-to-end pipeline for Twitter Sentiment Analysis leveraging deep learning models — specifically Bidirectional RNN and LSTM architectures — to classify tweets into positive, neutral, and negative sentiments.

🚀 What’s Inside?
1. Data Preprocessing: Clean, tokenize, and pad tweets for efficient input into neural networks.
2. Label Encoding: Converting categorical sentiments into machine-readable formats with one-hot encoding.

Model Architectures:
1. Bidirectional Simple RNN: Captures context from both past and future tokens with regularization techniques to minimize overfitting.
2. LSTM Model: Enhanced sequence learning using LSTM layers to improve long-term dependencies and accuracy.
3. Training Setup: Early stopping callbacks to prevent overfitting and ensure optimal model performance.
4. Evaluation: Detailed accuracy and loss tracking on both validation and test sets, achieving strong performance:
         RNN: ~89% accuracy
         LSTM: ~92% accuracy — clear proof that memory helps!

5. Performance Visualization: Includes confusion matrices and classification reports for deep insights into model strengths and weaknesses.

📈 Why This Matters?
Sentiment analysis is a cornerstone of modern NLP applications — from brand monitoring to social media analytics and customer feedback analysis. This project demonstrates how classic recurrent networks can still pack a punch when tuned right, while LSTMs elevate the performance by understanding sequence context better.

🛠️ Tools & Technologies
1. Python, TensorFlow/Keras
2. Scikit-learn for preprocessing and evaluation
3. Pandas, NumPy for data handling
4. Matplotlib & Seaborn for visualizations

🔍 Dataset
Sourced from Kaggle: Twitter Entity Sentiment Analysis

How to Run:
1. Clone the repo
2. Install dependencies
3. Prepare your dataset with preprocessing steps
4. Train the models (RNN or LSTM)
5. Evaluate on test data
6. Explore insights and tweak hyperparameters to improve performance
