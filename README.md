# sms-nlp-analysis
NLP analysis of SMS messages using TF-IDF, sentiment analysis, and text similarity

##  Overview

This project applies Natural Language Processing (NLP) techniques to analyze real-world SMS data from the NUS SMS Corpus. The dataset contains over 67,000 messages, primarily from Singaporean users, offering insight into informal, everyday communication.

The goal of this project is to extract meaningful patterns from unstructured text data and understand how people communicate through SMS.

---

##  Goals

* Analyze communication patterns in SMS messages
* Perform sentiment analysis on text data
* Identify key topics and frequently used phrases
* Measure similarity between messages
* Visualize insights using data-driven plots

---

## Techniques Used

* Text Preprocessing (tokenization, stopword removal, lemmatization)
* TF-IDF for keyword extraction
* N-grams for phrase detection
* Sentiment Analysis using VADER
* Levenshtein Distance for similarity analysis

---

## Key Findings

###  Informal Communication

SMS messages are highly informal, with frequent use of abbreviations such as "u", "ur", and expressive terms like "haha" and "lol".

###  Coordination-Focused Conversations

Most messages revolve around planning and scheduling, with phrases like "wat time", "go home", and "let know".

### Positive & Neutral Sentiment Dominance

The majority of messages are either neutral or positive, indicating that SMS is primarily used for casual and practical communication.

### High Variation in Text Structure

Messages differ significantly in wording and structure, highlighting diverse communication styles.

---

## Visualizations

### Word Cloud

[WordCloud](outputs/wordcloud.png)

### Sentiment Distribution

[Sentiment](outputs/sentiment.png)

### Top Words Frequency

[Top Words](outputs/top_words.png)

---

## Installation

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Open the notebook:

```bash
jupyter notebook
```

2. Run all cells in:

```
notebook/analysis.ipynb
```

---

## Limitations

* Informal language and slang may affect sentiment accuracy
* High-frequency words may not reflect meaningful topics
* Context is limited in short SMS messages

---

## Future Improvements

* Apply advanced models (e.g., word embeddings, transformers)
* Build a chatbot based on SMS style
* Deploy as a web application using Flask

---

## Author

**Serveheidari**

