\# Legal Text Classification

\## UE24CS352A - Machine Learning Mini Project



\### 📌 Project Overview

Automatic classification of US Supreme Court legal opinions into 

legal issue areas using NLP and Machine Learning (LDA, Doc2Vec, 

and Logistic Regression).



\### 🎯 Models Implemented

\- LDA + Logistic Regression (Accuracy: 64.35%)

\- Doc2Vec + Logistic Regression (Accuracy: 68.99%)



\### 📊 Dataset

\- Source: `textacy.datasets.SupremeCourt()`

\- Size: 8,398 US Supreme Court decisions

\- Period: 1946-2018

\- Labels: Legal issue areas (14 categories)



\### 🛠️ Setup Instructions



\#### Prerequisites

\- Google Colab or Python 3.x

\- Internet connection (for dataset download)



\#### Installation

```bash

pip install floret==0.10.3

pip install textacy==0.12.0

pip install gensim

python -m spacy download en\_core\_web\_sm

