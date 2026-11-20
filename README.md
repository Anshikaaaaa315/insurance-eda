# Medical Insurance Charges – EDA

Exploratory Data Analysis on a Medical Insurance dataset (1,338 records) to find out which factors drive insurance charges, and to prepare the data for Machine Learning.

**Dataset:** Medical Cost Personal Dataset (Kaggle)

## What I did
- Data overview: data types, missing values, duplicates
- Visualisation: distributions, countplots, boxplots, correlation heatmap
- Cleaning: removed duplicates, encoded categorical columns (binary + one-hot)
- Feature engineering: BMI categories (Underweight / Normal / Overweight / Obese)
- Feature selection: Pearson correlation and Chi-square test

## Key insights
- Smokers pay about **3.8x more** than non-smokers (correlation 0.79)
- Charges rise with **age** (correlation 0.30)
- Obese people pay about **1.5x more** than people with normal BMI
- Sex, region and number of children have only a weak effect

## Tools
Python, Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn

## How to run
```bash
pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
jupyter notebook insurance_eda.ipynb
```

## Next steps
Train and compare regression models (Linear Regression, Random Forest) to predict charges.
