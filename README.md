# Codsoft-3_CREDIT-CARD-FRAUD-DETECTION
This repository contains a machine learning project aimed at identifying fraudulent credit card transactions. The project involves preprocessing and normalizing transaction data, handling class imbalance issues, and training a classification algorithm to classify transactions as fraudulent or genuine.


Overview
Credit card fraud detection is a crucial task in the financial sector. This project leverages machine learning techniques to build a model that can accurately identify fraudulent transactions based on transaction data. The dataset used for this project is sourced from Kaggle and contains credit card transactions made by European cardholders in September 2013.

Dataset
The dataset contains the following key features:

Time: Number of seconds elapsed between this transaction and the first transaction in the dataset
V1, V2, ..., V28: Principal components obtained with PCA (to protect confidentiality)
Amount: Transaction amount
Class: Label indicating if the transaction is fraudulent (1) or genuine (0)

Running the Notebooks
The project is divided into Jupyter notebooks for easy understanding and modularity:

Data Exploration: 01-data-exploration.ipynb

Initial data loading and exploration.
Visualizing data distributions and relationships.
Data Preprocessing: 02-data-preprocessing.ipynb

Handling missing values and normalizing features.
Addressing class imbalance using techniques like SMOTE.
Model Building: 03-model-building.ipynb

Training various machine learning models (Logistic Regression, Random Forest).
Hyperparameter tuning.
Model Evaluation: 04-model-evaluation.ipynb

Evaluating model performance using metrics such as accuracy, precision, recall, and F1-score.
Prediction: 05-prediction.ipynb

Making predictions on new data.
Scripts
data_preprocessing.py: Contains functions for preprocessing the data.
model.py: Contains functions for building and training the machine learning models.
utils.py: Utility functions used across the project.
Results
The final model performance and predictions are stored in the results/ directory. Detailed evaluation metrics and model selection rationale are documented in the 04-model-evaluation.ipynb notebook.

Evaluation Metrics
Key metrics used for model evaluation include:

Precision: The ratio of true positive predictions to the total predicted positives.
Recall: The ratio of true positive predictions to the actual positives.
F1-score: The harmonic mean of precision and recall, giving a balanced measure of the model's performance.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.


Acknowledgments
The dataset is provided by the Machine Learning Group - ULB (Kaggle).
Inspiration and guidance from various online tutorials and courses on machine learning and data science.
