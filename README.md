 NLP Explorer
A multi-task NLP application built with Gradio and Hugging Face Transformers, featuring 7 interactive demos in a single interface.

 Features
TabTaskModels Used TokenizationText tokenization comparisonNLTK, BERT, T5, GPT-2💬 SentimentSentiment analysisDistilBERT, RoBERTa SimilaritySentence similarityall-MiniLM-L6-v2, paraphrase-MiniLM-L3-v2🏷️ Zero-ShotText classificationXLM-RoBERTa, BART🔍 NERNamed entity recognitionBERT large CoNLL03❓ Q&AQuestion answeringRoBERTa SQuAD2🌍 Lang DetectionLanguage detectionXLM-RoBERTa

 Installation
bashpip install gradio transformers torch sentence-transformers nltk spacy scikit-learn
python -m spacy download en_core_web_sm

 Usage
Open the notebook in Google Colab or Jupyter and run all cells. A Gradio interface will launch automatically.

 Built With

Gradio
Hugging Face Transformers
Sentence Transformers
NLTK
spaCy
