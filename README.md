# 🧠 NLP Text Classification

This project performs binary sentiment classification (positive/negative) on movie reviews using Natural Language Processing (NLP) techniques. It uses the built-in `movie_reviews` dataset from the NLTK library and a Naive Bayes classifier.

---

## ⚙️ Tech Stack

| Tool            | Purpose                                 |
|-----------------|------------------------------------------|
| Python          | Core programming language               |
| NLTK            | Tokenization, stopwords, datasets        |
| Scikit-learn    | Naive Bayes classifier, evaluation       |
| Google Colab| Interactive model building environment   |

---

## 📌 Workflow

1. Load `movie_reviews` dataset from NLTK
2. Clean and preprocess the text
3. Extract features using Bag-of-Words (DictVectorizer)
4. Train a Naive Bayes model
5. Evaluate using accuracy & classification report
6. Predict sentiment of new custom input

---

## 💡 Sample Output

```python
predict_sentiment("I hated every minute of this boring film. But it was a good start for beginners.")
# Output: 'negative'
