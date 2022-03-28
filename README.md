# Medical Papers Summarisation
Abstractive Summarisation of Long-form Medical Papers on the PubMed dataset by [Cohan et al. (2018)](https://arxiv.org/abs/1804.05685). The dataset may be download using: [Download](https://drive.google.com/file/d/1lvsqvsFi3W-pE1SqNZI0s8NR9rC1tsja/view?usp=sharing) ([mirror](https://archive.org/download/armancohan-long-summarization-paper-code/pubmed-dataset.zip)).

## Overview
The University of Bologna (UniBo) Artificial Intelligence in Industry (AIITI) project. In this project, we utilised the medical papers found in the PubMed dataset to compare different approaches for the abstractive summarisation of long-form documents.

Three different methods (Baseline, TextRank, SBERT + NSearch) were evaluated on the test set. Our results show that applying an initial extractive summarisation before a subsequent abstractive summarisation shows a small benefit in terms of the ROUGE scores.

The steps taken are described in detail in the [Report](https://github.com/LIA-UniBo/medical-papers-summarisation/blob/main/Report.pdf).

The code may also be viewed directly from the [Notebook](https://github.com/LIA-UniBo/medical-papers-summarisation/blob/main/main.ipynb).

## Results
The table below shows the results achieved in terms of the ROUGE scores.

|   Methodology   |  ROUGE-1  |  ROUGE-2  |  ROUGE-L  |
|:---------------:|:---------:|:---------:|:---------:|
|     Baseline    |     38.75 |     17.27 |     35.60 |
|     Textrank    |     39.10 |     17.15 |     35.67 |
| SBERT + NSearch |     38.92 |     17.12 |     35.59 |
