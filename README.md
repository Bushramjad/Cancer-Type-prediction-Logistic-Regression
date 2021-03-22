# Cancer Type prediction using LogisticRegression

Phase 0 — Data Preparation - Dataset from Kaggle is used. It contains 596 rows and 32 columns of tumor shape and specifications. The tumor is classified as benign or malignant based on its geometry and shape.

Phase 1 — Data Exploration - The dataset has 569 rows and 33 columns. All the values are non null.

Phase 2 — Encoding Categorical Data - Transform the categorical variable column (diagnosis) to a numeric type. sklearn’s LabelEncoder is used for this purpose. The M and B variables were changed to 1 and 0 by the label encoder.

Phase 3 — Feature Scaling - It fits the input data within a specific scale, like 0–100 or 0–1

Phase 4 — Model Selection - sklearn’s Logistic Regression is used to classify tumor as benign or malignant.

Phase 5 — Prediction

Phase 6 — Visualization
