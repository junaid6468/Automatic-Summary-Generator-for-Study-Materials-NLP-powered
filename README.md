# 📚 Automatic Summary Generator for Study Materials

This project is an AI-powered summary generator designed to help students, researchers, and educators by automatically extracting concise and relevant summaries from lengthy academic texts or study materials.

> Powered by state-of-the-art NLP models like **BART** or **T5**, this tool provides fast, accurate, and readable summaries for textbooks, notes, articles, and more.

---

## ✨ Features

- 🔍 Accepts large textual input (e.g., copied text or from files)
- 🧠 Generates concise summaries using transformer-based models
- 📌 Highlights keywords and core topics
- 📁 Jupyter Notebook interface for interactive use
- 🗂️ Optionally integrates with file upload (PDF, DOCX, TXT)
- 🔊 (Optional) Text-to-Speech output of the summary

---

## 🧪 Model Used

- `HuggingFace Transformers`: [BART](https://huggingface.co/facebook/bart-large-cnn) / [T5](https://huggingface.co/t5-base)
- `spaCy` and `NLTK` for preprocessing
- `Sumy` (optional) for classical summarization methods

---

## 🛠️ Installation

### 1. Clone the Repository
```bash
git clone https://github.com/junaid6468/summary-generator.git
cd summary-generator
