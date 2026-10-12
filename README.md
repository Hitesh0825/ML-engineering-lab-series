# Machine Learning Engineering Lab Series

A practical machine learning project covering five end-to-end exercises using Python, Pandas, NumPy, Matplotlib, and Scikit-learn.

## Project Overview

This repository contains five machine learning exercises covering regression, classification, ensemble learning, and customer segmentation.

## Exercises

| No. | Exercise | Technique | Notebook | Documentation |
|---|---|---|---|---|
| 1 | Insurance Cost Prediction | Linear Regression | [Notebook](notebooks/01_insurance_cost_prediction.ipynb) | [README](exercise-readmes/Exercise-1-README.md) |
| 2 | Bank Marketing Classification | Logistic Regression | [Notebook](notebooks/02_logistic_regression.ipynb) | [README](exercise-readmes/Exercise-2-README.md) |
| 3 | Decision Tree Classification | Decision Tree | [Notebook](notebooks/03_decision_tree.ipynb) | [README](exercise-readmes/Exercise-3-README.md) |
| 4 | Bank Marketing Classification | Random Forest | [Notebook](notebooks/04_random_forest.ipynb) | [README](exercise-readmes/Exercise-4-README.md) |
| 5 | Wholesale Customer Segmentation | K-Means Clustering | [Notebook](notebooks/05_kmeans_clustering.ipynb) | [README](exercise-readmes/Exercise-5-README.md) |

## Technologies Used

- Python 3.12
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Jupyter Notebook
- Git and GitHub

## Repository Structure

```text
ml-engineering-lab-series-01/
├── data/
│   └── raw/
├── notebooks/
├── outputs/
├── exercise-readmes/
├── reports/
├── src/
└── requirements.txt
```

## Setup

Create and activate a Python virtual environment, then install dependencies:

```bash
python -m venv .venv
```

Windows PowerShell:

```powershell
.\.venv\Scripts\Activate.ps1
```

Install packages:

```bash
pip install -r requirements.txt
```

Open the notebooks in VS Code or Jupyter and run the cells in order.

## Key Results

- **Exercise 2:** ROC-AUC 0.8769 and recall 0.8552 at threshold 0.35; both specified targets passed.
- **Exercise 5:** Four-cluster model completed; StandardScaler silhouette score was 0.1885, below the target of 0.42.

See each exercise README and notebook for methodology, metrics, outputs, and limitations. Results for the remaining exercises should be verified from their executed notebook outputs.

## Notes

Datasets are located in `data/raw/`, and generated prediction and clustering outputs are stored in `outputs/`. Virtual environments should not be committed to Git.

## Author

Hitesh Sharma
