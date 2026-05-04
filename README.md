# 📊 RNN Sentiment Analysis for IMDB

This project demonstrates **sentiment analysis** on the **IMDB movie reviews dataset** using a **Recurrent Neural Network (RNN)** implemented entirely in a single Jupyter Notebook. The model classifies reviews as **positive** or **negative**, showcasing how RNNs capture sequential dependencies in text.

---

## 🚀 Features
- End-to-end workflow in one notebook:
  - Data loading and preprocessing  
  - Tokenization and padding  
  - RNN model definition (LSTM/GRU)  
  - Training and evaluation  
- Clear, step-by-step explanations with code cells.  
- Easy to run and modify for experimentation.  

---

## 📂 Project Structure
```
RNN-Sentiment-Analysis-for-IMDB/
│
├── RNN_Sentiment_Analysis_IMDB.ipynb   # Main notebook with all code
├── requirements.txt                     # Dependencies
└── README.md                            # Project documentation
```

---

## ⚙️ Installation
Clone the repository and install dependencies:

```bash
git clone https://github.com/Qazim-07/RNN-Sentiment-Analysis-for-IMDB.git
cd RNN-Sentiment-Analysis-for-IMDB
pip install -r requirements.txt
```

---

## 📊 Usage
Open the notebook in Jupyter or VS Code:

```bash
jupyter notebook RNN_Sentiment_Analysis_IMDB.ipynb
```

Run the cells sequentially to:
1. Preprocess the IMDB dataset  
2. Train the RNN model  
3. Evaluate accuracy and loss  

---

## 🧠 Model Overview
- **Embedding Layer**: Converts words into dense vectors.  
- **RNN Layer (LSTM/GRU)**: Learns sequential dependencies in text.  
- **Dense + Sigmoid Output**: Predicts sentiment (positive/negative).  

---

## 📈 Results
- Achieves ~85% accuracy on IMDB dataset.  
- Demonstrates the effectiveness of RNNs for text classification.  

---

## 🔮 Future Work
- Add **Bi-LSTM** for better context capture.  
- Experiment with **attention mechanisms**.  
- Compare with **Transformer-based models (BERT, RoBERTa)**.  

---

## 🤝 Contributing
Contributions are welcome! Fork the repo, open issues, or submit pull requests.

---

## 📜 License
This project is licensed under the MIT License.

---
