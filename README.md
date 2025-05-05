# AICTE-Internship-word-embeddings-and-TF-IDF-vectors-in-NLTP

# Word Embeddings and TF-IDF Vectors in Natural Language Processing

This mini project explores two widely-used text representation techniques in Natural Language Processing (NLP): **TF-IDF** and **Word Embeddings** (Word2Vec/GloVe). It includes a comparison of their effectiveness in understanding and representing natural language for machine learning tasks such as text classification.

---

## 📌 Project Objectives

- Understand the concept and implementation of **TF-IDF** and **Word Embeddings**.
- Convert textual data into numerical formats suitable for machine learning.
- Compare the performance of TF-IDF and Word Embeddings in a classification setting.
- Visualize vector representations and similar words using Word2Vec.
- Provide insights on which technique is more effective and why.

---

## 🧰 Technologies Used

- **Language**: Python
- **Libraries**:
  - `scikit-learn` (TF-IDF, classifiers)
  - `gensim` (Word2Vec)
  - `nltk`, `spaCy` (Text preprocessing)
  - `matplotlib`, `seaborn` (Visualization)
  - `pandas`, `numpy` (Data manipulation)
- **Platform**: Jupyter Notebook / VS Code

---

## ⚙️ How It Works

### 1. Preprocessing
- Tokenization
- Lowercasing
- Stopword removal
- Punctuation removal

### 2. TF-IDF Vectorization
- Compute TF-IDF matrix for input sentences
- Train a simple classifier (e.g., Logistic Regression or Naive Bayes)

### 3. Word Embeddings
- Load pre-trained **GloVe** vectors using `gensim`
- Represent each document as an average of its word vectors
- Train the same classifier using these embeddings

### 4. Evaluation
- Compare model performance using:
  - Accuracy, Precision, Recall, F1-Score
  - Top similar words using `most_similar()` from Word2Vec
  - Vector values and similarity metrics

---

## 📊 Results

- **TF-IDF** shows strong results in short-text or frequency-driven tasks.
- **Word2Vec/GloVe** better captures semantic meaning and relationships.
- Top-5 similar words to “Python”: `['monty', 'php', 'perl', 'cleese', 'flipper']`
- Visualized vector spaces using PCA or t-SNE.

---

## 🧠 Conclusion

- TF-IDF is simple and works well for frequency-based tasks.
- Word Embeddings are more powerful for semantic understanding.
- Word2Vec/GloVe embeddings outperform TF-IDF in general language understanding tasks.

---


