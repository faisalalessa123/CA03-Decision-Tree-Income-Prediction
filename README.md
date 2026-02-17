# CA03 - Decision Tree (Census Income Classification)

## Purpose
This project builds and evaluates a Decision Tree classifier to predict whether an individual earns more than 50K per year (>50K) or 50K or less (<=50K) using census data. The notebook includes Data Quality Analysis (DQA), preprocessing and encoding, baseline model training, structured hyperparameter tuning, model evaluation (accuracy, precision, recall, F1, confusion matrix), tree visualization, and final prediction with probability output.

## Environment / Libraries Required
- Python 3.x
- pandas
- numpy
- matplotlib
- scikit-learn
- graphviz (optional for visualization)

## Versions Used
Developed and tested in Google Colab:
- Python 3.x
- pandas 1.x
- numpy 1.x
- scikit-learn 1.x
- matplotlib 3.x

## Dataset
Dataset: census_data.csv  
Source: https://github.com/ArinB/MSBA-CA-03-Decision-Trees/blob/master/census_data.csv?raw=true  
The dataset is loaded directly from the URL within the notebook.

## Acknowledgements
The model implementation uses sklearn.tree.DecisionTreeClassifier. No external code was reused beyond official Python libraries. This project was completed as part of the CA03 Decision Tree assignment.

## How to Install and Run

### Run in Google Colab (Recommended)
1. Open CA3.ipynb.
2. Run all cells from top to bottom.
3. The dataset loads automatically from the provided source URL.

### Run Locally
Install dependencies:
pip install pandas numpy matplotlib scikit-learn graphviz

Launch Jupyter:
jupyter notebook

Open CA3.ipynb and run all cells sequentially.
