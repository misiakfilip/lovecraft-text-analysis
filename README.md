# lovecraft-text-analysis
Text analysis of H.P. Lovecraft's works using NLP and sentiment analysis

This repository contains a natural language processing (NLP) analysis of selected works by H.P. Lovecraft. The goal of this project is to demonstrate text preprocessing, sentiment analysis, and word-level emotion analysis using Python.

## Project Overview

The analysis covers three of Lovecraft's texts:
- *The Call of Cthulhu*
- *The Dunwich Horror*
- *The Shadow over Innsmouth*

The NRC Emotion Lexicon was used to map words to emotions, enabling a detailed examination of sentiment distribution across the works. The project demonstrates common NLP techniques such as tokenization, lemmatization, and basic exploratory data analysis.

## How to Run

### Option 1: Run locally
1. Clone the repository:

git clone https://github.com/yourusername/lovecraft-text-analysis.git

2. Install dependencies:

pip install -r requirements.txt

3. Install en_core_web:

  python -m spacy download en_core_web_md

4. Open the Jupyter notebook or Python file:

### Option 2: Run on Google Colab
Click the link below to open the notebook directly in Colab:
[Open Lovecraft Analysis in Colab](https://colab.research.google.com/github/yourusername/lovecraft-text-analysis/blob/main/notebooks/lovecraft_analysis.ipynb)
