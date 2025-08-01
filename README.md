# 🧠 NLP Sentiment Analyzer & Summarizer

This Python-based project leverages state-of-the-art NLP models to:
- Summarize large texts 📚
- Analyze sentiment using transformer models 💬
- Perform POS (Part-of-Speech) tagging 🏷️
- Provide **positive suggestions** for negative sentiment 🌈
- Visualize sentiment with Matplotlib 📊

---

## 🔍 Features

- ✅ **Summarization** using BART (`facebook/bart-large-cnn`)
- ✅ **Sentiment Analysis** via DistilBERT (`distilbert-base-uncased-finetuned-sst-2-english`)
- ✅ **POS Tagging** with spaCy (`en_core_web_sm`)
- ✅ **Contextual Positive Suggestions** (Stress, Frustration, Sadness)
- ✅ **Interactive CLI** and sentiment score plot

---

## 📁 Project Structure

```bash
.
├── main.py                # Core script with summarization, sentiment analysis, POS tagging
├── requirements.txt       # List of dependencies
├── README.md              # Project documentation
