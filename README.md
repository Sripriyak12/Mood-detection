# 🎭 Emotion & Sentiment Analyzer

This is a Python-based NLP tool that combines a transformer-based emotion classifier (DistilRoBERTa) with VADER sentiment analysis to provide a comprehensive emotional and sentiment understanding of user input text.

---

## 🚀 Features

- 🔍 **Emotion Detection** using [j-hartmann/emotion-english-distilroberta-base](https://huggingface.co/j-hartmann/emotion-english-distilroberta-base)
- 😊 **Sentiment Analysis** using **VADER** (Valence Aware Dictionary and sEntiment Reasoner)
- 📊 Outputs both **emotion label** and **positive/neutral/negative sentiment**
- 💡 Easy to run and customize
- ✅ Works well for English text input

---

## 🧠 Under the Hood

| Component         | Technology                                  |
|------------------|---------------------------------------------|
| Emotion Classifier | 🤗 Hugging Face Transformers (DistilRoBERTa) |
| Sentiment Scorer | 🧠 NLTK's VADER                             |
| Language         | Python                                     |
| Frameworks       | PyTorch, Transformers, NLTK                |

---

## 🛠️ Installation

### 1. Clone the repository (or copy the code)

```bash
git clone https://github.com/your-username/emotion-sentiment-analyzer.git
cd emotion-sentiment-analyzer
```

### 2.Install dependencies
```bash
pip install transformers torch nltk vaderSentiment
```
### 3.Run the script directly:
```bash
python your_script_name.py
```


