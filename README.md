    Overview
       This project performs sentiment analysis on text data using multiple natural language processing (NLP) tools. The goal is to classify text into positive, negative, or neutral sentiment categories. Various Python libraries and pre-trained models are used, including:
       1. VADER (Valence Aware Dictionary for Sentiment Reasoning) – Rule-based sentiment analysis for English.
       2. TextBlob – Provides sentiment polarity and subjectivity, as well as noun phrase extraction.
       3. SpaCyTextBlob – Integrates TextBlob with SpaCy for NLP pipelines.
       4. Stanford CoreNLP – Advanced NLP toolkit for sentence-level sentiment classification.
       5. The project is built for both English and Arabic text (where applicable) and demonstrates multiple approaches to sentiment classification.


     Objectives
        1. Implement multiple sentiment analysis methods in Python.
        2. Compare performance and outputs of different NLP libraries.
        3. Build a clean, reusable pipeline for analyzing sentiment in raw text.
        4. Visualize sentiment scores at word and sentence level.
        5. Provide ready-to-use functions for sentiment scoring of arbitrary text.    


     Project Structure
         Sentiment-Analysis/
         │
         ├─ data/                        # Example datasets (if any)
         │
         ├─ notebooks/                   # Jupyter/Colab notebooks for testing
         │   ├─ Sentiment_Analysis.ipynb
         │
         ├─ src/                         # Python scripts for NLP pipelines
         │   ├─ vader_sa.py              # Functions using VADER
         │   ├─ textblob_sa.py           # Functions using TextBlob
         │   ├─ spacytextblob_sa.py      # Functions using SpaCyTextBlob
         │   └─ stanford_corenlp_sa.py   # Functions using Stanford CoreNLP
         │
         ├─ requirements.txt             # Required Python libraries
         ├─ README.md                    # Project documentation
         └─ LICENSE


         How It Works
             1. VADER: Calculates sentiment scores for each sentence and returns positive, negative, and neutral components.
             2. TextBlob: Computes polarity and subjectivity; extracts noun phrases for deeper analysis.
             3. SpaCyTextBlob: Combines SpaCy tokenization with TextBlob sentiment for easy integration in NLP pipelines.
             4. Stanford CoreNLP: Uses a pre-trained neural model to classify each sentence’s sentiment as Negative, Positive, or Very Positive.
   
