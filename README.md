#  NLP Explorer

> A multi-task NLP application built with **Gradio** and **Hugging Face Transformers**, featuring **7 interactive demos** in a single interface.

---

##  Overview

NLP Explorer is an interactive application that brings together seven core Natural Language Processing tasks in one unified Gradio interface. Each tab demonstrates a different NLP capability using state-of-the-art pre-trained transformer models.

---

##  Features

| Tab | Task | Models Used |
|-----|------|-------------|
| 🔤 **Tokenization** | Text tokenization comparison | NLTK, BERT, T5, GPT-2 |
| 💬 **Sentiment** | Sentiment analysis | DistilBERT, RoBERTa |
| 🔁 **Similarity** | Sentence similarity | all-MiniLM-L6-v2, paraphrase-MiniLM-L3-v2 |
| 🏷️ **Zero-Shot** | Text classification | XLM-RoBERTa, BART-large-MNLI |
| 🔍 **NER** | Named entity recognition | BERT large CoNLL03 |
| ❓ **Q&A** | Question answering | RoBERTa SQuAD2 |
| 🌍 **Lang Detection** | Language detection | XLM-RoBERTa |

---

##  Built With

- [Gradio](https://gradio.app/) — Interactive UI
- [Hugging Face Transformers](https://huggingface.co/transformers/) — Pre-trained models
- [Sentence Transformers](https://www.sbert.net/) — Sentence embeddings
- [NLTK](https://www.nltk.org/) — Natural language toolkit
- [spaCy](https://spacy.io/) — NLP pipeline
- [Scikit-learn](https://scikit-learn.org/) — Machine learning utilities
- [PyTorch](https://pytorch.org/) — Deep learning framework

---

##  Installation

```bash
pip install gradio transformers torch sentence-transformers nltk spacy scikit-learn
python -m spacy download en_core_web_sm
```

---

##  Usage

1. Open the notebook in **Google Colab** or **Jupyter Notebook**
2. Run all cells
3. A Gradio interface will launch automatically in your browser

---

##  Author

**Maroua Himmich** — AI Engineering Student at Junia ISEN Lille  
[LinkedIn](https://www.linkedin.com/in/himmich-maroua)
