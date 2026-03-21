{\rtf1\ansi\ansicpg936\cocoartf2868
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Adult Income Classification with Scikit-learn\
\
This project predicts whether an individual's income is above or below 50K using demographic and employment-related features from the Adult Census dataset.\
\
## Dataset\
- Adult Census Income dataset\
- 32,561 rows\
- 14 input features and 1 target column (`income`)\
\
## Tools\
- Python\
- pandas\
- scikit-learn\
- Jupyter Notebook\
\
## Project Steps\
- Loaded and explored the dataset\
- Replaced `?` values with missing values\
- Split features and target (`X` and `y`)\
- Built preprocessing pipelines for numeric and categorical features\
- Applied `SimpleImputer`, `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`, and `Pipeline`\
- Trained and compared Logistic Regression and Random Forest classifiers\
- Evaluated performance using accuracy, confusion matrix, precision, recall, and F1-score\
\
## Model Results\
- Logistic Regression achieved about 85.2% test accuracy\
- Random Forest achieved about 85.1% test accuracy\
- Random Forest slightly improved recall for the `>50K` class\
- Class-weighted Logistic Regression significantly improved recall for the `>50K` class, with lower overall accuracy\
\
## Key Learning\
This project shows how preprocessing choices, class imbalance, and model selection affect classification performance.}