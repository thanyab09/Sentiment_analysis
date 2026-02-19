# Sentiment Analysis: VADER vs RoBERTa

This project compares two approaches to sentiment analysis:

- **VADER (Valence Aware Dictionary for Sentiment Reasoning)**  
  A rule-based sentiment analysis tool optimized for social media text.

- **RoBERTa (Robustly Optimized BERT Approach)**  
  A transformer-based deep learning model fine-tuned for sentiment classification.

---

## Objective
The goal of this notebook is to evaluate the performance of a traditional lexicon-based model (VADER) against a modern transformer-based model (RoBERTa) on sentiment classification tasks.  
By comparing these two approaches, the project highlights the trade-offs between speed, interpretability, and accuracy.

---

## Dataset
The sentiment analysis experiments were conducted using the **Amazon Fine Food Reviews** dataset.

- **Source:** Amazon Fine Food Reviews Sentiment Analysis on Kaggle - (https://www.kaggle.com/code/chirag9073/amazon-fine-food-reviews-sentiment-analysis)  
- **Description:** This dataset contains text reviews of food products from Amazon, labeled with sentiment (positive or negative). It includes over 500,000 reviews,
  making it a rich resource for testing both lexicon-based and transformer-based models.  
- **Usage:**  
  - **VADER** was applied directly to the raw text to generate sentiment scores.  
  - **RoBERTa** was fine-tuned on the dataset to classify sentiment with higher accuracy.  

> Note: The dataset is not included in this repository due to size and licensing restrictions.  
> Please download it directly from the Kaggle source linked above.

---

## Results
- **VADER:**  
  - Fast and lightweight.  
  - Performs well on short, informal text.  
  - Struggles with nuanced or context-heavy language.  

- **RoBERTa:**  
  - Achieves higher accuracy and better handles complex language.  
  - Requires more computational resources and training time.  

This comparison demonstrates the strengths of traditional lexicon-based methods versus transformer-based deep learning models in sentiment analysis.

---

## Requirements
- Python 3.x
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `nltk` (for VADER)
  - `transformers` (for RoBERTa)
  - `torch`

---
