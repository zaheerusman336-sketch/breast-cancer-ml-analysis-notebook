# Breast Cancer ML Analysis Notebook

A guided end-to-end machine learning project for analysing a breast cancer dataset using Python and Jupyter Notebook.

## Repository overview

This repository contains a revised notebook that walks through a complete classification workflow, from data loading and cleaning to dimensionality reduction and model comparison.

## Project contents

```text
breast-cancer-ml-analysis-notebook/
├── data/
│   ├── Data.xlsx
│   └── Data.csv
├── notebooks/
│   └── Usman_Project_revised.ipynb
├── docs/
│   └── repository_notes.md
├── .gitignore
├── requirements.txt
└── README.md
```

## What the notebook does

The notebook covers the following stages:

1. checks and installs required Python packages
2. loads an Excel or CSV dataset
3. inspects structure and missing values
4. removes non-informative identifier columns
5. explores the class distribution
6. generates summary statistics
7. detects and removes outliers
8. visualises feature distributions and relationships
9. builds a correlation heatmap
10. standardises numeric features
11. applies Principal Component Analysis (PCA)
12. prepares the modelling dataset
13. splits the data into training and testing sets
14. trains multiple classification models
15. compares model performance using common evaluation metrics

## Models included

The notebook compares these classifiers:

- Logistic Regression
- Support Vector Machine
- Decision Tree
- Random Forest
- K-Nearest Neighbors
- Naive Bayes
- Gradient Boosting

## Dataset details

The included dataset has:

- **569 rows**
- **32 columns**
- target column: **Diagnosis**
- identifier column: **ID**

The `Diagnosis` column is used as the prediction target. The `ID` column is treated as a non-informative identifier and removed before modelling.

## Requirements

Install the required packages with:

```bash
pip install -r requirements.txt
```

## How to run

### Option 1: Jupyter Notebook

```bash
jupyter notebook
```

Then open:

```text
notebooks/Usman_Project_revised.ipynb
```

### Option 2: VS Code

Open the repository folder in VS Code and run the notebook cell by cell.

## Notes

- The notebook is written to be beginner-friendly.
- It accepts `.xlsx`, `.xls`, and `.csv` files.
- Although the included data is a breast cancer dataset, the notebook structure can be adapted for similar classification datasets.

## Suggested repository name

`breast-cancer-ml-analysis-notebook`

## Suggested GitHub description

`A guided Jupyter notebook for breast cancer data analysis, PCA, and classification model comparison using Python.`

