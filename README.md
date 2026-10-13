# Machine_Learning_Rainfall_Prediction
Creating a Machine Learning Model to Predict Rainfall (COMP 542) - Group Members: George Patterson, Coby Jones, Ian Sherrill.

## Local dataset setup

The training dataset is supplied locally and is not included in this repository.
Place your CSV at `data/rainfall.csv` beside the script, or set
`RAINFALL_DATASET_PATH` to another CSV path. Relative custom paths resolve from
the current working directory.

Required columns: `Date`, `Location`, `Temperature`, `Humidity`, `Wind Speed`,
`Precipitation`, `Cloud Cover`, `Pressure`, and `Rain Tomorrow`.
The script normalizes column spaces to underscores before model training.
Use only datasets you are permitted to process.
