The workflow implemented in the notebook includes:

Data Preprocessing: Feature scaling using StandardScaler.

Validation Strategy: 5-fold StratifiedKFold cross-validation to ensure model reliability.

Modeling:

Standalone Model: A DecisionTreeClassifier.

Ensemble Model: A BaggingClassifier utilizing 100 Decision Trees.
