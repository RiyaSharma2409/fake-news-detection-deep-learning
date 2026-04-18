# 📰 Fake News Detection using Deep Learning

## 🚀 Overview
This project focuses on detecting fake news using deep learning techniques.

We compare two sequence models:
- LSTM
- Bidirectional LSTM (BiLSTM)

The goal is to classify news articles as **real or fake** based on textual content.

---

## 📊 Dataset
- Source: Kaggle Fake News Dataset :contentReference[oaicite:0]{index=0}  
- Features:
  - Title  
  - Author  
  - Text  
- Target:
  - 0 → Real News  
  - 1 → Fake News  

---

## ⚙️ Approach

### 🔹 Data Preprocessing
- Handling missing values  
- Text cleaning  
- Tokenization  
- One-hot encoding  
- Padding sequences  

---

## 🧠 Models Used

### 🔹 LSTM (Long Short-Term Memory)
- Captures sequential dependencies in text  
- Handles long-term context  

---

### 🔹 Bidirectional LSTM (BiLSTM)
- Processes text in both directions  
- Captures better contextual understanding  
- More powerful than standard LSTM  

---

## 📈 Results Comparison

| Model      | Performance |
|------------|------------|
| LSTM       | Good accuracy |
| BiLSTM     | Higher accuracy |

---

## 🏆 Best Model
👉 **Bidirectional LSTM performed better**  
- Better context understanding  
- Improved classification accuracy  

---

## 🧠 Key Insights
- Deep learning models outperform traditional NLP methods  
- Context matters in fake news detection  
- BiLSTM is more effective due to bidirectional learning  

---

## ⚠️ Challenges Faced
- Handling missing values in dataset  
- Text preprocessing complexity  
- Model tuning  

---

## 🎯 Conclusion
Deep learning models, especially Bidirectional LSTM, are highly effective for fake news detection tasks.

---

## 🔮 Future Improvements
- Use pre-trained embeddings (GloVe, Word2Vec)  
- Try Transformer models (BERT)  
- Improve accuracy with hyperparameter tuning  
