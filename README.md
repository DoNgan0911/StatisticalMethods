# Medical Report Summarizer
Authors: Winta Yoseph, Kacie Do

Department: Information Science

Course: DTSC 4050: Statistical Methods for Data Science and Analysis

Instructor: Dr. Yang Zhang

Date: May 7th, 2025

## Project Overview
The healthcare industry is increasingly adopting advanced technologies to improve patient care. However, Electronic Health Records (EHRs) often contain lengthy and complex medical reports, which can slow down diagnosis and treatment. This project develops a Natural Language Processing (NLP) system that summarizes medical reports accurately and identifies key medical terms, thereby improving healthcare efficiency.

We utilize two models—TextRank for extractive summarization and Scispacy for domain-specific named entity recognition (NER). The system is evaluated against expert medical summaries using the ROUGE metric and precision/recall scores.

Features
1. Automated Medical Report Summarization: Uses the TextRank algorithm to extract key sentences without predefined keywords.

2. Domain-Specific Term Extraction: Implements Scispacy, a biomedical NLP model, to identify medical entities like diseases and chemicals.

3. Evaluation: Compares generated summaries with those from medical professionals using ROUGE scores and NER evaluation metrics.

4. Open-source Implementation: Available via a Google Colab notebook for easy experimentation.

## Dataset Information
We extracted four medical reports from publicly available datasets on Kaggle and MTSamples.com. These reports contain complex, lengthy medical language typical of Electronic Health Records. The dataset was used to develop and evaluate our summarization and entity recognition models.

## Motivation
Physicians spend significant time reviewing EHRs, averaging over 16 minutes per patient.

Medical reports are often long, complex, and prone to human error.

Faster, accurate summarization can accelerate medical decision-making and improve patient outcomes.

## Methodology
**TextRank**: A graph-based ranking model to select the most relevant sentences based on their relationships within the text.

**Scispacy**: An NLP model trained on biomedical data to identify domain-specific terminology and enhance summary relevance.

## Results
ROUGE-1 F1 score: 0.5467

This result demonstrates moderate agreement between generated summaries and expert summaries, with effective key term extraction.

## Limitations & Future Work
Extractive summarization may lead to coherence issues; integration of abstractive methods is a potential future direction.

Limited sample size for expert-generated summaries due to availability constraints.

Post-processing to address typographical errors and noisy data is necessary.

Collaboration with more medical experts could improve evaluation quality.

## How to Use
Access the code and run experiments on Google Colab:
Medical Report Summarizer Colab Notebook

Upload your own medical reports in the appropriate format to test summarization and entity extraction.

Modify parameters and models as needed to suit your dataset.

## References
A complete list of references is included in the project report file and covers all relevant literature and tools used.


Thank you for checking out our project!



