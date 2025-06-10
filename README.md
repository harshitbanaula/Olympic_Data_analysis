# Olympic_Data_analysis

This project analyzes 128 years of Olympic history using data from Kaggle. It explores trends in athlete performance, medal counts, gender participation, and country-wise achievements.

## Dataset

[120 Years of Olympic History: Athletes and Results] - https://www.kaggle.com/datasets/stefanydeoliveira/summer-olympics-medals-1896-2024

## Features

-  **Medal Tally by Country**  
  Summarized total medals (Gold, Silver, Bronze) won by each country.

- 🇮🇳 **Country-Specific Analysis**  
  Filtered medal performance for a specific country (e.g., India's gold medal history).

- **Data Cleaning & Integration**  
  - Merged datasets using `NOC`
  - Removed duplicates
  - Created dummy columns for medals

- **Machine Learning Model (Planned)**  
  Although commented in the current notebook, code includes:
  - Feature selection: `['Event', 'Sport', 'Team', 'NOC']`
  - Target: `City` (to predict Olympic host city)
  - Model: XGBoost Classifier with preprocessing and train-test split

## Tools Used

- Python
- Pandas
- Scikit-learn
- XGBoost
- SMOTE-ENN
- Matplotlib
- Seaborn
- Jupyter Notebook

