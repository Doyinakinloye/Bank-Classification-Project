🏦 Bank Classification Project

Predicting whether a client will subscribe to a bank term deposit using historical data. This project tackles real-world challenges like class imbalance, feature engineering, and threshold tuning—all at scale.

📌 Overview

- Goal: Binary classification of client subscription behavior.

- Dataset: Kaggle Playground Series S5E8

- Challenge: Only ~12% of clients subscribed, making this a highly imbalanced classification task.

🔍 Highlights

- 📊 EDA: Visualized patterns across job types, months, and contact methods.

🧼 Preprocessing:

- Ordinal, binary, and one-hot encoding

- Robust scaling for outlier resistance

🧠 Modeling:

- Compared XGBoost, RandomForest, Logistic Regression

- Stratified K-Fold CV for fair evaluation

- Hyperparameter tuning with RandomizedSearchCV

⚖️ Class Imbalance:

- Used BalancedBaggingClassifier to improve minority class recall

- Applied threshold moving to optimize F1 score

📈 Performance
- Model	ROC AUC	F1 Score
- XGBoost (tuned)	0.963	0.755
- BalancedBagging RF	0.952	0.696
💡 What I Learned
- How to diagnose and treat class imbalance using resampling and threshold tuning

- The importance of feature consistency between training and test sets

- How to scale ML workflows efficiently without compromising performance

- The value of metric selection in imbalanced contexts (F1 vs ROC AUC)

🛠 Tech Stack
- Python, Pandas, NumPy

- Scikit-learn, XGBoost, Imbalanced-learn

- Matplotlib, Seaborn

- Jupyter Notebook

💬 For Employers
- This project showcases my ability to:

- Handle large-scale, imbalanced datasets

- Build robust preprocessing and modeling pipelines

- Optimize models for real-world performance metrics

- Communicate insights clearly through visualizations and documentation

🤓 For Curious Minds
Ever wondered how banks decide who to market term deposits to? This project walks through the entire journey—from raw data to refined predictions—with transparency and reproducibility.
