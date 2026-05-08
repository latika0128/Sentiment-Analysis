# 📊 Sentiment Analysis using CNN-LSTM and CNN-GRU

## 🚀 Project Overview
This project focuses on building a **Sentiment Analysis system** for social media (Twitter/X) data using hybrid deep learning models. The system classifies text into **Positive** or **Negative** sentiment using two architectures:
- CNN + LSTM
- CNN + GRU

The goal is to compare performance and analyze efficiency in terms of accuracy, time complexity, and memory usage.

---

## 🧠 Key Features
- Hybrid Deep Learning Models (CNN-LSTM & CNN-GRU)
- NLP preprocessing pipeline
- Model comparison and evaluation
- Time and space complexity analysis
- Visualization of results

---

## 📂 Dataset
- **Source:** Twitter Sentiment Dataset (Kaggle)
- **Type:** Social media text data
- **Classes:** Positive, Negative

---

## ⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 🔄 Workflow
Text Data → Preprocessing → Tokenization → Padding → Embedding → CNN → LSTM/GRU → Dense → Output

---

## 🏗️ Model Architectures

### 🔹 CNN-LSTM
- Embedding Layer
- Conv1D + MaxPooling
- LSTM Layer
- Dense Output Layer

### 🔹 CNN-GRU
- Embedding Layer
- Conv1D + MaxPooling
- GRU Layer
- Dense Output Layer

---

## 📊 Results

| Model     | Accuracy | Time (sec) | Memory (MB) |
|----------|---------|-----------|------------|
| CNN-LSTM | ~88.6%  | ~645 sec  | ~45 MB     |
| CNN-GRU  | ~89%    | ~632 sec  | ~32 MB     |

---

## 📈 Visualizations
- Accuracy vs Epoch
- Loss vs Epoch
- Confusion Matrix
- Model Comparison Graph

---

## 📌 Key Insights
- CNN effectively extracts local text features
- LSTM captures long-term dependencies
- GRU provides faster and memory-efficient performance
- CNN-GRU slightly outperformed CNN-LSTM in efficiency

---

## 🧪 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score

---

## 🏁 Conclusion
Both models perform well for sentiment classification. However, CNN-GRU offers a better trade-off between performance and computational efficiency, while CNN-LSTM provides slightly deeper contextual understanding.

---

## 🔮 Future Work
- Use pre-trained embeddings (Word2Vec, GloVe)
- Apply transformer models (BERT)
- Extend to multi-class sentiment analysis
- Real-time sentiment prediction system
