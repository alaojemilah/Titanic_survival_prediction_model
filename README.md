## Titanic Survival Prediction Model

## Problem Statement
The Titanic dataset contains information about passengers aboard the Titanic. The goal of this project is to build a machine learning model that predicts whether a passenger survived or did not survive.

This is a *classification problem* so the output belongs to one of the two categories:
- *1* = Survived
- *0* = Did not survive

## Dataset
- *Source:* Titanic dataset (my fellowship)
- *Features used:* Passenger details including pclass, sex, age, sibsp, and fare

## What I Did
- Imported and explored the data
- Preprocessed and cleaned the data
- Split the data into training and test sets (80/20 split)
- Scaled features using feature scaling
- Trained multiple machine learning models
- Created a predict function to test on unseen data
- Performed hyperparameter tuning on the best model

## Models Tested & Results

| Model | Accuracy |
|---|---|
| Logistic Regression | 76.97% |
| Decision Tree | *80.34%* |
| Random Forest | 79.78% |
| SVM | 77.53% |
| Pipeline | 76.97% |

## Best Model
The *Decision Tree* achieved the highest accuracy of *80.34%*. After hyperparameter tuning the accuracy was 80.33%, confirming the model was already well optimised.

## Key Takeaways
- The model performed well on unseen data
- Hyperparameter tuning showed minimal improvement, meaning the base model was already solid
- Feature scaling and proper data splitting were key to reliable results

## Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn

## Author
Jemilah Alao | Data Analyst
[LinkedIn](https://www.linkedin.com/in/jemilah-alao-8a684528a)
