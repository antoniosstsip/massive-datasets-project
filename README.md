# Finding Similar Book Reviews – Massive Datasets Project

This project was developed for the course **Algorithms for Massive Datasets** at the Master in Computer Science, University of Milan (2024/2025).

The goal is to implement a simple similarity detector between book reviews from the [Amazon Books dataset](https://www.kaggle.com/datasets/rajeevw/amazon-books-reviews), using **Jaccard similarity**, without relying on external similarity libraries.

---

## How to run

You can execute the project directly in **Google Colab** using the following badge:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/antoniosstsip/massive-datasets-project/blob/main/project1.ipynb)

> Make sure to insert your own Kaggle API credentials in the designated section in order to download the dataset (do not upload the dataset in the repository).

---

## What the code does

- Downloads and extracts the Amazon Books dataset (optional/manual alternative is possible).
- Preprocesses the reviews (removing missing values and tokenizing text).
- Computes Jaccard similarity from scratch between all pairs of reviews (subsampled for performance).
- Prints the top 5 most similar review pairs with their similarity scores.

---

##  Requirements

- Python 3.7+
- Pandas, NumPy
- Kaggle API (installed with `!pip install kaggle` in Colab)

---

## Structure

- `project1.ipynb` – main notebook with all code
- `README.md` – this file
- Dataset is downloaded dynamically (not included)

---
## Contents

- `project1.ipynb` – Main code with all logic
- `project1.pdf` – Final report (LaTeX generated)

## Author

Antonios Tsipoulakos , erasmus student in Computer Science, University of Milan
