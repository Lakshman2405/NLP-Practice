# Natural Language Processing (NLP) Algorithms Portfolio

## 📌 Overview
This repository is a curated portfolio of implementations of **core Natural Language Processing (NLP) algorithms**, ranging from **classical statistical methods** to **machine learning** and **deep learning** approaches.

The objective of this project is to build a **strong conceptual and practical foundation in NLP** by implementing algorithms from scratch or using standard libraries, and understanding how language is modeled computationally.

Rather than focusing on a single application, this repository serves as a **learning-oriented NLP laboratory**, covering multiple paradigms used in real-world NLP systems.

---

## 🎯 Objectives
- Understand how text is represented numerically
- Implement classical NLP and statistical language models
- Apply machine learning techniques to NLP problems
- Explore probabilistic sequence models
- Build neural network models for language modeling and sequence learning
- Compare strengths and limitations of different NLP approaches

---

## 🧠 NLP Techniques Covered

### 1️⃣ Classical NLP & Statistical Methods
These methods focus on frequency-based and rule-inspired modeling of language.

#### 🔹 Bag of Words (BoW) & TF-IDF
- Implemented Bag of Words and TF-IDF vectorization
- Applied **Naive Bayes classification** for sentiment analysis
- Evaluated model performance using accuracy, precision, recall, and F1-score

**Concepts covered:**
- Text vectorization
- Term weighting
- Probabilistic classification

---

#### 🔹 Collocation Analysis (T-score & Chi-square)
- Identified statistically significant word collocations
- Implemented **t-score** and **chi-square** association measures
- Compared collocation detection sensitivity

**Concepts covered:**
- Word association measures
- Hypothesis testing in NLP
- Statistical dependency in language

---

#### 🔹 Hindle & Rooth Attachment Ambiguity
- Implemented attachment ambiguity resolution using bigram statistics
- Determined whether prepositional phrases attach to nouns or verbs
- Used probabilistic reasoning over corpus statistics

**Concepts covered:**
- Syntactic ambiguity
- Probabilistic attachment models
- Linguistic structure analysis

---

### 2️⃣ Probabilistic Models for NLP

#### 🔹 Hidden Markov Models (HMM)
- Implemented **Forward–Backward (Trellis) algorithm**
- Implemented **Viterbi algorithm** for optimal state decoding
- Calculated sequence likelihoods and posterior state probabilities

**Concepts covered:**
- Sequence modeling
- State transitions and emissions
- Dynamic programming

---

#### 🔹 Probabilistic Context-Free Grammar (PCFG)
- Defined probabilistic grammar rules
- Implemented parsing using:
  - CYK / Inside algorithm (all possible parses)
  - Viterbi parsing (most probable parse)
- Analyzed syntactic ambiguity through parse trees

**Concepts covered:**
- Grammar-based parsing
- Probabilistic syntax
- Tree-based language representations

---

### 3️⃣ Machine Learning for NLP

#### 🔹 Word Sense Disambiguation (Naive Bayes)
- Used Bag of Words features
- Trained a **Naive Bayes classifier** to disambiguate word senses
- Evaluated predictions on unseen sentences

**Concepts covered:**
- Supervised NLP classification
- Feature extraction for semantics
- Context-based meaning resolution

---

#### 🔹 Word2Vec (Distributional Semantics)
- Trained Word2Vec embeddings using Gensim
- Learned vector representations of words
- Analyzed semantic similarity between words

**Concepts covered:**
- Distributed word representations
- Context windows
- Semantic similarity

---

### 4️⃣ Deep Learning for NLP

#### 🔹 Recurrent Neural Networks (RNN)
- Built a basic RNN model for sequence modeling
- Demonstrated limitations such as vanishing gradients

---

#### 🔹 Long Short-Term Memory (LSTM)
- Implemented an LSTM-based next-word prediction model
- Trained on a real text corpus
- Generated new text sequences from seed input

**Concepts covered:**
- Sequence learning
- Long-term dependency modeling
- Neural language models

---

#### 🔹 Sequence-to-Sequence (Toy Translation)
- Implemented a simple encoder–decoder RNN model
- Performed toy machine translation
- Demonstrated teacher forcing and decoding logic

**Concepts covered:**
- Seq2Seq architecture
- Encoder–decoder paradigm
- Neural machine translation basics

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Libraries & Frameworks:**
  - NLTK
  - scikit-learn
  - Gensim
  - TensorFlow / Keras
  - NumPy, pandas

---

## 📊 Key Learnings
- Differences between classical, probabilistic, ML, and DL-based NLP
- Importance of feature representation in language modeling
- Strengths and limitations of statistical NLP
- How deep learning improves semantic understanding
- Trade-offs between interpretability and performance

---

## 🚀 Future Improvements
- Apply TF-IDF + word embeddings jointly
- Extend sequence models using attention mechanisms
- Add transformer-based models (BERT-style)
- Evaluate models on larger benchmark datasets

---

## 📎 Disclaimer
This repository is intended for **educational and learning purposes**.  
Some datasets and implementations are simplified to highlight algorithmic understanding rather than production deployment.

---

## 📫 Author
**Lakshman Guru Sai**  
B.Tech CSE (AI & DS)  
Interested in AI, NLP, Machine Learning, and Data Science
