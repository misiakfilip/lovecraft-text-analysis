# lovecraft-text-analysis
Text analysis of H.P. Lovecraft's works using NLP and sentiment analysis

This repository contains a natural language processing (NLP) analysis of selected works by H.P. Lovecraft. The goal of this project is to demonstrate text preprocessing, sentiment analysis, and word-level emotion analysis using Python.

## Project Overview

The analysis covers three of Lovecraft's texts:
- *The Call of Cthulhu*
- *The Dunwich Horror*
- *The Shadow over Innsmouth*

The NRC Emotion Lexicon was used to map words to emotions, enabling a detailed examination of sentiment distribution across the works. The project demonstrates common NLP techniques such as tokenization, lemmatization, and basic exploratory data analysis.

## Repository Structure

lovecraft-text-analysis/
│
├── data/
│ ├── the_call_of_cthulhu.txt
│ ├── the_dunwich_horror.txt
│ ├── the_shadow_over_innsmouth.txt
│ └── NRC-Emotion-Lexicon-Wordlevel-v0.92.csv
│
├── notebooks/
│ └── lovecraft_analysis.ipynb
│
├── src/
│ ├── lovecraft_analysis.py
│
├── reports/
│ └── Lovecraft_NLP_Analysis_Report.pdf
│
├── README.md
