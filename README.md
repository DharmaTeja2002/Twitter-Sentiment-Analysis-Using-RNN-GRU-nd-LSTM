# 🧠 Twitter Sentiment Analysis Using RNN, GRU & LSTM

This repository provides a complete end-to-end deep learning pipeline for **Twitter Sentiment Analysis** using **Bidirectional RNN**, **GRU**, and **LSTM** models to classify tweets into **positive**, **neutral**, and **negative** sentiments.

---

## 🚀 What’s Inside?

1. **Data Preprocessing**
   - Tweets are cleaned, tokenized, and padded for input into deep learning models.

2. **Label Encoding**
   - Sentiment labels are converted into one-hot encoded vectors for multi-class classification.

3. **Model Architectures**
   - ✅ **Bidirectional RNN**  
     Captures both forward and backward context. Regularization included to reduce overfitting.  
     _Accuracy: ~89.1%_

   - ✅ **Bidirectional GRU**  
     Lighter and faster alternative to LSTM, captures sequential dependencies efficiently.  
     _Accuracy: ~90.2%_

   - ✅ **Bidirectional LSTM**  
     Excels in modeling long-term dependencies and improves performance significantly.  
     _Accuracy: ~92.0%_

4. **Training Setup**
   - Dropout, L2 regularization, and EarlyStopping to improve generalization and reduce overfitting.

5. **Evaluation Metrics**
   - Accuracy, Confusion Matrix, Classification Report for comprehensive model assessment.

6. **Visualization**
   - Training/validation loss and accuracy plots  
   - Confusion matrix heatmaps

---

## 📈 Why This Project Matters

Sentiment analysis is key to:
- Social media monitoring
- Customer service automation
- Product feedback analysis
- Brand reputation management

This project shows that even without transformers, **RNN-based models still rock** when tuned right. GRUs and LSTMs offer increasing accuracy with deeper memory modeling.

---

## 🛠️ Tools & Technologies

- **Programming Language**
  - Python 3.x

- **Deep Learning**
  - TensorFlow / Keras (Sequential API, Embedding, GRU, LSTM, RNN)

- **Model Utilities**
  - EarlyStopping (Keras callbacks)
  - Dropout & L2 Regularization
  - Bidirectional Layers

- **Data Preprocessing**
  - `nltk` (stopwords, tokenization)
  - `re` (regex for text cleaning)
  - `tensorflow.keras.preprocessing.text` (Tokenizer)
  - `tensorflow.keras.preprocessing.sequence` (pad_sequences)
  - `sklearn.preprocessing` (LabelEncoder, OneHotEncoder)

- **Evaluation**
  - `sklearn.metrics` (classification_report, confusion_matrix, accuracy_score)

- **Data Handling**
  - `NumPy`
  - `Pandas`

- **Visualization**
  - `Matplotlib`
  - `Seaborn`
---

## 🔍 Dataset

- **Source**: Kaggle  
  **Dataset**: Twitter Entity Sentiment Analysis  
  - Consists of tweets labeled as `positive`, `neutral`, or `negative`.
---

## 📦 How to Run

1. **Clone the Repo**
2. **Install Dependencies**
3. **Preprocess the Dataset**
4. **Train the Model**
5. **Evaluate the Model**
6. **Make Predictions on New Tweets**

---

## 📊 Model Accuracy Comparison

| Model          | Accuracy |
|----------------|----------|
| RNN            | ~89.1%   |
| **GRU**        | ~90.2%   |
| **LSTM**       | ~92.0%   |
