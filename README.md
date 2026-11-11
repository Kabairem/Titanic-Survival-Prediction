# Titanic Survival Prediction

This project analyzes the Titanic dataset and compares several machine learning models to predict passenger survival.

## Project structure
- `Notebook/titanic.ipynb` — exploratory analysis and model training notebook
- `Rawdata/titanic_training_data_titanic_training_data.csv` — Titanic training dataset
- `requirements.txt` — Python dependencies for the notebook environment
- `titanic/` — local virtual environment used for the project

## Setup
Use the repository's local virtual environment to install dependencies:

```bash
./titanic/Scripts/python.exe -m pip install -r requirements.txt
```

If you are working from a different Python environment, you can also run:

```bash
pip install -r requirements.txt
```

## Dependencies
The project uses:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost

## Workflow
Open and run the notebook in `Notebook/titanic.ipynb` to:
- load the dataset
- clean and inspect the data
- train survival-prediction models
- compare model performance
