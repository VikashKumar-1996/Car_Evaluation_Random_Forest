# Car_Evaluation_Random_Forest
This repo dives into the well-known Car Evaluation dataset from the UCI Machine Learning Repository, turning raw attributes into smart decisions on whether a car deserves a proud “acceptable” badge or lands itself in the scrapyard pile.

📊 Dataset Overview

The Car Evaluation dataset contains categorical features describing key criteria used in evaluating a car:

Feature	Description
buying	Buying price of the car
maint	Maintenance cost
doors	Number of doors
persons	Passenger capacity
lug_boot	Luggage space
safety	Safety score

Target Variable:
class – Car acceptability categorized as: unacc, acc, good, vgood

🧠 Machine Learning Approach

The goal: Predict the car's acceptability class using classification models.

✅ Techniques Used

Random Forest Classifier

GridSearchCV for hyperparameter tuning

Evaluation with F1-score

Random Forest steps:

Train baseline RandomForest model

Use GridSearchCV to find the best parameters

Evaluate best model performance

🧪 Model Performance

Performance is measured using the macro F1-score (due to class imbalance).

Model	F1 Score (Macro)
Baseline Random Forest	~0.92 ✅
Tuned RF (GridSearchCV)	~0.96 🚀
