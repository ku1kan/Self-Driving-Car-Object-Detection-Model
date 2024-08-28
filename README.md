# Self-Driving-Car-Object-Detection-Model

This repository contains Python code for training and validating a decision tree classifier to predict object classes in self-driving car scenarios. The model uses bounding box coordinates (xmin, xmax, ymin, ymax) as features to classify objects into specific categories (class_id). The dataset is split into training and validation sets to evaluate the model's performance.

Key Components:
Data Handling: CSV files (labels_train.csv, labels_val.csv) are read into Pandas DataFrames to facilitate training and validation.

Model Training: A Decision Tree Classifier is utilized to learn patterns from the training data.

Evaluation: Training accuracy is calculated using accuracy_score, and validation accuracy is measured to assess model generalization.

Visualization: The trained decision tree is exported to a .dot file (Self_Driving_Car_Predictions.dot) for visualization using Graphviz.

Files:
labels_train.csv: Contains training data with object labels and bounding box coordinates.
labels_val.csv: Contains validation data for evaluating model performance.
Usage:
To replicate the experiment or explore the implementation details, clone the repository and execute the Python script. Ensure the necessary dependencies (pandas, scikit-learn) are installed.

License:
This project is licensed under the MIT License, allowing for further modification and distribution.
