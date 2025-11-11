# Overview

This project focuses on turning long, messy customer complaints into short, clear summaries.I have used a BART-based model from Hugging Face ,
it reads each complaint, summarizes the main issue, identifies the sentiment, and suggests what action a company should take.
Programming language Python was used to make the project on Google Colab and NLP techniques were applied .

# Problem Statement

Companies receive hundreds of complaints every day and most of them are long, repetitive, and hard to process quickly. Manually reading each one takes a lot of  time and effort. The goal here was to build a small NLP system that can automatically summarize complaints and highlight how the customer feels (positive, neutral, or negative),which will be helpful for support teams to respond faster.

# Dataset

The dataset was sourced from kaggle - https://www.kaggle.com/datasets/adhamelkomy/bank-customer-complaint-analysis
The dataset includes real customer complaints from the banking sector, along with product categories and complaint narratives. These narratives form the base for summarization and sentiment analysis.

# Technical Aspects

**Libraries :** transformers, pandas, tqdm, nltk
**Model :** philschmid/bart-large-cnn-samsum (a BART model fine-tuned for summarizing conversational text)

# Key function 


# Output
