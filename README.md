# german credit risk project

*In this dataset, each entry represents a person receiving a loan from a bank. Each person is classified as a good or bad credit risk based on their qualifications.

*In this data, it was tried to struggle with IMBALANCED data.

*Data preprocessing

*Barplot, countplot, catplot and boxplot from matplotlib and seaborn libraries were used for visualization.

*In the visualizations, the variables were crossed with each other and the relationships between them were observed.

*The following models were created with the function called base_models;
  LogisticRegression,
  GaussianNB,
  KNN,
  LinearSVC,
  SVC,
  CART,
  RandomForest,
  GBM,
  XGBoost,
  LightGBM,
  CatBoost

*XGBoost model selected. The best parameters were found using the GridSearchCV method. The model has been tuned.

*While struggling with imbalanced data, PRECISION, RECALL, F1 SCORE, Cohen KAPPA SCORE, Matthews Corrcoef values were also examined in addition to the Accuracy value.

*Confusion Matrix created.

*ROC curve value and its graph was generated.
