# Spam Classification Using Positive von Mises–Fisher Distribution

This project applies text processing and statistical modeling techniques to classify spam emails using the Enron dataset. 
It compares a Positive von Mises–Fisher (PvMF) model with traditional logistic regression.

## Features
- Bag-of-words preprocessing and cleaning
- PvMF likelihood-based spam classification
- Logistic regression comparison
- Evaluation using accuracy, precision, and recall
- Visual confusion matrices

## Folder Structure
- `notebooks/`: Jupyter notebook with full workflow
- `src/`: Python scripts for preprocessing, modeling, and evaluation
- `plots/`: Output plots from the notebook
- `data/`: Placeholder folder for the Enron dataset

## Setup
```bash
pip install -r requirements.txt
```

> Note: This project requires R and the `rotasym` + `DirStats` packages for PvMF modeling via rpy2.

## Data
The Enron dataset is not included due to size. You can obtain it from:
https://www.cs.cmu.edu/~enron/

Extract `enron1.tar.gz` into `data/` and update paths if needed.
