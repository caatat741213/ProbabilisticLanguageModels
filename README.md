# Probabilistic Language Models Workshop

## 👥 Team Members
* **Chao-Chung Liu**


---

## 📖 Project Description
This project is an NLP (Natural Language Processing). We implemented **Unigram** and **Bigram** probabilistic models to estimate the probability of sentences based on a specific text corpus.

---

## 📊 Dataset Description
* **Title:** Harry Potter and the Sorcerer's Stone
* **Source:** [San Diego State University (SDSU) - Harry Potter Text](https://dgoldberg.sdsu.edu/515/harrypotter.txt)
* **Author:** J.K. Rowling
* **Vocabulary Size:** Approximately 6,000 unique words (after normalization).
* **Requirements:** This dataset satisfies the "over 2000 words" requirement for this project.

---

## 🛠️ Features
1. **Document Collection:** Loading custom text files.
2. **Tokenizer:** Splitting text using Regular Expressions (Regex).
3. **Normalization Pipeline:** Includes Stopword removal and Porter Stemming.
4. **Probabilistic Models:**
   * **Unigram Model:** Calculates word independence probability.
   * **Bigram Model:** Calculates local dependency probability between word pairs.

---

## 🧭 Conclusion
Our experiments show that:
* **Unigram models** ignore word order and focus on frequency.
* **Bigram models** are very strict about word sequences; if a pair never appeared in the book, the probability becomes zero.

---

## 🚀 How to Run
1. Clone this repository.
```bash
    git clone [https://github.com/caatat741213/ProbabilisticLanguageModels.git](https://github.com/caatat741213/ProbabilisticLanguageModels.git)
   cd ProbabilisticLanguageModels
```
2. Create and activate a virtual environment (Optional but recommended):
```bash
    python -m venv .venv
    # Windows:
    .venv\Scripts\activate
    # Mac/Linux:
    source .venv/bin/activate
```
3. Install dependencies:
```bash
    pip install -r requirements.txt
```
4. Run the Notebook:
    Open ProbabilisticLanguageModels.ipynb in VS Code or Jupyter Notebook and run all cells.

