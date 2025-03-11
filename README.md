# Gout Flare Detection

This repository was developed by **I Made Akira Ivandio Agusta (15406525),** Coventry University.

This study investigates and evaluates machine learning algorithms for the early identification of gout flares using Emergency Department Chief Complaint data. The analysis uses two datasets stored in the **dataset** directory, namely **GOUT-CC-2019-CORPUS-SYNTHETIC** and **GOUT-CC-2020-CORPUS-SYNTHETIC**. The data were collected from [PhysioNet](https://physionet.org/content/emer-complaint-gout/1.0/).

The first notebook **(01 Gout Flare Detection—Feature Engineering & Machine Learning Algorithms)** evaluates different feature-classifier combinations, revealing that the Support Vector Machine algorithm with TF-IDF features delivers superior performance.

The second notebook **(02 Gout Flare Detection—SMOTE vs No SMOTE Comparison)** addresses the class imbalance in the datasets. The analysis demonstrates that applying SMOTE reduces overall model performance.

Based on the evaluation across both notebooks, this study concludes that the optimal approach for detecting gout flares from chief complaints is **SVM with TF-IDF features without implementing SMOTE oversampling.**
