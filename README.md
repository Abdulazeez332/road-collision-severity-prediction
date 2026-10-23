# UK Road Collision Severity Prediction

A machine learning project comparing classification models for predicting UK road collision severity: fatal, serious, or slight. Includes the complete Jupyter notebook and project report.

## Features

- Data exploration, missing-value handling, and feature engineering.
- Training-only preprocessing with categorical encoding and numeric scaling.
- Comparison of a majority baseline, logistic regression, decision tree, random forest, and gradient boosting.
- Class imbalance experiments using class weights, undersampling, oversampling, and SMOTE.
- Evaluation with accuracy, macro F1, weighted F1, class recall, and confusion matrices.
- Feature importance, overfitting checks, and a separate data leakage diagnostic.

## Files

- [project-code.ipynb](project-code.ipynb) — complete analysis and model comparison.
- [project-report.pdf](project-report.pdf) — accompanying project report.
- [requirements.txt](requirements.txt) — Python packages for running the notebook.

## Setup

```bash
git clone https://github.com/Abdulazeez332/road-collision-severity-prediction.git
cd road-collision-severity-prediction
pip install -r requirements.txt
jupyter notebook project-code.ipynb
```

Place `dft-road-casualty-statistics-collision-2023.csv` beside the notebook, or update `DATA_PATH` in the notebook to your dataset location. The dataset is not included. Run the cells in order; charts are written to `outputs/charts/`.

The supplied notebook identifies the course as **AI306 – Data Mining**, although the original folder was named **AI361 Project**. Original notebook and report content is preserved. Model training was not rerun as part of repository preparation.
