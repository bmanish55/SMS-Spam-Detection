# 📩 SMS Spam Detection

This is a machine learning project that classifies SMS messages as either **spam** or **ham (not spam)** using natural language processing (NLP) techniques. It utilizes a dataset of labeled messages and builds a predictive model using the **Multinomial Naive Bayes** algorithm.

## 📝 Table of Contents

- [Demo](#-demo)
- [Features](#-features)
- [Dataset](#-dataset)
- [Technologies Used](#-technologies-used)
- [Installation](#-installation)
- [Usage](#-usage)
- [Results](#-results)
- [Future Work](#-future-work)
- [License](#-license)

---

## 📽️ Demo

> The Jupyter Notebook provides step-by-step code for preprocessing, training, and evaluating the spam classifier.  
> [Click here to view the notebook](sms_spam_detection.ipynb)

---

## ✅ Features

- Data cleaning and preprocessing
- Text normalization (lowercasing, punctuation removal, stemming)
- Tokenization and vectorization using `CountVectorizer`
- Model training with `MultinomialNB`
- Performance evaluation with accuracy score and confusion matrix
- Visualizations using `matplotlib` and `seaborn`

---

## 📊 Dataset

- **File**: `spam.csv`
- **Size**: ~5,500 SMS messages
- **Columns**:
  - `label`: Message category (`spam` or `ham`)
  - `message`: The text content of the SMS

---

## ⚙️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- NLTK
- Matplotlib
- Seaborn

---

## 🧑‍💻 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/bmanish55/SMS-Spam-Detection.git
   cd SMS-Spam-Detection
