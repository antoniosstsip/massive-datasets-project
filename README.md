# Finding Similar Book Reviews

**Course:** Algorithms for Massive Datasets (2024/2025)  
**Student:** Antonios Tsipoulakos, Erasmus Student in Computer Science  
**University of Milan**

---

## 🔎 Project Overview

This project implements a basic similarity detector for Amazon book reviews, using **Jaccard Similarity** between tokenized texts.  
The algorithm is implemented entirely **from scratch**, without relying on external similarity libraries.

You can run the project directly in Google Colab:  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/antoniosstsip/massive-datasets-project/blob/main/final_project1.ipynb)

---

## 📂 Dataset

- **Source**: [Amazon Books Reviews on Kaggle](https://www.kaggle.com/datasets/rajeevw/amazon-books-reviews)
- **License**: Public domain (CC0)
- **Used file**: `Books_rating.csv`, column `review/text`

> 📌 The dataset is **downloaded dynamically** during notebook execution via Kaggle API. You must insert your own `KAGGLE_USERNAME` and `KAGGLE_KEY`. These should not be uploaded to the repository.

---

## ⚙️ What the Code Does

- Installs required libraries automatically in Colab
- Downloads and extracts dataset via Kaggle API
- Preprocesses text: lowercase, tokenize, remove empty rows
- Computes pairwise **Jaccard similarity from scratch**
- Displays top-5 most similar review pairs (text + score)
- Uses a global flag to **subsample for speed or scale up**

---

##  Experiments

- Tested with subsets of 100–500 reviews to ensure quick execution
- Computed over 4,950 pairwise combinations in small runs
- Notebook is fully executable in Colab within reasonable time

---

##  Scalability

- Uses a global variable `USE_SUBSAMPLE` to switch between fast runs and full dataset processing
- Structure generalizes to any number of reviews
- Suggestions for future improvement: TF-IDF, word embeddings, parallelization

---

##  Report

You can view the full report (PDF or LaTeX source) in the repository:
- `final_report.tex`
- `final_report.pdf`

---

##  Academic Declaration

> I declare that this material is entirely my own work and has not been taken from the work of others, save as cited and acknowledged. I understand and accept the consequences of plagiarism and confirm that no generative AI tool was used to write this code or report.

---

##  Requirements

- Python 3.7+
- Libraries: `pandas`, `numpy`, `matplotlib`, `kaggle`

---

##  Colab Link

Click here to open the notebook in Colab:  
📎 https://colab.research.google.com/github/antoniosstsip/massive-datasets-project/blob/main/final_project1.ipynb

---

## Contact

Antonios Tsipoulakos  
Erasmus Student in Computer Science – University of Milan

