This project presents a complete Natural Language Processing (NLP) preprocessing pipeline developed for mental health text analysis.

The pipeline transforms raw textual data into machine-learning-ready features through systematic preprocessing, linguistic normalization, feature engineering, and data quality assessment.

Although developed using mental health datasets, the workflow can easily be adapted to other NLP classification tasks.

1 Clean noisy textual data
2) Improve dataset quality
3 Detect duplicate records
4 Detect label conflicts
5 Normalize text using spaCy
6 Generate linguistic features
8 Produce machine-learning-ready datasets

| Tool | Purpose |
|-------|----------|
| Python | Programming |
| Pandas | Data manipulation |
| spaCy | NLP preprocessing |
| Scikit-learn | Feature extraction |
| Matplotlib | Visualization |
| Regex | Text cleaning |
| JSON | Reporting |

# NLP Pipeline

Raw Dataset

↓

Label Cleaning

↓

Duplicate Detection

↓

Conflict Detection

↓

Text Cleaning

↓

spaCy Tokenization

↓

Lemmatization

↓

Stopword Removal

↓

Feature Engineering

↓

CountVectorizer

↓

Machine Learning Ready Dataset


## Data Quality Checks

 Missing values

 Duplicate texts

 Label consistency

 Class distribution

 Text statistics

 Average word length

 Lexical diversity

 Emoji analysis

## NLP Preprocessing

The preprocessing workflow includes

- Lowercasing
- Whitespace normalization
- Tokenization
- Lemmatization
- Stopword removal
- Punctuation removal
- Short-token filtering

---

## Feature Engineering

The following features are extracted:

- Average Word Length
- Lexical Diversity
- Text Length
- Emoji Count
- N-grams (1–2)
- Bag-of-Words

---

## Visualization

The project generates:

- Class distribution
- Dataset statistics
- Data quality reports