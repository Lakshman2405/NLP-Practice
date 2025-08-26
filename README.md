# 📊 Statistical NLP: Hypothesis Testing for Word Collocations

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![NLTK](https://img.shields.io/badge/NLTK-Latest-orange?logo=natural-language-toolkit)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![License](https://img.shields.io/badge/License-MIT-green)

An interactive Natural Language Processing (NLP) project that applies statistical hypothesis testing (**T-Test** and **Chi-Square Test**) to identify significant word collocations in text. This project demonstrates how to move beyond basic text analysis to derive statistically validated insights.

---

## 🧠 What are Word Collocations?

Collocations are words that frequently appear together, forming a meaningful unit (e.g., "strong coffee," "make a decision"). This project answers a key question:
> **"Are these two words appearing together merely by chance, or is their association statistically significant?"**

---

## ⚙️ How It Works

The project follows a complete NLP pipeline:

1.  **Text Preprocessing:** Loads text data and cleans it (tokenization, stopword removal, contraction handling).
2.  **Frequency Analysis:** Calculates individual word frequencies and co-occurrence rates.
3.  **Statistical Testing:** Employs two fundamental tests to measure the significance of word pairs:
    *   **T-Test:** Checks if the observed co-occurrence rate is significantly different from the expected rate under the assumption of independence.
    *   **Chi-Square Test:** Assesses the independence between two words in a contingency table.
4.  **Result Interpretation:** Compares the calculated test values against critical values to determine if a word pair is a true collocation.

---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 🚀 Getting Started

### Prerequisites

Ensure you have the following installed:
*   Python 3.x
*   Jupyter Notebook/Lab
*   The required Python libraries:

### Installation & Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Lakshman2405/Statistical-NLP-Collocations.git
    cd Statistical-NLP-Collocations
    ```

2.  **Install required packages:**
    ```bash
    pip install nltk numpy python-docx
    ```

3.  **Download NLTK Data:**
    Run the first cell of the Jupyter Notebook (`NLP Lab 2.ipynb`) to download all necessary NLTK datasets. This only needs to be done once.
    ```python
    import nltk
    nltk.download('all')
    ```

4.  **Run the Notebook:**
    Launch Jupyter Notebook and open `NLP_Lab_2.ipynb` to explore the code and run the analysis.
    ```bash
    jupyter notebook
    ```

---
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
## 📈 Methodology & Code Overview

### 1. Text Preprocessing
The code uses a custom class `REReplacer` to handle contractions (e.g., "won't" → "will not") and NLTK's `stopwords` corpus to remove common, uninformative words.

### 2. Hypothesis Testing Functions
The core of the project lies in these two custom-built functions:

#### **T-Test Function (`T_test`)**
```python
def T_test(w1, w2, c1, c2, c12):
    # ... calculates expected and observed means
    # ... returns t-value for the word pair (w1, w2)

### **Chi-Square Test Function (chi_2_test)**
```python
def chi_2_test(w1, w2, c1, c2, c12):
    # ... builds a 2x2 contingency table
    # ... calculates the chi-square statistic

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
🛠️ Technologies Used
Python: Core programming language

NLTK: Natural Language Toolkit for text processing

NumPy: For numerical computations

python-docx: For reading .docx files

Jupyter Notebook: For an interactive development environment

