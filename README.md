# Legal Text Classification

**UE24CS352A – Machine Learning Mini Project**

##  Project Overview

Automatic classification of US Supreme Court opinions into legal issue areas using NLP and machine learning (LDA, Doc2Vec, and Logistic Regression).

##  Models Implemented

| Model | Accuracy |
|-------|----------|
| LDA + Logistic Regression | 64.35% |
| Doc2Vec + Logistic Regression | 68.99% |

##  Dataset

- **Source:** `textacy.datasets.SupremeCourt()`
- **Size:** 8,398 US Supreme Court decisions
- **Period:** 1946–2018
- **Labels:** Legal issue areas (14 categories)

##  Setup Instructions

The following instructions detail how to set up the project environment.

 Clone this repository to your local machine:
   ```powershell
   git clone [https://github.com/SAATHVIK-2006/Classification_of_Legal_Text.git]
   cd Classification_of_Legal_Text
   ``` 
   
   
### Prerequisites

- Google Colab or Python 3.x
- Internet connection (for dataset download)

### Installation

```bash
pip install floret==0.10.3
pip install textacy==0.12.0
pip install gensim
python -m spacy download en_core_web_sm
```

   

##  Authors

| Name | SRN |
|------|-----|
| SAATHVIK SAI SUVARNA| PES1UG24AM238 |
| PRITHVI RAJ | PES1UG24AM204 |


