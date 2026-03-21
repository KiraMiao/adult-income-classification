# Adult Income Classification with Scikit-learn

This project predicts whether an individual's income is above or below 50K using demographic and employment-related features from the Adult Census dataset.

## Dataset
- Adult Census Income dataset
- 32,561 rows
- 14 input features and 1 target column (`income`)

## Tools
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## Project Steps
- Loaded and explored the dataset
- Replaced `?` values with missing values
- Split features and target (`X` and `y`)
- Built preprocessing pipelines for numeric and categorical features
- Applied `SimpleImputer`, `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`, and `Pipeline`
- Trained and compared Logistic Regression and Random Forest classifiers
- Evaluated performance using accuracy, confusion matrix, precision, recall, and F1-score

## Model Results
- Logistic Regression achieved about 85.2% test accuracy
- Random Forest achieved about 85.1% test accuracy
- Random Forest slightly improved recall for the `>50K` class
- Class-weighted Logistic Regression significantly improved recall for the `>50K` class, with lower overall accuracy

## Key Learning
This project shows how preprocessing choices, class imbalance, and model selection affect classification performance.

## How to Run
1. Open the notebook `adult-income-classification.ipynb`
2. Install required Python packages such as pandas and scikit-learn
3. Run the notebook cells in order

## Main Models Compared
- Logistic Regression
- Random Forest Classifier
- Class-weighted Logistic Regression
