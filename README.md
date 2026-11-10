# Titanic_training

This project uses a local virtual environment in `titanic/`.

Install the full ML stack for the notebook with:

```bash
./titanic/Scripts/python.exe -m pip install -r requirements.txt
```

Required packages include:
- pandas
- matplotlib
- seaborn
- scikit-learn
- xgboost

The Titanic notebook reads the CSV from `Rawdata/titanic_training_data_titanic_training_data.csv` and builds survival-prediction models with scikit-learn and XGBoost.
