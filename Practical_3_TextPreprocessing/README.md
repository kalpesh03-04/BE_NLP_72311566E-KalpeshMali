#  NLP Practical 3

## Text Preprocessing, Stopwords Removal, Lemmatization, Label Encoding and TF-IDF

---

##  Objective

To perform **text preprocessing techniques** in Natural Language Processing such as **text cleaning, stopword removal, lemmatization, label encoding, and TF-IDF representation** using Python.

---

##  Problem Statement

Apply different **text preprocessing techniques** on a dataset and convert textual data into **numerical form using TF-IDF** for further machine learning tasks.

---

##  Dataset

The **Twitter Airline Sentiment dataset (Tweets.csv)** is used for this experiment.
It contains tweets related to airline services along with sentiment labels.

---

##  Tools and Libraries

* Python
* Jupyter Notebook
* Pandas
* NLTK (Natural Language Toolkit)
* Scikit-learn

---

##  Techniques Implemented

### 1️. Text Cleaning

Text cleaning removes unwanted elements such as:

* Special characters
* Numbers
* Punctuation
* Uppercase letters

The text is converted into **lowercase format** for better processing.

---

### 2️. Stopword Removal

Stopwords are commonly used words such as:

```
the, is, and, to, of, in
```

These words do not add significant meaning in NLP tasks and are removed to improve model performance.

---

### 3️. Lemmatization

Lemmatization converts words into their **base or dictionary form**.

Examples:

```
running → run  
cars → car  
better → good
```

This helps reduce variations of words.

---

### 4️. Label Encoding

Label encoding converts **categorical labels** into **numerical values** so that machine learning algorithms can process them.

Example:

```
positive → 2  
neutral → 1  
negative → 0
```

---

### 5️. TF-IDF Representation

TF-IDF stands for **Term Frequency – Inverse Document Frequency**.

It measures the importance of a word in a document relative to the entire dataset.

TF-IDF helps reduce the impact of frequently occurring words and highlights more meaningful terms.

---

##  Output

The following outputs are generated:

* Dataset preview
* Cleaned text output
* Stopwords removed text
* Lemmatized text
* Label encoded sentiment values
* TF-IDF matrix representation

Screenshots of these outputs are included in this folder.

---

##  Conclusion

Text preprocessing techniques such as **cleaning, stopword removal, lemmatization, and TF-IDF** are essential steps in Natural Language Processing.
They help convert raw text data into structured numerical form suitable for machine learning and deep learning models.
