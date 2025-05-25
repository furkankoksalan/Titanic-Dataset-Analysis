# Titanic Survival Prediction

Machine learning project to predict passenger survival on the Titanic using classification algorithms.

## Data

The dataset contains information about 891 passengers from the Titanic. Key features include passenger class, age, gender, fare, and family information.

## Approach

Started with exploratory data analysis to understand survival patterns. Found that gender and passenger class had strong correlation with survival rates. 

Created some new features like family size and extracted titles from passenger names. Tested different algorithms and Random Forest gave the best results.

## Results

Final model achieved 84% accuracy on test data. Most important features were:
- Gender (female passengers had much higher survival rate)
- Passenger class (first class passengers more likely to survive)  
- Age and fare also significant factors

## Files

- `titanic_analysis.ipynb` - main notebook with analysis
- `train.csv` - training data 
- `test.csv` - test data

## Kaggle Notebook

[View on Kaggle](https://www.kaggle.com/code/furkankoksalan/titanic-survival-prediction-analysis)

## Requirements

```
pandas
numpy  
scikit-learn
matplotlib
seaborn
```

## Usage

Run the notebook cells sequentially. Data files are included in the repository.

---

*Project completed for Akbank Machine Learning Bootcamp*
