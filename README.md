<div align="center">

# Spanish Text Preprocessing with NLTK

**Natural Language Processing exercise: from raw text to a list of nouns**

<a href="https://colab.research.google.com/github/Steven-Macas/PLN/blob/main/mia_ejercicio_PLN.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open in Colab" /></a> <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python: 3" /> <img src="https://img.shields.io/badge/NLTK-NLP-154F5B?style=flat-square" alt="NLTK: NLP" /> <img src="https://img.shields.io/badge/Jupyter-Colab-F37626?style=flat-square&logo=jupyter&logoColor=white" alt="Jupyter: Colab" />

</div>

## Overview

A natural language processing pipeline applied to a Spanish text, built with **NLTK**.

## Pipeline

1. Conversion to lowercase.
2. Removal of accents with `unidecode`.
3. Tokenisation with `word_tokenize`.
4. Removal of Spanish stopwords (`nltk.corpus.stopwords`).
5. Part-of-speech tagging with `nltk.pos_tag`.
6. Filtering of the tokens to keep only nouns.

## How to run

Open the notebook in Colab with the badge above, or locally:

```bash
pip install nltk unidecode jupyter
jupyter notebook mia_ejercicio_PLN.ipynb
```

*The notebook is written in Spanish.*

---

<sub>Made by <b>Steven Macas</b> — Data Engineer &amp; Data Analyst · <a href="https://gointy.com">gointy.com</a> · <a href="https://www.linkedin.com/in/steven-macas">LinkedIn</a> · <a href="https://github.com/Steven-Macas">GitHub</a></sub>
