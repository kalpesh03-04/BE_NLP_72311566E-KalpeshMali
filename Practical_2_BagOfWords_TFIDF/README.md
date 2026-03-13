#  NLP Practical 2

## Bag of Words, TF-IDF and Word2Vec

---

##  Objective

To understand different **text representation techniques** in Natural Language Processing such as **Bag of Words (BoW)**, **Normalized Bag of Words**, **TF-IDF**, and **Word2Vec embeddings**.

---

##  Problem Statement

Perform **Bag-of-Words (count occurrence and normalized count occurrence)** and **TF-IDF** on text data.
Create **word embeddings using Word2Vec** on the dataset.

---

##  Dataset

The **Twitter Airline Sentiment dataset (Tweets.csv)** is used for this experiment.

The dataset contains tweets related to airline services and their sentiment labels.

---

##  Tools and Libraries

* Python
* Jupyter Notebook
* Pandas
* Scikit-learn
* Gensim

---

##  Techniques Implemented

### 1️. Bag of Words (Count Occurrence)

Bag of Words converts text into a **matrix of word counts**.
Each row represents a document and each column represents a word from the vocabulary.

---

### 2️. Normalized Bag of Words

Normalized BoW divides the count of each word by the **total number of words in the document**, giving the **relative frequency**.

---

### 3️. TF-IDF (Term Frequency – Inverse Document Frequency)

TF-IDF measures how important a word is in a document relative to the whole dataset.

It reduces the importance of very common words and highlights meaningful terms.

---

### 4️. Word2Vec Embeddings

Word2Vec is a **neural network-based method** that converts words into **dense numerical vectors**.

Words with similar meanings have **similar vector representations**.

---

##  Output

The following outputs are generated:

* Dataset preview
* Text column extraction
* Bag of Words matrix
* Normalized Bag of Words
* TF-IDF matrix
* Word2Vec word vector representation

Screenshots of the outputs are included in this folder.

---

##  Conclusion

Text representation techniques such as **Bag of Words**, **TF-IDF**, and **Word2Vec** are essential in Natural Language Processing.
They convert textual data into numerical form so that machine learning models can process and analyze text effectively.

