day 3

steps : 

Data split: Split data into training and testing sets and label-encoded the target.

Numerical pipeline: Imputed missing values and applied PowerTransformer() to numerical features.

Categorical pipeline: Imputed missing values and one-hot encoded categorical features.

Column transformer: Combined numerical and categorical transformers using ColumnTransformer.

Pipeline setup: Created a full pipeline with preprocessing and LinearRegression model.

Model training: Trained the pipeline using .fit() on training data.

Prediction: Predicted on test data and rounded the output for classification-style evaluation.

Accuracy check: Used accuracy_score to evaluate model predictions.

Cross-validation: Applied cross_val_score with cv=5 to assess generalization performance.

