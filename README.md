# Natural Language Processing (NLP) Projects

This repository contains various NLP (Natural Language Processing) implementations and analyses focusing on fundamental NLP tasks.

## Project Structure

### 1. Text Preprocessing
Located in: `text_pre_processing/`

This folder focuses on text preprocessing techniques, which are essential steps before any NLP task. The implementation uses TripAdvisor hotel reviews dataset.

Text preprocessing typically includes:
- Tokenization
- Lowercasing
- Removing special characters and numbers
- Removing stop words
- Lemmatization/Stemming
- Handling punctuation

**Dataset**: `tripadvisor_hotel_reviews.csv` - A collection of hotel reviews from TripAdvisor

### 2. POS Tagging and Named Entity Recognition (NER)
Located in: `pos_tagging_and_ner/`

This folder contains implementations of Part-of-Speech (POS) tagging and Named Entity Recognition (NER) using BBC news dataset.

#### What is POS Tagging?
Part-of-Speech tagging is the process of marking up words in a text with their corresponding part of speech (noun, verb, adjective, etc.). This is a fundamental NLP task that helps in:
- Understanding the grammatical structure of sentences
- Word sense disambiguation
- Building parse trees for further processing

#### What is Named Entity Recognition (NER)?
NER is the process of locating and classifying named entities (person names, organizations, locations, etc.) in text. It's crucial for:
- Information extraction
- Question answering systems
- Document classification

**Dataset**: `bbc_news.csv` - A collection of BBC news articles for analysis

### 3. Sentiment Analysis
Located in: `sentiment_analysis/`

This folder contains implementation of sentiment analysis on book reviews dataset. Sentiment analysis, also known as opinion mining, is the process of determining the emotional tone or attitude expressed in text.

The implementation demonstrates:
- Text preprocessing for sentiment analysis
- Sentiment scoring and classification
- Analysis of sentiment polarity (positive, negative, neutral)
- Interpretation of sentiment results

**Dataset**: `book_reviews_sample.csv` - A collection of book reviews for sentiment analysis

## Getting Started

Each folder contains Jupyter notebooks (`.ipynb` files) that demonstrate the implementation and analysis process. The notebooks are self-contained with detailed explanations and code comments.

### Prerequisites
- Python 3.x
- Jupyter Notebook
- Required libraries (specified within each notebook)

## Data Sources
- BBC News Dataset
- TripAdvisor Hotel Reviews Dataset

---
Note: Please refer to individual notebooks for detailed implementation and specific requirements.
