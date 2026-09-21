# Project 2: Naive Bayes

CS-4103 Fundamentals of Machine Learning, University of Tulsa

## What is here

- `assignment/Assignment 2.1.ipynb` and `assignment/Assignment 2.2.ipynb`, the two notebooks you complete. 2.1 covers the two text variants on Spam/Ham and 20 Newsgroups. 2.2 covers the Gaussian and Categorical variants on the handwritten digits and the Titanic passengers.
- `data/`, the Spam/Ham emails and the Titanic passengers. The digits and 20 Newsgroups datasets download through scikit-learn the first time a notebook runs.
- `assignment/Project 2 - Naive Bayes.pdf`, the project spec. The same PDF is posted on Harvey.
- `assignment/Project 2 - Explainer.mp4`, a short silent animation of the four variants and how the equations in the spec fit together.

## Setup

Use Python 3.10 or newer.

```
pip install -r requirements.txt
jupyter notebook
```

Open the notebooks from the `assignment` folder. They load data through `../data`, so they fail if you move them or start them elsewhere.

## Working in the notebooks

The four Naive Bayes variants are already implemented, and so is the cross validation loop. Your job is to decide which variant fits each dataset, call the provided functions with the right arguments, run the matching scikit-learn class on the same folds, and write about what you see.

Fill in each `TODO`. The numbered comment above a `TODO` lists the steps that region needs.

Import nothing beyond the libraries listed in the import cell.

Run every cell, top to bottom, before you submit. 20 Newsgroups takes about a minute per variant.

## Submitting

Submit through Harvey:

- Both notebooks, with all outputs visible.
- The report PDF described in the spec.

A notebook with cleared outputs is graded as though the code did not run.
