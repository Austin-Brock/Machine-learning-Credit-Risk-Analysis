# Machine-learning-Credit-Risk-Analysis
Machine learning project that analyzes customer credit history to predict loan default risk, identify high-risk borrowers, and help financial institutions make data-driven lending decisions.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
jupyter lab
```

## Data

This project uses the [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset) from Kaggle (32,581 rows, 12 columns).

Data files are not committed. Download the CSV and place it at:

```
data/raw/credit_risk_dataset.csv
```

## Project structure

```
data/raw/         original, untouched dataset
data/processed/   cleaned/transformed data
notebooks/        exploration and experiments
src/              reusable Python code
models/           trained model files
tests/            tests
```
