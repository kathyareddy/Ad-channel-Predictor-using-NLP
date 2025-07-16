# Ad Channel Predictor using NLP

A Natural Language Processing project that predicts the most suitable **advertising channel** (like Email, Social Media, SMS, etc.) based on the content of a marketing message. It uses text classification techniques on labeled data to help marketers choose the best communication medium.


---

## Overview

Given a marketing message, the system predicts which channel it is best suited for: **Email**, **Social Media**, **SMS**, etc. It uses **TF-IDF vectorization** and a **Multinomial Naive Bayes classifier** to perform text classification on labeled ad content.

---

## Tech Stack

- **Python 3**
- **Scikit-learn** – ML models and pipeline
- **Pandas, NumPy** – Data processing
- **NLTK / Regex** – Text cleaning
- **TF-IDF** – Feature extraction
- **Matplotlib / Seaborn** – Visualization

---

## Features

-  Preprocess raw ad text (cleaning, stopword removal)  
-  Convert messages to TF-IDF vectors  
-  Classify messages into channels (Email, SMS, etc.)  
-  Evaluate accuracy, visualize confusion matrix  
-  Try with custom inputs for prediction  

---

## File Structure

```
Ad-channel-Predictor-using-NLP/
│
├── ad_channel_predictor_nlp.ipynb     # Jupyter Notebook with full pipeline
├── ad_channel_data.csv                # Input dataset
├── README.md                          # Project documentation
```

---

## Dataset

- **File**: `ad_channel_data.csv`
- **Fields**:
  - `message`: marketing message content
  - `channel`: target ad channel (label)
- **Sample Classes**: Email, SMS, Social Media, Push Notification

---

## Workflow Summary

1. Load and clean dataset  
2. Preprocess text (remove punctuation, lowercase, stopwords)  
3. Vectorize using TF-IDF  
4. Train Naive Bayes classifier  
5. Evaluate with accuracy and confusion matrix  
6. Predict for new messages  

---

## Results

- **Model**: Multinomial Naive Bayes  
- **Accuracy**: ~85% (depends on dataset split)  
- **Evaluation**: Classification report and confusion matrix  

---

## Future Improvements

- Use more robust models like SVM or BERT  
- Build a Streamlit or Flask UI  
- Expand dataset for more real-world diversity  
- Integrate A/B testing logic  

---


