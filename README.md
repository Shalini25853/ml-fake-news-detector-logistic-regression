# ml-fake-news-detector-logistic-regression
A logistic regression model using TF-IDF to classify fake vs real news headlines, with 93.9% accuracy. Includes model evaluation and future enhancement recommendations.
# 📰 Fake News Detection using Logistic Regression

This project implements a **logistic regression classifier** to detect fake news headlines using **TF-IDF vectorization** and binary classification techniques. The model is designed for integration into real-time mobile or web applications to help users assess the credibility of online articles.

---

## 🔍 Problem Statement

Misinformation spreads rapidly through platforms like Twitter/X, influencing public opinion and markets. This model aims to classify whether a news headline is *real* or *fake*, giving users a confidence score to support their decision-making.

---

## ⚙️ Tools & Technologies
- Python
- Scikit-learn
- TF-IDF Vectorizer
- Pandas / NumPy
- Jupyter Notebook

---

## 🧠 Methodology

1. **Text Preprocessing**
   - Tokenization
   - Stopword removal
   - TF-IDF feature extraction

2. **Model Building**
   - Logistic Regression (binary classifier)
   - 80/20 train-test split

3. **Evaluation**
   - Accuracy: **93.9%**
   - Confusion matrix
   - Precision, Recall, F1-score

---

## 📊 Results

- **High Precision**: Effectively minimizes false positives
- **Challenge**: Model struggles slightly with subtle false negatives
- **Confusion Matrix**: Shows strong performance on both real and fake cases

---

## 🚧 Limitations & Future Work

- TF-IDF lacks semantic understanding — future work can explore:
  - BERT or transformer-based embeddings
  - Hybrid models (ensemble learning)
  - Fact-checking API integration
  - User feedback loop for continuous learning

---

## 🧾 Business Impact

This tool can be embedded into **social media platforms**, **news aggregation apps**, or **browser extensions** to reduce the spread of fake news and improve digital literacy.

---

## 📁 Files Included
- `A1_Classification_[Individual].ipynb` – Jupyter notebook with model code
- `A1 Report SHALINI JAMES PAULRAJ.pdf` – Detailed report explaining the process and results

---

## 🏷️ Tags
`#machine-learning` `#logistic-regression` `#nlp` `#text-classification` `#fake-news` `#tfidf` `#python`

---

## ✍️ Author
**Shalini James Paulraj**  
Graduate Student – Business Analytics & International Business  
[LinkedIn](https://linkedin.com/in/shalinijamespaulraj)
