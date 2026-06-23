# Iris Species Classifier

A multiclass classification project predicting Iris flower species using Random Forest.

## Results
- Validation Accuracy: 100% (30 samples)
- Cross-validation Mean: 96.7% (+/- 0.021)

## Key Findings
- Petal length and petal width are the strongest predictors
- Setosa is easily separable from other species
- Versicolor and Virginica overlap, causing occasional misclassification

## Difference from Titanic Project
- Multiclass classification (3 classes) vs binary (2 classes)
- Clean dataset with no missing values or feature engineering needed
- Balanced classes (50 samples each)

## Tools Used
- Python 3.12, scikit-learn, pandas, matplotlib, seaborn

## How to Run
1. pip install -r requirements.txt
2. jupyter notebook
3. Open 01_iris_eda.ipynb and run all cells
