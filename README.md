# NLP-Programs-using-Python-NLTK-and-SPACY
# NLP-Programs-using-Python-NLTK-and-SPACY

A set of beginner-level Natural Language Processing practicals built in Python, using **NLTK** and **spaCy**. Each notebook focuses on one core NLP technique, from breaking text into tokens to pulling out named entities.

---

## Programs

### 1. Tokenization
**File:** `Tokenization.ipynb`

Splits raw text into sentences and words — the first step in almost any NLP pipeline.

**Covers:**
- Sentence tokenization
- Word tokenization

**Libraries:** NLTK, spaCy

---

### 2. Stemming & Lemmatization
**File:** `stemming_lemmatization.ipynb`

Reduces words to their root form using two different approaches.

- **Stemming** chops off word endings using rules, which can sometimes produce a form that isn't a real word.
- **Lemmatization** maps a word to its actual dictionary base form using vocabulary and grammar rules.

**Covers:**
- Porter Stemmer
- WordNet Lemmatizer

**Libraries:** NLTK

---

### 3. Stop-word Removal
**File:** `stopword_removal.ipynb`

Filters out frequently occurring words (like *the*, *is*, *a*, *and*) that usually carry little meaning on their own.

**Covers:**
- Word tokenization
- Identifying stop words
- Removing stop words from text

**Libraries:** NLTK

---

### 4. POS Tagging
**File:** `pos_tagging.ipynb`

Labels each word in a sentence with its grammatical role — noun, verb, adjective, and so on.

**Covers:**
- Word tokenization
- Assigning POS tags
- Grammatical categories (noun, verb, adjective, adverb, preposition, determiner)

**Libraries:** NLTK

---

### 5. Parsing & Chunking
**File:** `parsing_chunking.ipynb`

Looks at sentence structure beyond individual word tags — grouping words into phrases and mapping how they relate to each other.

**Covers:**
- Regex-based chunking
- Noun phrase extraction
- Dependency parsing
- Grammatical relationships between words

**Libraries:** NLTK, spaCy

---

### 6. Named Entity Recognition (NER)
**File:** `ner.ipynb`

Detects and labels real-world entities mentioned in text.

**Covers:**
- Identifying named entities
- Classifying entities (person, organization, location, date, money, GPE, etc.)

**Libraries:** spaCy

---

## Requirements

```bash
pip install nltk spacy
python -m spacy download en_core_web_sm
```

NLTK resources needed (downloaded automatically inside the notebooks):
- `punkt`, `punkt_tab`
- `stopwords`
- `averaged_perceptron_tagger_eng`
- `wordnet`, `omw-1.4`

## Running the Notebooks

Open any `.ipynb` file in:
- Jupyter Notebook / JupyterLab
- VS Code (with the Jupyter extension)
- Google Colab

Run the cells from top to bottom.

## Repository Structure

```
NLP-Programs-using-Python-NLTK-and-SPACY/
├── Tokenization.ipynb
├── stemming_lemmatization.ipynb
├── stopword_removal.ipynb
├── pos_tagging.ipynb
├── parsing_chunking.ipynb
├── ner.ipynb
└── README.md
```

## What You'll Learn

By working through these notebooks, you'll get hands-on practice with:

- Breaking text into sentences and words
- Reducing words to their root/base form
- Filtering out low-information words from text
- Tagging words with their grammatical role
- Grouping words into phrases and mapping relationships between them
- Detecting and classifying named entities in text

## Purpose

This repository was put together as a practical, code-first way to learn the building blocks of NLP. Rather than just reading about how text is processed, each notebook walks through applying a specific technique on real text, using two of the most widely used Python NLP libraries — NLTK and spaCy.

## Author

Anurag
