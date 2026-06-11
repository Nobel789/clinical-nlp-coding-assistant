# Clinical NLP & Note Coding Assistant

## Overview
This repository contains a series of Jupyter Notebooks demonstrating Natural Language Processing (NLP) techniques applied to healthcare data. The primary focus is on automating clinical documentation, extracting vital medical information, and mapping raw clinical notes to standardized medical codes.

## Project Architecture
The project progresses from basic text extraction to advanced validation using Transformer models, broken down into the following workflows:

1. **Automated Documentation & Extraction:** Core NLP techniques for pulling structured data from unstructured clinical text.
2. **Note Coding Assistant:** Systems designed to map raw clinical language to potential coded outputs (e.g., billing or research codes).
3. **ClinicalBERT Validation:** Leveraging a domain-specific Large Language Model (ClinicalBERT) to validate mapped codes by understanding complex clinical language patterns beyond simple keyword rules.
4. **Reporting:** Generating clean, simple reports from the mapped coding data.

## Repository Contents
* `notebooks/`: Contains the step-by-step Jupyter Notebook pipeline (numbered 01 through 07).
* `clinical_reporting_research_code_candidates.csv`: The dataset containing the candidate codes used for mapping and validation throughout the notebooks.

## How to Use
To explore this project, clone the repository and open the notebooks in order. Ensure you have standard data science and NLP libraries installed (e.g., `pandas`, `transformers`, `nltk`, or `spacy` depending on the specific notebook dependencies).

> **Disclaimer:** All clinical notes and data used in these notebooks are for educational and practice purposes only. They contain no real Patient Health Information (PHI) or Personally Identifiable Information (PII).
