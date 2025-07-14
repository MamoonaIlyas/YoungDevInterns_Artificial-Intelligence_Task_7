# YoungDevInterns_Artificial-Intelligence_Task_7
 Develop an Advanced Model with Hyperparameter Tuning  Task: Optimize a complex model using hyperparameter tuning.  Details:  Use GridSearchCV or RandomizedSearchCV to find the best hyperparameters.  Train and evaluate a model such as a Random Forest or Gradient Boosting.
📌 Overview
This project focuses on building and optimizing a Random Forest Classifier to categorize cereal ratings into Low, Medium, and High using nutritional data. The model is tuned using GridSearchCV and evaluated with a detailed classification report.

📊 Dataset
File: preprocessed_cereal.csv

Features: Nutritional values (calories, sugar, protein, etc.)

Target: rating_class (derived from continuous rating field using binning)

⚙️ Methodology
🔹 Preprocessing
Binned the rating column into 3 categories: Low, Medium, High

Applied LabelEncoder to encode target labels

Performed a stratified train-test split for balanced class distribution
