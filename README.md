# Fake News Detection

This project is a Natural Language Processing (NLP) based classifier to identify whether a news article is **real** or **fake** using machine learning techniques.

## Overview
Fake news can cause significant harm in public opinion and trust. This project uses TF-IDF and machine learning models like Logistic Regression to detect fake news based on the article text.

## 🛠 Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- TF-IDF Vectorizer
- NLTK (for text cleaning)
- Jupyter Notebook

## Dataset
Used a labeled dataset of real and fake news articles.  
📁 `news.csv` contains the text and label.  
*Source:* [Kaggle - Fake News](https://www.kaggle.com/c/fake-news/data)

## How to Run

```bash
git clone https://github.com/FaaizAman/Fake-News-Detection.git
cd Fake-News-Detection
pip install -r requirements.txt
jupyter notebook Fake\ News\ Detection.ipynb
